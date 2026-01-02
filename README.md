# Medican - Sistema de Gestión Veterinaria

Este proyecto es un sistema de escritorio para la gestión de una clínica veterinaria, desarrollado en Java utilizando el patrón MVC (Modelo-Vista-Controlador).

## 📄 Licencia y Derechos de Autor

Este proyecto es de **CÓDIGO ABIERTO** para fines educativos y de aprendizaje. Puede ser estudiado, modificado y distribuido libremente.

> [!IMPORTANT]
> **Aviso sobre Imágenes:** Las imágenes, iconos y recursos gráficos utilizados en este proyecto pertenecen a sus respectivos autores y diseñadores. No se reclaman derechos de propiedad sobre estos recursos visuales. Si planea utilizar este software con fines comerciales, asegúrese de reemplazar estos recursos o adquirir las licencias correspondientes.

## 🚀 Requisitos de Ejecución

Para ejecutar este proyecto correctamente en su entorno local, necesita las siguientes herramientas:

*   **IDE:** Apache NetBeans (versión 12.0 o superior recomendada).
*   **JDK:** Java Development Kit (versión 8 o superior).
*   **Base de Datos:** PostgreSQL.

## ⚙️ Configuración

Antes de compilar y ejecutar la aplicación, es **OBLIGATORIO** configurar las credenciales de acceso a la base de datos en el código fuente.

1.  Abra el proyecto en NetBeans.
2.  Navegue al archivo de conexión: `src/Modelo/Conexion.java`.
3.  Busque las líneas donde se definen las variables de conexión y actualícelas con su usuario y contraseña de PostgreSQL local:

```java
// src/Modelo/Conexion.java

String cadenaConexion = "jdbc:postgresql://localhost:5432/medican"; // Verifique el puerto y nombre de BD
String pgUsuario = "postgres";  // <--- Ponga aquí su usuario
String pgPassword = "test1234"; // <--- Ponga aquí su contraseña
```

4.  Asegúrese de cargar el script de la base de datos (si está disponible) en su servidor PostgreSQL para crear la estructura de tablas necesaria.


## 👥 Contribuidores

<a href="https://github.com/KLPaul">
  <img src="https://avatars.githubusercontent.com/KLPaul" width="80" style="border-radius:50%">
</a>
<br>
[@KLPaul](https://github.com/KLPaul)
