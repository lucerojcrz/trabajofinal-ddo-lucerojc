# Diagrama de Secuencia

El diagrama de secuencia sirve para **mostrar cómo se comunican los objetos entre sí a lo largo del tiempo**.  
Es ideal para ver el paso a paso de una acción específica, como si fueran mensajes que se mandan entre objetos.

---

## Ulitidad

- Se utlitiza para entender **qué objetos participan** en una acción y en qué orden lo hacen.
- También permite ver cómo se da **la interacción entre clases o módulos**.
- Para representar procesos **concretos** como: login, alta de usuario, compra, etc.

---

## ¿Qué contiene?

- **Objetos o clases:** son los que intervienen en el proceso (usuario, sistema, base de datos, etc).
- **Líneas de vida:** representan el tiempo en que cada objeto está activo.
- **Mensajes:** son flechas con texto que muestran qué le dice un objeto a otro (por ejemplo: `validarDatos()`)
- **Retornos:** son las respuestas a esos mensajes, con datos, confirmaciones o negaciones.

---

## Ejemplo: ingreso de usuario en el sistema del gimnasio

1. El **usuario** ingresa usuario y contraseña.
2. El sistema le manda esos datos a la clase **Autenticador**.
3. El autenticador los valida con la **Base de Datos**.
4. Si los datos son correctos, se permite el acceso.
5. El sistema responde al usuario con "Bienvenido" o "Acceso denegado".