Este es un template base para proyectos en React que incluye todo lo necesario para comenzar con una interfaz moderna, rutas definidas y componentes reutilizables.

🚀 Características incluidas
✅ React y React DOM configurados

🎨 ShadCN/UI instalado y listo para usar (@shadcn/ui)

📁 Estructura de carpetas organizada (components, pages, routes)

🧭 Una ruta de ejemplo ya definida

🧩 Dashboard base con diseño limpio y responsivo

🌙 Soporte para modo oscuro

##& 🛠️ Instrucciones para usar este template

1. Crear una nueva carpeta y clona solo "template-react" del repositorio
```bash
git init
git remote add origin https://github.com/Laime27/templates.git
git config core.sparseCheckout true
git sparse-checkout init
git sparse-checkout set template-react
git pull origin main
```
3. Mover el contenido de template-react a la raíz
```bash
xcopy template-react\* . /E /H /K
```
4. Eliminar la carpeta template-react
```bash
rmdir /s /q template-react
```
o con 
```bash
rm -r -fo template-react
```
5. Cambiar el "name" en package.json y package-lock.json por el nombre del nuevo proyecto

6. Instalar dependencias
```bash
npm install
```

