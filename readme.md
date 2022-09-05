# Autenticación vs Autorización

Autenticación y autorización son procesos vitales de seguridad de información los cuales son usados para proteger sistemas y datos.

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

### Tipos comunes de Autorización

Los sistemas de autorización existen de diferentes formas en un ambiente de tecnología. Por ejemplo, el mecanismo Acces Control Lists (ACLs) determina cuales usuarios o servicios pueden acceder a entorno digital en particular. Se logra este control de acceso al hacer cumplir las reglas de permitir o denegar el permiso según el nivel de autorización del usuario. Es común que en cualquier sistema existan usuarios generales y super usuarios o administradores. Si un usuario standard quiere hacer cambios que afecten la seguridad, un ACL podría denegarle la posibilidad de completar esta tarea. Por otra parte, los administradores tienen la autorización de hacer ajustes en la seguridad, caso en el que el ACL les dejaría hacerlo.

Otro tipo común de autorización es el que se refiere al acceso de información.

### Ejemplo

En cualquier ambiente de negocios, tenemos comunmente información con diferente nivel de sensibilidad. Podemos tener información pública la cual se puede encontrar en el sitio web de la compañía. La información interna es accesible solamente por los empleados. La información confidencial puede estar al alcance de solamente un par de individuos. En este ejemplo, la autorización determina los usuarios que pueden acceder a información de distintos tipos.

## La diferencia entre Autenticación y Autorización

Autenticación y Autorización puede sonar parecidos, pero no lo son. Como lo mencionamos anteriormente, uno de estos procesos es el encargado de verificar la identidad de un usuario o servicio antes de proveerles acceso, mientras que el otro determina lo que pueden hacer una vez cuenten con el acceso respectivo.

### Ejemplo

Digamos que yo decido ir a visitar a un amigo a su casa. Cuando llego, yo toco la puerta y mi amigo la abre. Él me reconoce (autenticación) y me saluda. Una vez que mi amigo me ha autenticado, se sentirá cómodo al dejarme entrar a su casa. Basado en mi relación con él, hay algunas cosas que puede hacer y otras que no (autorización). Por ejemplo, puedo entrar al área de la cocina, pero no puedo ir a su oficina privada. En otras palabras, tengo la autorización de entrar a la cocina, pero el acceso a la oficina privada está prohibido.

## ¿Cuáles son las similitudes entre Autorización y Autenticación?

Estos dos conceptos son similares en que ambos son parte del subyacente proceso de proveer acceso. Consecuentemente, son confundidos en la seguridad de la información ya que comparten la abreviación "auth". Autenticación y Autorización también son similares en la forma en la que ambos aprovechan la identidad.

## Ejemplo

Uno verifica la identidad antes de dar acceso, mientras que el otro usa esta identidad verificada para controlar el acceso.

## Autenticación y Autorización en Cloud Computing

La seguridad es vital en cualquier solución de cloud computing. Dado que estos servicios proporcionan un modelo de acceso compartido en el que todo corre en una misma plataforma, necesitan separar y proteger los sistemas de los usuarios y su información. Los servicios de la nube usa autenticación y autorización para conseguir estas metas de seguridad. De hecho, las plataformas de cloud computing no podrían proporcionar economías de escala a través de su modelo de recursos compartidos sin autenticación y autorización.

## ¿Qué viene primero, Autenticación o Autorización?

Tanto autenticación como autorización radican en la identidad. Dado que no puedo autorizar a un usuario o servicio antes de identificarlo, la autenticación siempre está antes de la autorización.

### Ejemplo

Como lo mencionamos anteriormente, los baristas solo pueden crear y ver ordenes, mientras que los managers también puede acceder a las información de ventas diarias. Si el sistema POS no puede identificar cuales usuarios están accediendo al sistema, tampoco puede proveer del correcto nivel de acceso. La autenticación provee la identidad verificada que la autorización necesita para controlar el acceso. Cuando Juan o Ana entrar al sistema, la aplicación sabe quien se ha entrado y también sabe el role que debería de asignar según la identidad.
