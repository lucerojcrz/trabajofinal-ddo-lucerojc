# UML (Lenguaje de Modelado Unificado)

El UML es un lenguaje que se usa para **representar visualmente** cómo va a funcionar un sistema antes de ponerse a programar.
Nos permite pensar y **planificar el diseño del software** antes de empezar a escribir el código. En definitiva, es como hacer el “boceto” de una aplicación antes de construirla. Te ahorra problemas y ayuda a que todo el equipo esté en sintonía sobre qué se está haciendo.

---

## ¿Para qué podemos usarlo?

- Nos permite **entender mejor** cómo se va a comportar nuestro sistema.
- Podemos **comunicar ideas** entre el equipo de trabajo sin necesidad de transmitirlo en código.
- Es perfecto para **detectar errores o mejoras** a tener en cuenta antes de desarrollar.

---

## Tipos de diagramas UML:

### 1. Diagrama de Clases

Este diagrama muestra las **clases del sistema**, sus atributos, métodos y cómo se relacionan entre sí.

Por ejemplo:
- Clase `Cliente`
- Atributos: nombre, apellido, edad, telefono, mail.
- Métodos: registrarse(), modificarDatos()

---

### 2. Diagrama de Casos de Uso

Este tipo de diagrama muestra **qué puede hacer un usuario** en el sistema.  
Se enfoca en los `actores` (usuarios) y las funcionalidades que usan.

Por ejemplo:
- Actor: Cliente
- Casos de uso: Consultar rutina, modificar datos, ver estadísticas.

---

### 3. Diagrama de Secuencia

Este tipo muestra cómo **se comunican los objetos entre sí a lo largo del tiempo**.  
Es ideal para ver el paso a paso de una acción.

Por ejemplo:
- Usuario llama a login()
- El sistema valida los datos ingresados por el usuario.
- Devuelve acceso permitido, denegado o no existente, dependiendo el caso.

---

### Diagrama de Actividad

Es último muestra **el flujo de acciones** o decisiones dentro de un proceso.  
Es como un “flujograma” que indica qué pasa primero, qué pasa después y qué caminos puede tomar.
