# Café Central - Aplicación Parcial (Vue 3 + Bootstrap 5.3)

## Descripción
Aplicación de ejemplo para el segundo parcial: **Cafetería "Café Central"**. Proyecto educativo que demuestra:
- Modularización con componentes.
- Rutas con vue-router.
- Consumo de API externa para gestión de productos (FakeStore API).
- Login simulado desde un archivo JSON local.

## Estructura del proyecto
- `src/components/` → Navbar, Sidebar, Footer, ProductCard.
- `src/views/` → LoginView, DashboardView, ProductView.
- `src/services/` → `apiService.js` (peticiones HTTP), `authService.js` (login simulado).
- `src/data/usuarios.json` → Usuarios de prueba.

## Login
- Validación desde `usuarios.json`.
- Usuarios de prueba:
  - `admin` / `admin123`
  - `estudiante` / `parcial2025`
- **Importante:** validación educativa, no es autenticación real.

## Gestión de productos
- Endpoints usados (FakeStore API):
  - `GET https://fakestoreapi.com/products`
  - `POST https://fakestoreapi.com/products` 
  - `PUT https://fakestoreapi.com/products/:id`
  - `DELETE https://fakestoreapi.com/products/:id`

