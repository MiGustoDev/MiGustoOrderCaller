<div align="center">

  <img src="public/Logo%20Mi%20Gusto%202025.png" alt="Mi Gusto Logo" width="180" />

  # 📣 Mi Gusto — Llamador de Pedidos

  **Sistema táctil y display inteligente de gestión de pedidos 100% offline**

  [![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev/)
  [![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
  [![Vite](https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white)](https://vitejs.dev/)
  [![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
  [![Offline Ready](https://img.shields.io/badge/Offline-100%25-22c55e?style=for-the-badge&logo=pwa&logoColor=white)](#)

</div>

---

### 💡 Sobre el Proyecto

**Mi Gusto — Llamador de Pedidos** es una solución web de alto rendimiento, diseñada para operar en **entornos de despacho dinámicos** donde la velocidad, la claridad visual y la autonomía de conexión son críticas.

Diseñado específicamente para **puntos de venta, food trucks, eventos multitudinarios y ferias gastronómicas**, permite sincronizar en tiempo real el armado de órdenes con la pantalla de llamado para los clientes, sin depender de servidores externos ni conexión a Internet.

---

## 🖼️ Vistas del Sistema

<div align="center">

<table align="center" style="border-collapse: collapse; border: none; width: 100%;">
  <tr>
    <td align="center" width="50%" style="border: none; padding: 10px;">
      <img src="public/assets/Contador.png" alt="Vista Contador - Panel Touch" width="100%" style="border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.15);" />
      <br />
      <sub style="font-size: 13px;"><b>🧮 Panel Contador — Control Táctil</b></sub>
    </td>
    <td align="center" width="50%" style="border: none; padding: 10px;">
      <img src="public/assets/Llamador.png" alt="Vista Llamador - Display TV Vertical" width="100%" style="border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.15);" />
      <br />
      <sub style="font-size: 13px;"><b>📺 Vista Llamador — Display de Turnos</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%" style="border: none; padding: 10px;">
      <img src="public/assets/Contador-Interactive.png" alt="Gestión de Estados" width="100%" style="border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.15);" />
      <br />
      <sub style="font-size: 13px;"><b>⚡ Gestión en Tiempo Real</b></sub>
    </td>
    <td align="center" width="50%" style="border: none; padding: 10px;">
      <img src="public/assets/Llamador-TV.png" alt="Visualización TV" width="100%" style="border-radius: 12px; box-shadow: 0 4px 20px rgba(0,0,0,0.15);" />
      <br />
      <sub style="font-size: 13px;"><b>🎯 Pantalla de Retiro Optimizada</b></sub>
    </td>
  </tr>
</table>

</div>

---

## ✨ Características Principales

- ⚡ **100% Offline & Resiliente**  
  Sin dependencia de APIs externas o servidores cloud. Persistencia inmediata mediante `localStorage` que garantiza cero pérdida de datos ante reinicios.

- 📱 **Interfaz Táctil Ergonométrica (Vista Contador)**  
  Controles oversized (+1, -1, Enviar) diseñados para operarios en cocinas o mostradores táctiles de ritmo rápido.

- 📺 **Display de Gran Formato (Vista Llamador)**  
  Diseño adaptativo de alto contraste pensado para televisores de 55"+ verticales (1080x1920) y pantallas de despacho visibles a distancia.

- 🔄 **Flujo de Trabajo Dinámico en 2 Etapas**  
  - **En Preparación**: Los pedidos recién emitidos se posicionan en el sector superior.
  - **A Retirar**: Transición con un tap para alertar al cliente en la zona de entrega.

- 🎯 **Sincronización Multiventana Instantánea**  
  Escucha activa de eventos de almacenamiento (`storage event`) para actualizar ambas pantallas simultáneamente en milisegundos.

---

## 🛠️ Tecnologías Clave

<div align="center">

| Tecnología | Rol en el Sistema | Beneficio Clave |
| :--- | :--- | :--- |
| **React 18** | UI Framework | Renderizado reactivo y componentes modulares |
| **TypeScript** | Lenguaje | Tipado estricto para estados de pedidos y eventos |
| **Tailwind CSS** | Estilos | Diseño responsivo con paleta cromática de alta visibilidad |
| **Vite** | Bundler & Architecture | Multi-entry build optimizado para distros offline |
| **Lucide Icons** | Iconografía | Simbología limpia e intuitiva |

</div>

---

## 🎯 Casos de Uso Ideal

- 🍔 **Food Trucks & Stand Gastronómicos**
- 🍕 **Locales de Comida Rápida & Delivery**
- 🎪 **Ferias, Festivales & Eventos Masivos**
- 🛍️ **Puntos de Retiro de Mercadería & Takeaway**

---

## 👥 Desarrolladores

<div align="center">

| Desarrollador | Enlaces |
| :--- | :--- |
| **Facundo Carrizo** | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/Facu14carrizo) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/facu14carrizo/) |
| **Ramiro Lacci** | [![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](https://github.com/ramirolacci) [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ramiro-lacci/) |

</div>

<br />

<div align="center">
  <sub>Desarrollado con ❤️ para el ecosistema <b>Mi Gusto</b></sub>
</div>

