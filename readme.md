# Autenticacion vs Autorizacion

Autenticacion y autorizacion son procesos vitales de seguridad de informacion los cuales son usados para proteger sistemas e informacion.

## Resumen

- Autenticacion verifica la identidad del usuario o de un servicio.

- Autorizacion determina los accesos permitidos.

## ¿Qué es Autenticación (AuthN)?

Autenticacion (AuthN) es un proceso el cual verifica si alguien o algo es ser quien dice ser. Los sistemas usualmente usan alguna forma de autenticación para asegurar el acceso a una aplicación o a su información.

### Ejemplo

Cuando necesito acceso a un sitio online o a un servicio, usualmente tengo que registrar mi usuario y una contraseña. Tras bambalinas, el sistema compara los datos que yo ingresé con los registros que posee en su base de datos. Si la información ingresada hace match, el sistema asume que mis datos son válidos y me da acceso. En este ejemplo, el sistema de autenticación supone que solo yo conozco las credenciales correctas. Por lo tanto, me autentica usando el principio de algo que solo yo sabría.

## ¿Cuál es el propósito de la Autenticación?

En cuestión, verificar que alguien o algo sea quien dice ser. Existen muchas formas de autenticación.

### Ejemplo

En el mundo del arte cuenta con procesos e instituciones que confirman que una pintura o escultura es el trabajo de un artista en particular. De la misma forma, los gobiernos usa distintas técnicas de autenticación para proteger de falsificación a su moneda. En esencia, la autenticación protege objetos de valor, y en esta época de la información en la que vivimos, resguarda sistemas y datos.

## ¿Qué es Autenticación de Identidad?

Es el proceso de verificar la identidad de un usuario o un servicio. Basado en esta información, un sistema provee al usuario con el acceso apropiado.

### Ejemplo

Supongamos que tenemos a dos personas trabajando en una cafetería, Ana y Juan. Ana es la manager del negocio, mientras que Juan es el barista. La cafetería usa un sistema Point of Sale (POS) en el cual meseros y baristas pueden colocar ordenes por ser preparadas. En este ejemplo, el POS usaría algún proceso para verificar la identidad de Ana y Juan antes de permitirles acceso al sistema. En algún caso podría preguntar por el nombre de usuario y una contraseña, o tal vez podría solicitar el escaneo del pulgar o algún lector de huellas digitales. Como la cafetería necesita proteger al acceso al POS, los empleados que utilizan el sistema deben verificar su identidad a través de un proceso de autenticación.

## Tipos comunes de autenticación

Los sistemas puedan usar muchos mecanismos para autenticar al usuario. Es común, para verificar la identidad, que el proceso de autenticación use:

1. Algo que tu sepas.
2. Algo que tu tengas.
3. Algo que tu seas.

Las contraseñas y las preguntas de seguridad son dos factores de autenticación que están en el grupo de "algo que tu sepas". Dado que tu podrías saber tu contraseña o la respuesta a un set específico de preguntas de seguridad, los sistemas utilizan estas asunciones para dar acceso.

Otro tipo común de factor de autenticación utiliza algo que yo tengo. Los dispositivos físicos como los tokens de seguridad USB o teléfono están en este grupo.

### Ejemplo

Cuando accedo a un sistema, se me envía un One Time Pin (OTP) vía SMS o por una app, esto verifica la seguridad porque ella misma está en mi dispositivo.

El último tipo de factor de seguridad utiliza lo que yo soy. Los mecanismos de autenticación biométrica están en esta categoría. Dado que algunos rasgos físicos son únicos, verificar a los individuos usando estos factores son formas seguras de mecanismos de autenticación.

## ¿Qué es Autorización (Auth) ?

Es el proceso de seguridad que determina el nivel de acceso de un usuario o un servicio. En tecnología, usamos autorización para para darle a los usuarios o los servicios permisos para acceder a cierta información o ejecutar una acción en particular.

### Ejemplo

Si volvemos al ejemplo de la cafetería, Ana y Juan tienen diferentes roles en el negocio. Como Juan es el barista, él solo podría colocar y ver órdenes. Ana, por otra parte, en su rol de manager del negocio, podría tener acceso al total de ventas realizadas diariamente. Dado que Ana y Juan tiene diferentes trabajos en la cafetería, el sistema usaría su identidad verificada para proveer a cada uno de los usuarios permisos individuales. Es vital notar la diferencia entre autorización y autenticación. La autenticación verifica el usuario (Ana) antes de darle acceso, y la autorización determina las cosas que pueden hacer una vez que el sistema les haya otorgado acceso (podría ser ver la información de las ventas).
