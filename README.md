
# 🛒 MiniMarket VR

> **Juego de cajero de supermercado en Realidad Virtual** para Meta Quest 2/3/Pro y PC VR.  
> Escanea, cobra, empaqueta y sobrevive al caos del turno en el minimarket más divertido.

---

## 🎮 Gameplay

| Característica | Descripción |
|---|---|
| **Puesto de caja interactivo** | Cinta transportadora, escáner láser, pantalla táctil, balanza, lector de tarjetas, cajón de efectivo |
| **Productos físicos** | Agarra con tus manos, pasa por el láser (*beep* + vibración), empaqueta con física real |
| **Métodos de pago** | Efectivo (cuenta billetes/monedas, da cambio) · Tarjeta (inserta, espera, *aprobado*) |
| **Clientes con personalidad** | Normal, Apurado, Gracioso, Quejumbroso, Despistado — cada uno con diálogos y comportamiento único |
| **Eventos de caos** | Código de barras roto · Botella rota (limpia con atomizador) · Cliente apurado · Producto caído (imán accesibilidad) |
| **Progresión** | Turnos de 5–10 min → Gana dinero + propinas → Compra mejoras (escáneres láser, música, skins, accesorios) |
| **Accesibilidad** | Imán para atraer objetos · Subtítulos flotantes · Confort VR (vignette, snap turn, teleport) · Jugable sentado |

---

## 🛠 Stack Técnico

| Tech | Versión / Detalle |
|---|---|
| **Unity** | 2022.3 LTS (URP) |
| **XR Interaction Toolkit** | 2.6.5 |
| **Meta XR Core SDK** | Latest (Oculus XR Plugin) |
| **Plataformas** | Meta Quest 2/3/Pro (Standalone) · PC VR (Link/AirLink/SteamVR) |
| **Lenguaje** | C# |
| **Render Pipeline** | Universal Render Pipeline (Single Pass Instanced) |
| **Input System** | Unity Input System + XRI Default Input Actions |

---

## 🚀 Quick Start

### Requisitos
- Unity **2022.3.x LTS** con módulo **Android Build Support** + NDK/SDK
- **Meta Quest** en modo desarrollador + USB Debugging (para build standalone)
 Opcional: Oculus PC App + Link/AirLink (para PC VR)

### Clonar y abrir
```bash
git clone https://github.com/ClutchDev23/MiniMarket-VR-Game.git
cd MiniMarket-VR-Game
# Abre con Unity Hub → Add project → selecciona esta carpeta
