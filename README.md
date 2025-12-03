## Instrucciones para ejecutar el proyecto 

### 1. Clonar el repositorio 

(https://github.com/ThyBrim/Uso-de-ASP-NET-Core)

2. Abrir el proyecto 
  * Abre la solución en Visual Studio o Visual Studio Code. 
3. Configurar la base de datos 
  * Actualiza la cadena de conexión en appsettings.json según tu entorno. 
  * Ejecuta las migraciones: 
      dotnet ef database update 
4. Ejecutar la aplicación 
dotnet run 
Accede a la aplicación en:\ http://localhost:5000 
�
� Tecnologías utilizadas 
• ASP.NET Core 7.0 
• Entity Framework Core 
• SQL Server 
• Bootstrap para diseño responsivo 
Estructura del proyecto 
ProyectoASPNetCore/ 
│ 
├──    
├──    
├──    
├──    
Controllers/ 
Models/      
Views/       
wwwroot/            
       # Controladores MVC 
       # Modelos de datos 
       # Vistas Razor 
# Recursos estáticos (CSS, JS) 
├── appsettings.json       # Configuración 
└── README.md              # Documentación del proyecto 
Credenciales de prueba 
• Usuario: demo@correo.com 
• Contraseña: Demo123! 
