# Proyecto - V1.2

## 🔧 Comando para iniciar el Servidor Local

```bash
uvicorn main:app --reload --host 127.0.0.1 --port 8000
```
## ✅ Estado Actual del Proyecto
La interfaz gráfica ya está funcional junto con la base de datos SQL.
Actualmente, el sistema cuenta con 4 funciones principales:
 
 
## 📦 Insumos

Esta función permite añadir los insumos a nuestra base de datos SQL con datos específicos como:

- Nombre del Insumo
- Descripción
- Cantidad Inicial
- Costo Unitario

## 🛒 Mercado

Esta Función clave para visualizar una estimación de precios de los productos.

Actualmente funciona de forma local, pero en futuras versiones estará online. Permite publicar precios de insumos. Incluye un sistema de filtros por categoría para buscar fácilmente.

## 🧮 Calculadora

Función básica en desarrollo, incluye dos herramientas:

- Cálculo del IVA
- Cálculo del precio final con margen de ganancia ingresado por el usuario.

## 👥 Equipo

#### Actualmente obsoleta.
Se planea reactivar esta sección en una futura versión con un sistema de login.
Permitirá:

- Crear equipos

- Unirse a un equipo

Esto facilitará la colaboración entre usuarios (dueños de negocios o microempresas).
