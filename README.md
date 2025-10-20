# 🎧 Radio Alura

### *A Java Object-Oriented Programming Challenge Project*

---

## 📖 Description

**Radio Alura** is a console-based Java application developed as part of the course **“Java: Applying Object-Oriented Programming”** from **[Alura Latam](https://www.aluracursos.com/) and [Oracle Next Education (ONE)](https://www.oracle.com/mx/education/oracle-next-education/)**.

The project simulates a **digital audio platform**, where users can play songs and podcasts, track likes, views, and determine personalized classifications for their content.

This challenge was designed to **apply and consolidate the core principles of Object-Oriented Programming (OOP)** such as abstraction, inheritance, encapsulation, and polymorphism.

---

## 🧠 Main Concepts Practiced

Throughout the project, the following Java and OOP concepts were applied:

* 🧱 **Abstraction:** Creating a generic `Audio` class that represents shared properties of all audio types.
* 🔁 **Inheritance:** Defining subclasses `Cancion` and `Podcast` that extend `Audio` and inherit its behavior.
* 🔒 **Encapsulation:** Using private attributes and public getters/setters to protect and control data access.
* 🎭 **Polymorphism:** Overriding methods like `getClasificacion()` to define specific behavior for each subclass.
* ⚙️ **Code Reusability:** Building modular, maintainable code by following clean programming practices.
* ⭐ **Custom Logic:** Implementing a favorite filter system that selects top-rated audio content.

---

## 🧩 Project Structure

```
src/
└── com/aluracursos/radioalura/
    ├── modelo/
    │   ├── Audio.java
    │   ├── Cancion.java
    │   ├── Podcast.java
    │   └── MisFavoritos.java
    └── principal/
        └── Principal.java
```

### **Class Overview**

* **Audio** → Superclass containing shared attributes and methods (title, duration, likes, plays, classification).
* **Cancion** → Subclass that represents a song; its classification depends on the number of likes.
* **Podcast** → Subclass representing a podcast; its classification depends on total plays.
* **MisFavoritos** → Helper class that filters and lists audios with high classification values.
* **Principal** → Main class used to instantiate and test different objects in the application.

---

## ⚙️ How It Works

1. The user can instantiate objects of type `Cancion` or `Podcast`.
2. Each object allows actions such as:

   * Adding likes (`meGusta()`)
   * Increasing play count (`reproduce()`)
3. Based on their metrics, each audio is **classified** differently:

   * Songs → Based on total likes.
   * Podcasts → Based on total plays.
4. The `MisFavoritos` class filters the best-rated audios and displays user-friendly messages.

---

## 🚀 How to Run the Project

### **Requirements**

* Java Development Kit (JDK) 17 or later
* An IDE such as IntelliJ IDEA, Eclipse, or VS Code with Java extensions

### **Steps**

1. Clone this repository:

   ```bash
   https://github.com/GuillenA7/audio-player-oop-java.git
   ```
2. Open the project in your IDE.
3. Navigate to the class `Principal.java`.
4. Run the program — you’ll see the output in the console simulating plays, likes, and favorites.

---

## 🧮 Example Output

```
Total reproducciones: 5000  
Total me gusta: 100  

Café.Tech is one of the favorites of the moment ☕  
Forever is also one of the favorites 💿
```

---

## 🧑‍💻 Technologies Used

* **Language:** Java
* **Paradigm:** Object-Oriented Programming (OOP)
* **Tools:** IntelliJ IDEA
* **Version Control:** Git & GitHub

---

## 🧩 Course Information

This project was created as part of the course:

**Java: Aplicando la Orientación a Objetos**

📚 *by Alura Latam + Oracle Next Education (ONE)*

👩‍🏫 *Instructor: Génesys Rondón*

🕒 Duration: 10 hours

---

## 🏆 Learning Outcomes

After completing this project, I reinforced my ability to:

* Design maintainable and modular Java applications.
* Implement inheritance and polymorphism effectively.
* Apply encapsulation for secure data management.
* Write cleaner and more reusable object-oriented code.

---

## 🌐 Connect

📫 **Author:** [Jose Adrian Guillen Lamas]

💼 [LinkedIn Profile](https://www.linkedin.com/in/jose-adrian-guillen-lamas-3b3b5135b/)

💻 [GitHub Profile](https://github.com/GuillenA7)

---

> 🎉 *This project is part of my journey through the Oracle Next Education program — continuing to grow as a back-end developer specialized in Java.*
