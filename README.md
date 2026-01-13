# ChambaYa - Marketplace Inteligente de Servicios

> Aplicación web optimizada para móviles que conecta proveedores de servicios técnicos (Chambistas) con clientes en Venezuela. Construida con un ecosistema de confianza basado en sistema de reputación robusto, gamificación y validación asistida por IA.

## 🚀 Características Principales

### 🔐 Sistema de Confianza
- **Verificación de identidad** con cédula venezolana y multimedia
- **Puntaje de confianza** calculado automáticamente (1-100 puntos)
- **Sistema de reputación** con calificaciones mutuas y evidencia visual
- **Moderación automática** para mantener calidad del servicio

### 🎮 Gamificación Avanzada
- **Niveles de Prestigio**: Bronce → Plata → Oro con beneficios progresivos
- **Sistema de Logros**: Relámpago, Perfeccionista, Local Hero
- **Penalizaciones inteligentes**: "Bajo Radar" con rehabilitación automática
- **Barra de progreso** para engagement continuo

### 💰 Pagos Seguros Localizados
- **Pago Móvil** con instrucciones específicas venezolanas
- **Binance** para pagos con criptomonedas
- **Confirmación bilateral** para máxima seguridad
- **Estados de pago** transparentes y trazables

### 📱 Optimizado para Móviles
- **Diseño responsivo** desde 320px
- **Gestos táctiles** intuitivos
- **Funcionalidad offline** con sincronización
- **Carga rápida** optimizada para conexiones 3G

## 🏗️ Arquitectura Técnica

### Stack Tecnológico
- **Frontend**: React 18 + TypeScript + Tailwind CSS + Framer Motion
- **Backend**: Supabase (PostgreSQL + Auth + Storage + Realtime)
- **Testing**: fast-check (Property-Based Testing) + Jest (Unit Testing)
- **Deployment**: Vercel (Frontend) + Supabase Cloud (Backend)

### Base de Datos
- **PostgreSQL** con funciones SQL avanzadas
- **Row Level Security (RLS)** para seguridad
- **Triggers automáticos** para gamificación y moderación
- **Índices optimizados** para búsquedas rápidas

## 📋 Especificaciones del Proyecto

Este proyecto sigue la metodología de **Desarrollo Dirigido por Especificaciones** con documentación completa:

### 📄 Documentos de Especificación
- **[requirements.md](.kiro/specs/chamba-ya-marketplace/requirements.md)**: 12 requisitos con criterios EARS
- **[design.md](.kiro/specs/chamba-ya-marketplace/design.md)**: Arquitectura completa + 47 propiedades de corrección
- **[tasks.md](.kiro/specs/chamba-ya-marketplace/tasks.md)**: Plan de implementación con 16 tareas principales

### 🧪 Testing Strategy
- **Property-Based Testing**: 47 propiedades de corrección universales
- **Unit Testing**: Casos específicos y edge cases
- **Integration Testing**: Flujos end-to-end críticos
- **Cobertura objetivo**: 90%+ en lógica de negocio

## 🎯 Funcionalidades Clave

### Para Chambistas (Técnicos)
- ✅ Registro con verificación de identidad
- ✅ Sistema de niveles y logros
- ✅ Gestión de presupuestos y trabajos
- ✅ Seguimiento de reputación en tiempo real
- ✅ Acceso a soporte prioritario (nivel Oro)

### Para Clientes
- ✅ Búsqueda inteligente con IA
- ✅ Filtros avanzados (ubicación, precio, disponibilidad)
- ✅ Sistema de calificaciones con evidencia visual
- ✅ Pagos seguros localizados
- ✅ Historial completo de servicios

### Para Administradores
- ✅ Moderación automática de perfiles
- ✅ Sistema de reportes de fraude
- ✅ Analytics de reputación y engagement
- ✅ Gestión de capacitaciones y rehabilitación

## 🚀 Comenzar Desarrollo

### Prerrequisitos
- Node.js 18+
- npm o yarn
- Cuenta de Supabase
- Git

### Instalación
```bash
# Clonar el repositorio
git clone https://github.com/[tu-usuario]/ChambaYa-App.git
cd ChambaYa-App

# Instalar dependencias
npm install

# Configurar variables de entorno
cp .env.example .env.local
# Editar .env.local con tus credenciales de Supabase

# Ejecutar en desarrollo
npm run dev
```

### Configuración de Supabase
1. Crear proyecto en [supabase.com](https://supabase.com)
2. Ejecutar scripts SQL del archivo `design.md`
3. Configurar políticas RLS
4. Añadir credenciales a `.env.local`

## 📊 Roadmap de Implementación

### Fase 1: Fundación (Tareas 1-4)
- [x] Configuración del proyecto
- [x] Esquema de base de datos
- [x] Sistema de autenticación
- [ ] Gestión de perfiles

### Fase 2: Core Features (Tareas 5-8)
- [ ] Sistema de búsqueda
- [ ] Gestión de trabajos
- [ ] Sistema de pagos
- [ ] Checkpoint intermedio

### Fase 3: Gamificación (Tareas 9-12)
- [ ] Sistema de reputación
- [ ] Niveles y logros
- [ ] Penalizaciones y capacitaciones
- [ ] Moderación automática

### Fase 4: Optimización (Tareas 13-16)
- [ ] Optimizaciones móviles
- [ ] Manejo de errores
- [ ] Testing completo
- [ ] Checkpoint final

## 🤝 Contribuir

1. Fork el proyecto
2. Crear rama feature (`git checkout -b feature/nueva-funcionalidad`)
3. Commit cambios (`git commit -m 'Añadir nueva funcionalidad'`)
4. Push a la rama (`git push origin feature/nueva-funcionalidad`)
5. Abrir Pull Request

### Estándares de Código
- **TypeScript** estricto
- **ESLint + Prettier** para formato
- **Conventional Commits** para mensajes
- **Property-Based Tests** para nuevas funcionalidades

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para detalles.

## 👥 Equipo

- **Desarrollador Principal**: [Tu Nombre]
- **Arquitecto de Software**: Kiro AI
- **Metodología**: Desarrollo Dirigido por Especificaciones

## 📞 Contacto

- **Email**: [tu-email]
- **LinkedIn**: [tu-linkedin]
- **Twitter**: [tu-twitter]

---

**ChambaYa** - Conectando talento venezolano con oportunidades reales 🇻🇪

## 🔗 Enlaces Útiles

- [Documentación de Supabase](https://supabase.com/docs)
- [Guía de React + TypeScript](https://react-typescript-cheatsheet.netlify.app/)
- [Tailwind CSS](https://tailwindcss.com/docs)
- [fast-check (Property-Based Testing)](https://fast-check.dev/)

## 📈 Métricas del Proyecto

- **Líneas de especificación**: ~2,000
- **Propiedades de corrección**: 47
- **Tablas de base de datos**: 12
- **Componentes React estimados**: ~50
- **Tiempo estimado de desarrollo**: 8-12 semanas