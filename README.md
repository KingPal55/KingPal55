# Java 23 Demo – Fall 2025 Presentation

This repository contains runnable examples showcasing key features introduced in **Java 23**, released in September 2024. These examples support a 10–15 minute technical presentation.

## 🔑 Featured JEPs

### 1. Pattern Matching for Primitives (JEP 455 – Preview)
Allows `instanceof` and `switch` to work directly with primitive types.

### 2. Implicit Classes and Instance Main Methods (JEP 477 – Third Preview)
Simplifies small programs by removing the need for `public class` and `static void main`.

### 3. Markdown in Javadoc (JEP 467)
Supports Markdown formatting in documentation comments.

### 4. Stream Gatherers (JEP 473 – Second Preview)
Enhances the Stream API with more powerful aggregation patterns.

---

## 🧪 How to Run
Use Java 23 with preview features enabled:

```bash
javac --enable-preview --release 23 Main.java
java --enable-preview Main
