# 🌍 Hola Mundo Multilenguaje

## 📌 Descripción

Este proyecto reúne la clásica implementación de **"Hola mundo"** en múltiples lenguajes de programación.

Ideal para:

* Primeros pasos en programación
* Comparar sintaxis entre lenguajes
* Verificar instalaciones de compiladores e intérpretes

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

### 🔹 Rust 🦀

```rust
fn main() {
    println!("Hola Mundo");
}
```

#### ▶ Crear y ejecutar

```bash
cargo new holamundo_rust
cd holamundo_rust
cargo run
```

---

## 🧠 Explicación simple

Todos los programas hacen exactamente lo mismo:

👉 Mostrar el mensaje **"Hola mundo"**

Cada lenguaje tiene su estilo:

* **C++** → clásico y potente
* **Pascal** → académico y estructurado
* **Python** → minimalista
* **JavaScript** → omnipresente
* **Rust** → seguro y moderno

---

## 📁 Estructura del proyecto

```
.
├── holamundo.cpp
├── holamundo.pas
├── holamundo.py
├── holamundo.js
├── holamundo.html
├── holamundo_rust/
├── README.md
```

---

## 🎯 Objetivo del proyecto

* Aprender la base de cada lenguaje
* Comparar sintaxis
* Practicar compilación y ejecución

---

## ⚠️ Nota

No se incluyen archivos compilados (ejecutables, `.o`, etc.), ya que pueden generarse fácilmente a partir del código fuente.

---

## 🚀 Autor

Proyecto con fines educativos.


Proyecto creado con fines educativos.
