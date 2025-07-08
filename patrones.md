# Patrones de Diseño

Los patrones de diseño son **soluciones probadas y estructuradas** a problemas comunes que aparecen al programar.  
Se usan en el diseño de software orientado a objetos para no tener que reinventar todo cada vez que armamos una aplicación.

---

## ¿Por qué son fundamentales?

- Porque **ahorran tiempo** al dar una solución clara a un problema conocido.
- Porque ayudan a **mantener el código organizado, escalable y reutilizable**.
- Porque son fáciles de entender por otros programadores.

---

## Patrón Singleton

Este patrón se usa cuando queremos que una **clase tenga una sola instancia en todo el programa**.  
Es como decir: “esta clase existe una sola vez, y se usa en todos lados igual”.

---

## ¿Qué problema resuelve?

Evita que se creen múltiples objetos de algo que **debe existir una sola vez**.  
Algunos ejemplos típicos:

- Conexión a una base de datos.
- Configuraciones globales.
- Un logger de errores.

---

## ¿Cómo funciona?

- La clase **tiene un constructor privado** (para que nadie la instancie desde afuera).
- Tiene un método estático que devuelve la única instancia.
- Si la instancia ya existe, la devuelve. Si no, la crea.