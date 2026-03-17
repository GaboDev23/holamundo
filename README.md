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

### 🔹 Python

```python
print('Hola mundo')
```

#### ▶ Ejecución

```bash
python3 holamundo.py
```

---

### 🔹 JavaScript

```javascript
console.log("Hola Mundo");
```

#### ▶ Ejecución (Node.js)

```bash
node holamundo.js
```

#### 🌐 Ejecución en navegador

Archivo `holamundo.html`:

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Hola Mundo</title>
</head>
<body>
    <script src="holamundo.js"></script>
</body>
</html>
```

---

## 🧠 Explicación simple

Todos los programas hacen lo mismo:

👉 Mostrar el texto **"Hola mundo"** en la consola.

Pero cada lenguaje tiene su estilo:

* **C++** → estructurado y potente
* **Pascal** → clásico y académico
* **Python** → simple y directo
* **JavaScript** → flexible y omnipresente (navegador + servidor)

---

## 📁 Estructura del proyecto

```
.
├── holamundo.cpp
├── holamundo.pas
├── holamundo.py
├── holamundo.js
├── holamundo.html
├── README.md
```

---

## 🎯 Objetivo del proyecto

* Aprender la estructura básica de programas
* Comparar sintaxis entre lenguajes
* Practicar compilación y ejecución

---

## ⚠️ Nota

Los archivos compilados (`.o`, ejecutables, etc.) no se incluyen en el repositorio, ya que pueden generarse fácilmente a partir del código fuente.

---

## 🚀 Autor

Proyecto creado con fines educativos.

Proyecto creado con fines educativos.
