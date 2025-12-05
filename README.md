# DigitalCabinet

Organizá el stock de todos tus hogares, chateá con tu familia y controlá tus gastos mensuales desde un solo lugar.

---

## 🧾 Descripción

**DigitalCabinet** es una aplicación pensada para familias y hogares que quieren llevar un mejor control de:

- El **stock** de productos en casa (alacena, heladera, limpieza, etc.).
- Las **compras y gastos mensuales**, organizados por categoría.
- La **comunicación entre miembros del hogar** mediante un chat interno.
- Una **lista de deseos** para productos que todavía no se compraron, pero se quieren tener en cuenta.

Un mismo usuario puede tener **varios hogares**, y cada hogar cuenta con su propio stock, chat y configuración.

---

## ✨ Funcionalidades principales

### 👨‍👩‍👧‍👦 Múltiples hogares
- Un usuario puede crear y gestionar **más de un hogar** (por ejemplo: casa principal, casa de los padres, departamento, etc.).
- Cada hogar tiene:
  - Su **propio stock** de productos.
  - Su propio **chat familiar**.
  - Sus listas de productos y gastos separadas.

### 📦 Gestión de stock por hogar
- Alta, edición y eliminación de productos.
- Datos típicos de cada producto:
  - Nombre
  - Cantidad
  - Unidad (ej: unidades, kg, litros, etc.)
  - Categoría (ej: alimentos, limpieza, higiene, otros)
  - Precio (opcional, pero recomendado para el cálculo de gastos).
- Posibilidad de ver **qué hay en cada hogar** sin tener que estar físicamente ahí.

### 💬 Chat entre familiares
- Cada hogar tiene un **chat interno** donde los miembros pueden:
  - Coordinar compras.
  - Avisar cuando algo se está por acabar.
  - Dejar notas o recordatorios rápidos.

### ⭐ Lista de deseos
- Sección dedicada a la **lista de deseos** del hogar:
  - Productos que todavía no se compraron pero se quieren tener en cuenta.
  - Ideal para armar próximas compras o planificar grandes compras futuras.

### 💰 Gastos mensuales por categoría
- Al cargar el **precio** de los productos:
  - Se calcula el **gasto mensual estimado**.
  - Los gastos se agrupan por **categoría** (ej: alimentos, limpieza, higiene, otros).
- Permite tener una visión rápida de:
  - En qué categorías se gasta más.
  - Cómo se distribuye el presupuesto del hogar a lo largo del mes.

### 🗂️ Categorías de productos y gastos
- Los productos están organizados en **categorías**, lo que facilita:
  - Navegar el stock.
  - Analizar los gastos por tipo de producto.
- Las mismas categorías pueden usarse tanto para:
  - Clasificar productos.
  - Agrupar los gastos del mes.

---

## 🧱 Modelo conceptual (simplificado)

Entidades principales:

- **Usuario**
  - Puede pertenecer a uno o varios hogares.
- **Hogar**
  - Tiene stock, chat, lista de deseos y configuración propia.
- **Producto**
  - Pertenece a un hogar.
  - Tiene cantidad, categoría y, opcionalmente, precio.
- **Categoría**
  - Agrupa productos y gastos (ej: alimentos, limpieza).
- **Mensaje (Chat)**
  - Mensajes enviados entre miembros del hogar.
- **Elemento de lista de deseos**
  - Producto deseado, aún no comprado.
