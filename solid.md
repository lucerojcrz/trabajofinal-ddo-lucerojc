# Principios SOLID

Los principios SOLID son **cinco reglas básicas** que ayudan a que el diseño del software sea más organizado, mantenible y flexible.  
Cada letra representa un principio distinto. Estos principios se usan en la programación orientada a objetos y son clave para escribir buen código.

---

## 🔠 ¿Qué significa SOLID?

### 1) **S** – Single Responsibility Principle (Responsabilidad Única)

Una clase debe tener **una sola razón para cambiar**.  
O sea, que haga **una sola cosa** bien definida.  
Por ejemplo: una clase que solo se encargue de guardar usuarios, no de imprimir facturas ni de mandar mails.

---

### 2) **O** – Open/Closed Principle (Abierta/Cerrada)

Una clase debe estar **abierta para extenderse**, pero **cerrada para modificarse**.  
Significa que podés agregar funcionalidades sin tocar el código original.  
Por ejemplo: herencia o polimorfismo para agregar nuevos comportamientos.

---

### 3) **L** – Liskov Substitution Principle

Una subclase debería poder **reemplazar a su clase padre sin romper el sistema**.  
Por ejemplo: si `Perro` hereda de `Animal`, debería poder usarse como un `Animal` sin que se rompa nada.

---

### 4) **I** – Interface Segregation Principle

Es mejor tener **muchas interfaces chiquitas y específicas** que una sola gigante.  
Así las clases implementan **solo lo que necesitan**.

---

### 5) **D** – Dependency Inversion Principle

Las clases deben depender de **abstracciones** (interfaces), **no de clases concretas**.  
Esto hace que el código sea más fácil de testear y cambiar.

---

## ¿Qué permite el uso de estos principios?

- Mejoran el diseño del software.
- Hacen el código más limpio y fácil de mantener.
- Evitan errores cuando el sistema crece o cambia.