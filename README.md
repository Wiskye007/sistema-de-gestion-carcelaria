Sistema de Gestión Carcelaria (SGC) - Carceleta San Martín
Sistema web full-stack desarrollado para la administración, control de seguridad, seguimiento médico y gestión de usuarios de la Carceleta San Martín.

Tecnologías Utilizadas
- Frontend: Next.js (App Router), React, Tailwind CSS, Shadcn UI, Lucide Icons.Backend: Python, Flask, Flask-JWT-Extended, Werkzeug Security.
- Base de Datos: PostgreSQL / SQL con gestor de conexiones dedicado.

Características principales
- Autenticación y Seguridad: Control de acceso basado en roles (Administrador, Supervisor, Guardia, Médico) con tokens JWT.  
- Control de Sesiones en Tiempo Real: Monitoreo dinámico de usuarios en línea y offline mediante sistema de pings y filtrado estricto.
- Panel de Convictos: Registro, control de estados (Procesado/Condenado), niveles de peligrosidad, historial de movimientos, conducta y visitas.
- Panel Médico: Gestión de revisiones pendientes, casos urgentes, tratamientos activos y diagnósticos.
- Panel de Seguridad: Control táctico de pabellones, ocupación en tiempo real y registro de incidencias.
- Panel de Reportes: Visualización de métricas y estadísticas consolidadas del sistema.Panel de
- Personalización de la experiencia de usuario (tamaño de fuente, densidad de tablas, pantalla de inicio predeterminada y soporte para Modo Claro / Modo Oscuro).  
- Herramientas de Sistema (Admin): Verificación del estado del servidor, exportación de respaldos y generación de reportes de logs.

Instalación y configuración local:
1. Clonar el repositorioBashgit clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
2. Configurar el Backend (Flask)Bashcd Backend
# Crear y activar entorno virtual
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate

# Instalar dependencias
pip install -r requirements.txt

# Configurar variables de entorno (.env)
# Define tu conexión a la base de datos y credenciales SMTP

# Ejecutar servidor de desarrollo
python app.py
3. Configurar el Frontend (Next.js)Bashcd Frontend
# Instalar dependencias
npm install

# Ejecutar servidor de desarrollo
npm run dev

Licencia:
Este proyecto es de uso académico y profesional para la gestión interna de seguridad.
