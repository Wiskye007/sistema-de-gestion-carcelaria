Sistema de Gestión Carcelaria (SGC) - Carceleta San Martín: 
Sistema web full-stack desarrollado para la administración, control de seguridad, seguimiento médico y gestión de usuarios de la Carceleta San Martín.

Tecnologías utilizadas
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
Capturas:
<img width="1472" height="761" alt="image" src="https://github.com/user-attachments/assets/653f938a-273b-49fd-9d3f-e61fc78d7e95" />
<img width="1863" height="853" alt="image" src="https://github.com/user-attachments/assets/ce924bbe-0c09-4c56-81f0-e85c017bf8ad" />
<img width="1873" height="880" alt="image" src="https://github.com/user-attachments/assets/c403d051-eaf8-4a2d-994e-c5148479d4c2" />
<img width="1887" height="892" alt="image" src="https://github.com/user-attachments/assets/5c1ef617-bd2e-4139-8218-c80942966cb0" />

# Instalación y configuración local:
1. Clonar el repositorio:
git clone https://github.com/tu-usuario/tu-repositorio.git →
cd tu-repositorio
3. Configurar el Backend (Flask):
cd Backend → python -m venv venv → venv\Scripts\activate → pip install -r requirements.txt → python app.py
4. Configurar el Frontend (Next.js):
cd Frontend → npm install → npm run dev

Licencia:
Este proyecto es de uso académico y profesional para la gestión interna de seguridad.
