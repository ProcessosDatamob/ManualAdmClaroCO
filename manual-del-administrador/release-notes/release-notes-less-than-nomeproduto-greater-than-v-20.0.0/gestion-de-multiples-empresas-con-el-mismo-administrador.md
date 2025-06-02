# Gestión de Múltiples Empresas con el Mismo Administrador

**Acceso al Portal con Múltiples Empresas Vinculadas**\
Ahora, los administradores que tienen acceso a más de una empresa pueden gestionarlas todas con un único inicio de sesión. Las principales novedades incluyen:

* **Selección de Empresa en el Inicio de Sesión**: Al ingresar al portal, el sistema mostrará una lista con todas las empresas vinculadas al usuario, incluyendo información como el nombre de la empresa, el RFC y el plan contratado.
* **Acceso Directo**: Tras seleccionar una empresa, el portal se cargará con los datos y funcionalidades específicos de esa empresa.
* **Cambio Rápido de Empresa**: Dentro del portal, es posible alternar entre empresas en cualquier momento, facilitando la gestión centralizada de múltiples organizaciones.

Esta funcionalidad proporciona mayor agilidad y practicidad para quienes administran múltiples empresas en el sistema.\
Más información en la sección **Primer Acceso y Vínculo al Enterprise**.

**Auditoría para Usuarios con Múltiples Empresas**\
El sistema ahora registra y muestra correctamente los logs de auditoría de usuarios vinculados a más de una empresa. Con esta mejora:

* **Auditoría por Empresa**: Toda acción realizada dentro de una empresa será registrada y visible únicamente en esa empresa, incluso si el usuario administrador está vinculado a otras.
* **Auditoría Antes del Inicio de Sesión**: Las acciones auditables ejecutadas antes del inicio de sesión serán registradas en la primera empresa asociada al usuario.

Esta actualización garantiza una trazabilidad clara y precisa de las acciones de los administradores en entornos con múltiples empresas.\
Más información en la sección **Auditoría**.

**Creación de Múltiples Empresas con el Mismo Administrador**\
Ahora el portal del operador permite crear varias empresas utilizando el mismo correo electrónico de administrador. Si el sistema detecta que el correo ya está vinculado a otro usuario, mostrará un mensaje informando que ese usuario también tendrá acceso a la nueva empresa. Al confirmar, el sistema vincula automáticamente al usuario existente con la nueva empresa, sin necesidad de crear un nuevo acceso ni restablecer la contraseña.

Esta mejora facilita la gestión de múltiples empresas por parte de un solo administrador, manteniendo todo centralizado en un único inicio de sesión.
