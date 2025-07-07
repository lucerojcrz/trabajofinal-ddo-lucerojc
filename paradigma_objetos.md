# Paradigma de Objetos

La programación orientada a objetos es una forma de organizar el código que se basa en objetos.  
Un objeto tiene algunas características (atributos) y acciones (métodos). Su idea principal es representar cosas del mundo real en código.  
Esto hace que el programa sea muchísimo más fácil de entender y poder hacer modificaciones si así se quisiera.

---

## Utilidad

- Se utiliza para organizar mejor el código, como si fuera la vida real
- Podés tranquilamente modificar cosas sin romper todo lo demás

---

## ¿Qué es una clase?

No es algo real todavía, sino el diseño de cómo va a ser un objeto.

Por ejemplo: una clase `Persona` define que todas las personas tienen nombre, apellido, edad, peso, altura, etc.

---

## ¿Qué es un objeto?

Es algo real basado en esa clase.  
Por jemplo: si la clase es `Persona`, un objeto sería “Pedro Rodríguez, 27 años, 80 kilos, 1,80 cm, etc”.

---

## ¿Qué son los atributos?

Son las **características** del objeto.  
Por jemplo: nombre, apellido, nacionalidad, edad, peso, altura, etc.

---

## ¿Qué son los métodos?

Son las **acciones** que puede hacer el objeto.  
Por jemplo: caminar(), comer (), correr (), hablar(), dormir(), cantar (), etc.

---

## Los cuatro pilares de la Programación Orientada a Objetos

1. **Encapsulamiento:**  
   Proteger los datos del objeto. Solo se puede acceder desde ciertos métodos, para evitar errores. Atributos privados y métodos públicos, así lo trabajamos.

2. **Abstracción:**  
   Mostrar solo lo necesario. Lo que pasa "adentro" del objeto no importa, solo cómo lo usás.

3. **Herencia:**  
   Crear nuevas clases a partir de otras de forma que hereden algunas características de la clase padre o superclase. 
   Por ejemplo: la clase `Empleado` se hereda de la clase `Persona`, u otro ejemplo, la clase `Futbolista` se hereda de la clase `Deportista` .

4. **Polimorfismo:**  
   Permitir que una misma acción funcione distinto para cada objeto.  
   Por ejemplo: el método `hacerRuido` puede sonar distinto en diferentes objetos dependiento en qué animal se use.