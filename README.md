# LocalServi Template — Plantilla Web para Negocios de Servicios Locales

**Autoría:** Ascensión — Consultora Web y Digital, Plasencia (Cáceres), España  
**Fecha de creación:** Enero 2026  
**Licencia:** Uso bajo solicitud — Contacto directo para adaptación personalizada

---

## ¿Qué es esta plantilla?

Plantilla web completa en **HTML/CSS/JavaScript puro** (sin dependencias de CMS ni frameworks) diseñada específicamente para **negocios de servicios locales**: fisioterapia, peluquería, salón de uñas, entrenamiento personal, pilates, y cualquier servicio que se ofrezca a domicilio o en un local.

Desarrollada originalmente para **DomiFisio Plasencia** (fisioterapia a domicilio), adaptable a cualquier sector de servicios.

---

## ✨ Característica diferencial

### Botones Llamar + WhatsApp por cada servicio

Cada tarjeta de servicio incluye **dos botones de contacto inmediato**:

- 📞 **Llamar** — enlace directo `tel:` al número del negocio
- 💬 **WhatsApp** — mensaje predefinido y personalizado para ese servicio concreto

```html
<!-- Ejemplo: el botón WhatsApp abre un mensaje ya escrito -->
<a href="https://wa.me/34XXXXXXXXX?text=Hola,%20quiero%20información%20sobre%20*Fisioterapia%20Manual%20a%20Domicilio*">
  WhatsApp
</a>
```

El usuario no tiene que pensar qué escribir. Pulsa y el mensaje ya está redactado con el servicio que le interesa. Esto reduce la fricción al mínimo y aumenta la tasa de contacto, especialmente en móvil.

**Pensado para personas mayores:** tamaño de botones generoso, colores con buen contraste, sin pasos intermedios.

---

## 📁 Estructura del repositorio

```
localservi-template/
│
├── index.html                          # Página principal con las tarjetas de servicios
├── fisioterapia-manual-domicilio.html  # Ejemplo: página individual de servicio 1
├── rehabilitacion-movilidad-domicilio.html  # Ejemplo: página individual de servicio 2
├── ejercicio-terapeutico-domicilio.html     # Ejemplo: página individual de servicio 3
├── entrenamiento-personal-domicilio.html    # Ejemplo: página individual de servicio 4
├── pilates-plasencia.html              # Ejemplo: página individual de servicio 5
│
├── aviso-legal.html                    # Aviso legal (RGPD, España)
├── politica-privacidad.html            # Política de privacidad
├── condiciones-servicio.html           # Condiciones del servicio
│
├── robots.txt                          # Configuración para buscadores
├── sitemap.xml                         # Mapa del sitio para SEO
├── site.webmanifest                    # Configuración PWA
├── default.php                         # Redirección de seguridad PHP
│
├── favicon.ico                         # Favicons (múltiples formatos)
├── favicon.svg
├── favicon-96x96.png
├── apple-touch-icon.png
├── web-app-manifest-192x192.png
├── web-app-manifest-512x512.png
│
└── images/                             # Carpeta de imágenes del negocio
    └── (imágenes del negocio — no incluidas por privacidad)
```

---

## 🛠️ Qué incluye técnicamente

### SEO Local avanzado
- **Schema.org JSON-LD** completo: `LocalBusiness`, `Physiotherapy` (adaptable a `HairSalon`, `BeautySalon`, `SportsActivityLocation`, etc.)
- `OfferCatalog` con cada servicio como `Offer` + `Service`
- **Geo tags** para posicionamiento local (`geo.region`, `geo.placename`, `geo.position`)
- **Open Graph** para compartir en redes sociales
- Meta tags optimizados por servicio

### Accesibilidad y rendimiento
- `aria-label` en todos los botones de llamada y WhatsApp
- Imágenes con `width` y `height` para evitar CLS (Core Web Vitals)
- `loading="lazy"` en imágenes secundarias
- `preload` para la imagen principal del hero
- Sin dependencias externas (sin jQuery, sin Bootstrap)

### Páginas legales completas (RGPD España)
- Aviso Legal + Política de Privacidad
- Condiciones del Servicio con política de cancelación
- Adaptadas a negocios de servicios a domicilio en España

### Diseño responsive
- Mobile-first
- Grid adaptativo: 1 columna (móvil) → 2 columnas (tablet) → 3 columnas (desktop)
- Header con menú hamburguesa en móvil, menú horizontal en desktop
- Botones flotantes de llamada y WhatsApp visibles en todo momento

---

## 🎨 Adaptable a cualquier sector

Esta plantilla ha sido diseñada para adaptarse con cambios mínimos a:

| Sector | Schema.org @type | Cambios necesarios |
|--------|------------------|--------------------|
| Fisioterapia | `Physiotherapy` | ✅ Ya configurado |
| Peluquería | `HairSalon` | Color + textos + imágenes |
| Salón de uñas | `BeautySalon` | Color + textos + imágenes |
| Entrenamiento personal | `SportsActivityLocation` | Color + textos + imágenes |
| Pilates / Yoga | `SportsActivityLocation` | Color + textos + imágenes |
| Limpieza del hogar | `LocalBusiness` | Color + textos + imágenes |
| Cuidado de mayores | `LocalBusiness` | Color + textos + imágenes |
| Proyectos sociales / ONG | `NGO` | Adaptación completa |

---

## 💼 Modelo de uso

Esta plantilla **no se vende como producto descargable**. Se ofrece como base para un **servicio personalizado**:

- El negocio proporciona sus datos (nombre, teléfono, servicios, fotos)
- La plantilla se adapta completamente a su identidad y sector
- Se entrega el sitio listo para subir al servidor

**Especialmente orientado a:**
- Emprendedores y pymes con presupuesto limitado
- Negocios locales que necesitan presencia digital profesional sin gran inversión
- Proyectos sociales y asociaciones sin ánimo de lucro (adaptación solidaria)

---

## 📞 Contacto

Para solicitar adaptación de esta plantilla para tu negocio o proyecto:

- **LinkedIn:** [Ascensión — Consultora Web y Digital]
- **Ubicación:** Plasencia, Cáceres, Extremadura, España
- **Especialidad:** Sitios web para negocios locales, emprendedores y proyectos sociales

---

## 📄 Propiedad intelectual

El código, diseño y estructura de esta plantilla son obra original de su autora.  
El sitio web de DomiFisio Plasencia fue el proyecto base sobre el que se desarrolló esta plantilla.  
Todos los derechos reservados. Uso, copia o distribución sin autorización expresa está prohibida.

© 2026 — Ascensión, Plasencia, España
