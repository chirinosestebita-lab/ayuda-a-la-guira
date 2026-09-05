# 🛡️ Sistema de Control Logístico y Censo Integral — La Guaira

Aplicación web progresiva (PWA) de una sola página desarrollada para la gestión logística de emergencia, control de inventarios, despacho con firmas criptográficas (HMAC-SHA256) y censo poblacional con geolocalización GPS, optimizada para entornos de alta resiliencia y despliegue rápido.

---

## 🚀 Características Principales

* **Control de Inventario en Tiempo Real**: Gestión por categorías (Salud, Alimentos, Agua, Herramientas) con alertas automáticas de stock crítico y control de unidades.
* **Comandas y Despachos Criptográficos**: Armado de órdenes de salida con generación de códigos QR y sellado de seguridad mediante **HMAC-SHA256** para auditorías inalterables.
* **Censo Situacional con GPS**: Captura automática de coordenadas geográficas, registro de integrantes, vulnerabilidades y necesidades urgentes de los hogares afectados.
* **RBAC Estricto (Control de Acceso)**: Niveles de privilegios diferenciados (Administrador, Coordinador, Operador y Voluntario) para blindar acciones críticas.
* **Resiliencia Offline (IndexedDB + LocalStorage)**: Capacidad de operar sin conexión a internet respaldando los datos localmente en el navegador y sincronizando al reconectar.
* **Reportes y Exportación**: Generación nativa de reportes tabulares en formato Excel (`.xlsx`) y respaldos completos en JSON.

---

## 🛠️ Tecnologías Utilizadas

* **HTML5 / CSS3 / JavaScript (Vanilla)**: Arquitectura ligera sin dependencias de frameworks pesados de compilación.
* **Tailwind CSS**: Framework de utilidades CSS para diseño responsivo y moderno en modo oscuro.
* **Lucide Icons**: Iconografía moderna y limpia.
* **Dexie.js / IndexedDB**: Almacenamiento estructurado robusto del lado del cliente.
* **CryptoJS**: Implementación de criptografía HMAC para la firma y verificación de bitácoras.
* **SheetJS (xlsx)**: Exportación de datos a hojas de cálculo de Excel.
* **QRCode.js**: Generación dinámica de códigos QR para las comandas de despacho.

---

## 📂 Estructura del Proyecto

```text
mi-proyecto-logistica/
├── public/
│   └── favicon.ico
├── index.html        # Aplicación completa autocontenida (Frontend + Lógica SPA)
└── vercel.json       # Configuración de enrutamiento para Vercel
