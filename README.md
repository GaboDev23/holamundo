# 🌍 Hola Mundo Multilenguaje

## 📌 Descripción

Este proyecto contiene la clásica implementación de **"Hola mundo"** en diferentes lenguajes de programación.

Es ideal para:

* Primeros pasos en programación
* Verificar instalación de compiladores
* Comparar sintaxis entre lenguajes

---

## 💻 Lenguajes incluidos

### 🔹 C++

```cpp
#include <iostream>

int main() {
    std::cout << "Hola mundo\n";
    return 0;
}
```

#### ▶ Compilación y ejecución

```bash
g++ holamundo.cpp -o holamundo
./holamundo
```

---

### 🔹 Pascal

```pascal
program holamundo;
begin
    writeLn('Hola mundo')
end.
```

#### ▶ Compilación y ejecución

```bash
fpc holamundo.pas
./holamundo
```

---

## 🧠 Explicación simple

Ambos programas hacen exactamente lo mismo:

👉 Mostrar el texto **"Hola mundo"** en la consola.

Pero cada lenguaje tiene su propio estilo:

* **C++** usa `std::cout`
* **Pascal** usa `writeLn`

Es como decir lo mismo en distintos idiomas, pero con acento diferente.

---

## 🎯 Objetivo del proyecto

* Aprender la estructura básica de programas
* Comparar sintaxis entre lenguajes
* Practicar compilación desde la terminal

---

## 📁 Estructura del proyecto

```
.
├── holamundo.cpp
├── holamundo.pas
├── README.md
```

---

## ⚠️ Nota

Los archivos compilados (`.o`, ejecutables, etc.) no se incluyen en el repositorio, ya que pueden generarse fácilmente a partir del código fuente.

---

## 🚀 Autor

Proyecto creado con fines educativos.
