# 🚀 Aplicación React de Autenticación con Supabase

Una aplicación React simple con interfaces de autenticación (Inicio de Sesión, Registro y Página Principal) conectada a **Supabase** para la gestión de usuarios.

## ✨ Características Principales

- Página de acceso con autenticación mediante Supabase  
- Página de registro para nuevos usuarios  
- Página principal con funcionalidad de cierre de sesión  
- Navegación entre diferentes vistas  

## ✅ Requisitos Previos

- Node.js (versión 14 o superior)  
- npm o yarn  
- Cuenta y proyecto en Supabase  

## ⚙️ Instalación y Configuración

### 1. Clonar el repositorio

```bash
git clone https://tu_enlace_del_repositorio.git
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Configurar credenciales de Supabase

- Crear un archivo `.env.local` en la raíz del proyecto  
- Agregar las siguientes variables:

```env
VITE_SUPABASE_URL=https://id_proyecto.supabase.co
VITE_SUPABASE_ANON_KEY=tu_clave_anonima_publica
```

> Asegúrate de reemplazar con tus credenciales reales de Supabase.

### 4. Iniciar el servidor de desarrollo

```bash
npm run dev
```

### 5. Abrir en el navegador

```
http://localhost:5173
```

## 🧰 Tecnologías Implementadas

- React  
- TypeScript  
- React Router (v6)  
- Vite  
- Supabase (Autenticación y Backend)  

## 📁 Estructura del Proyecto

```
src/
  ├── lib/
  │   └── supabaseClient.ts       // Cliente de Supabase
  ├── pages/
  │   ├── Home.tsx                // Página principal
  │   ├── Login.tsx               // Página de acceso
  │   └── Signup.tsx              // Página de registro
  ├── App.tsx                     // Componente principal
  ├── App.css                     // Estilos generales
  ├── config.ts                   // Configuración de entorno
  ├── main.tsx                    // Punto de entrada
  └── index.css                   // Estilos base
```

## ⚠️ Consideraciones Importantes

- Es necesario crear tu propio proyecto en Supabase y configurar las variables de entorno  
- Para despliegues en producción, **protege adecuadamente tus variables de entorno**  

## Fotos de Funcionamiento:

![Screenshot 2025-06-12 111824](https://github.com/user-attachments/assets/fe497c21-33f4-4da8-b2ad-e7e7c25299f7)


![Screenshot 2025-06-12 111710](https://github.com/user-attachments/assets/0e0d8036-3b7a-4294-b899-984d2ca03cde)


![Screenshot 2025-06-12 111751](https://github.com/user-attachments/assets/60fa8b89-8be2-40ac-ae9e-e4ba50aba30d)

