# 🚀 Instrucciones para correr el proyecto localmente

Este repositorio contiene el prototipo de una interfaz para trámites tributarios en línea, usando Tailwind CSS con el CLI.

---

## 📁 1. Clona el repositorio

```bash
git clone https://github.com/AleNaranjo-Git/ich_prototype.git
cd ich_prototype
```

---

## 📦 2. Instala las dependencias

Este paso descargará `tailwindcss`, `@tailwindcss/cli` y cualquier otro paquete definido en `package.json`:

```bash
npm install
```

---

## 🛠️ 3. Compila el CSS con Tailwind CLI

Este comando generará el archivo `output.css` a partir del `input.css`:

```bash
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

> Deja este comando corriendo mientras trabajas. Deténlo con `Ctrl + C` cuando termines.

---

## 🌐 4. Abre el prototipo

Puedes abrir el archivo `src/index.html` directamente en el navegador (doble clic o click derecho > "Abrir con...").

---

## 📁 Estructura esperada

```
tu-proyecto/
├── node_modules/          ← generado por `npm install` (no está en Git)
├── package.json
├── package-lock.json
├── src/
│   ├── input.css
│   ├── output.css         ← generado por el CLI
│   └── index.html
```

---


## 🛑 Cómo detener el proceso de Tailwind

Presiona `Ctrl + C` en la terminal donde está corriendo el `--watch`.

---
