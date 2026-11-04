# 💼 Moneta — *tu bolsillo inteligente*

> 💙 Plataforma de finanzas personales para que **ningún peso** quede por fuera: ni el grande, ni el hormiga. 🐜

![Estado](https://img.shields.io/badge/estado-en%20desarrollo-blue)
![Tipo](https://img.shields.io/badge/proyecto-acad%C3%A9mico-green)
![Enfoque](https://img.shields.io/badge/dise%C3%B1o-mobile--first-1f3a68)

---

## 📚 Contexto académico

Proyecto integrador de las materias:

- 🧭 **Metodologías**
- 💻 **Introducción a la Programación**
- 🧠 **Lógica**

---

## 🎯 ¿De qué trata Moneta?

Moneta es una plataforma donde el usuario registra **absolutamente todos sus gastos** de forma manual, para tener una visión real y completa de su dinero. A partir de esa información, la app le muestra cómo van sus finanzas del mes, le ayuda a ahorrar y le da recomendaciones personalizadas.

---

## ✨ Funcionalidades principales

| | Funcionalidad | Descripción |
|---|---|---|
| 📝 | **Registro manual de gastos** | Ingreso de cada gasto, sin que se escape ninguno |
| 🧾 | **Comprobantes y recibos** | Carga de imágenes de transferencias, tirillas y recibos de compra |
| 🐜 | **Gastos hormiga** | Seguimiento de esos pequeños gastos que pasan desapercibidos |
| 📊 | **Resumen mensual** | Estado de las finanzas del mes: saldo disponible, gasto del día, tendencia semanal |
| 🐷 | **Bolsillo inteligente** | Espacio para ahorrar, incluyendo el ahorro para gastos fijos |
| 💡 | **Tips y recomendaciones** | Sugerencias de en qué usar el dinero que va "sobrando" |
| 🚨 | **Alertas** | Aviso cuando la cuenta se acerca a **cero**, entre otras alertas |

---

## 🧩 Componentes del proyecto

### 🌐 1. Parte pública — Landing page
- 📖 Explica de qué trata la plataforma.
- 🖊️ Incluye el **formulario de inscripción** de usuarios.
- 📧 Al inscribirse, el usuario recibe un **correo de bienvenida** y pasa a la app móvil.

### 📱 2. Parte privada — App móvil
- 🔐 El usuario termina de crear su cuenta con su **propia contraseña** y accede a la plataforma.
- 🏠 Acceso a todas las herramientas de control de gastos y ahorro.

---

## 🔄 Flujo de acceso

```
📧 Ingresa su correo
      │
      ├── ❌ Correo NO registrado ──► 💬 Mensaje + botón ──► 🌐 Formulario de la landing
      │                                                        │
      │                                                        ▼
      │                                               📩 Correo de bienvenida
      │
      └── ✅ Correo registrado (primer ingreso)
                  │
                  ▼
        🔑 Modal: crear contraseña
        (mín. 8 caracteres, mayúsculas, minúsculas
         y caracteres especiales + confirmación)
                  │
                  ▼
        🔢 Código alfanumérico de 6 dígitos (token por correo)
                  │
                  ▼
        📝 Formulario de primer ingreso
                  │
                  ▼
        🏠 Home de la app
```

---

## 📲 Vistas de la app

1. 🔐 **Inicio de sesión** — campo "ingresa tu correo".
2. 🔑 **Modal de creación de contraseña** — con validaciones y visualización de la contraseña 👁️.
3. 🔢 **Verificación con código** de 6 dígitos.
4. 🚫 **Correo no registrado** — redirige al formulario de la landing.
5. 📝 **Formulario de primer ingreso** — cuentas, bancos, gastos, estado civil, cantidad de hijos, en qué suele gastar, gastos fijos y otros datos útiles.
6. 🏠 **Home** — saldo disponible del mes, gasto del día, tendencia semanal y ahorro para gastos fijos.

**Barra de navegación inferior:**

| 🏠 Inicio | 💸 Movimientos | 🐷 Bolsillo inteligente | 🐜 Gastos hormiga |
|---|---|---|---|

> 🍔 En móvil, las opciones principales van abajo y las demás en un **menú hamburguesa**.

---

## 🎨 Identidad visual

- 🏷️ **Marca:** Moneta
- 💬 **Slogan:** *tu bolsillo inteligente*
- 👛 **Logo:** billetera con una "M" y un billete verde asomando
- 🎨 **Colores:** azul marino 🔵 y verde 🟢, con tonos de azul en tendencia
- ✨ **Estilo:** diseño muy limpio y moderno
- 🧩 **Íconos de apoyo:** 🎛️ Controla · 🐷 Ahorra · 🗂️ Organiza · 📈 Invierte

---

## 🛠️ Tecnologías

- 🧱 **HTML5**
- 🎨 **CSS3** (flex, pseudoelementos, media queries, hovers)
- 💨 **Tailwind CSS** (en las vistas que lo requieren)
- 📐 **Diseño responsivo, mobile-first**

---

## 🗺️ Avance del proyecto

- [x] 🚩 **Sprint 1:** diseño de la landing page y formulario de registro
- [x] 🌐 Landing page terminada (parte pública)
- [x] 🎨 Mockups del flujo de acceso (login, contraseña, código, no registrado)
- [x] 🖼️ Prototipo interactivo del flujo de acceso
- [x] 📝 Vista del formulario de primer ingreso
- [x] 🏠 Vista del home
- [ ] 💸 Vista de Movimientos
- [ ] 🐷 Vista del Bolsillo inteligente
- [ ] 🐜 Vista de Gastos hormiga
- [ ] 🚨 Alertas y recomendaciones

---

## 👥 Equipo

| 👤 Integrante | 🎓 Rol |
|---|---|
| Luisa | _por completar_ |
| _por completar_ | _por completar_ |

🏫 **Institución:** _por completar_
👩‍🏫 **Docente:** _por completar_

---

## 📄 Licencia

Proyecto con fines **académicos** 🎓.

---

<p align="center">💙 Hecho con dedicación por el equipo Moneta 💚</p>
