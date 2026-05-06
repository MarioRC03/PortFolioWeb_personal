<div align="center">

```
   ╔════════════════════════════════════════════╗
   ║   M.R.C // ctOS_INTRUSION_v2.6             ║
   ║   ────────────────────────────────────     ║
   ║   PORTFOLIO · DEV + ETHICAL HACKING        ║
   ╚════════════════════════════════════════════╝
```

**Un portfolio interactivo construido en una sola página HTML.**  
*Vanilla JS · Three.js · 0 frameworks · 0 build steps*

[![Live Demo](https://img.shields.io/badge/▶_LIVE_DEMO-00ff41?style=for-the-badge&logoColor=black&labelColor=000000)](https://tu-url-aqui.netlify.app)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mario-rodriguez-carbonero-384a3032a)

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=for-the-badge&logo=three.js&logoColor=white)](#)
[![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=black)](#)

</div>

---

## `> whoami`

Soy **Mario Rodríguez Carbonero** — desarrollador full-stack y estudiante de hacking ético desde Salamanca. Este repo es mi portfolio: **una única página HTML**, sin frameworks, sin server, sin build process. Pesa lo que pesa porque tiene **animaciones, una red 3D, una terminal interactiva real y un bot encapuchado** que vive en la trastienda.

> No es una landing genérica. Si llegas aquí, dale al switch del fondo y abre la backdoor — ahí está la mitad del proyecto.

---

## `> cat features.txt`

```bash
[OK]  Secuencia de boot ctOS al cargar (typing terminal)
[OK]  Scanlines CRT + flicker constante de tubo de rayos catódicos
[OK]  Cursor crosshair custom verde fosforescente
[OK]  Lluvia de katakana matrix de fondo
[OK]  Red 3D de nodos con Three.js + paralaje del ratón
[OK]  HUD de vigilancia (clock UTC, uptime, CPU, MEM en vivo)
[OK]  Glitch RGB permanente sobre el nombre
[OK]  Decryption effect en los títulos de sección
[OK]  Perfil tipo "expediente del sujeto" con ASCII portrait
[OK]  Skill bars dobles: DEV_MODE / SEC_MODE
[OK]  Terminal interactiva con comandos de verdad
[OK]  Switch fixed bottom + flip 3D a una backdoor secreta
[OK]  CIPHER · hacker encapuchado que repinta la web
[OK]  9 paletas de color (cyberpunk, fuego, oceano, oro, rosa...)
[OK]  Konami code easter egg
```

---

## `> stack --list`

| Capa | Lo que uso |
|---|---|
| Render | Vanilla JavaScript (ES modern) |
| Animación | CSS keyframes + GSAP + ScrollTrigger |
| 3D | Three.js (r128) sobre canvas |
| Tipografía | Chakra Petch · JetBrains Mono · VT323 |
| Build | **Ninguno**. Es un archivo `.html` plano. |
| Server | **Ninguno**. Single-file static site. |

> ¿Por qué sin framework? Porque puedo, y porque a veces lo más impresionante es enseñar que dominas la plataforma sin abstracciones. Carga rápido, deploy en cualquier sitio, código auditable de un vistazo.

---

## `> tree .`

```
portfolio/
└── index.html       # toda la aplicación
```

That's it. Se acabó la estructura del proyecto.

---

## `> make run`

Tres formas, de la más tonta a la más profesional:

```bash
# 1. Abre index.html con doble click

# 2. Sirvelo localmente con cualquier server estático
python3 -m http.server 8000
# o
npx serve

# 3. Deploy directo (recomendado)
# arrastra index.html a https://app.netlify.com/drop
```

No hay `npm install`. No hay `package.json`. No hay nada que romper.

---

## `> ls /easter_eggs`

### Terminal interactiva (sección `05_terminal`)

Una shell de verdad con historial (flechas ↑↓):

| Comando | Output |
|---|---|
| `help` | lista todos los comandos |
| `whoami` | identidad del visitante |
| `skills` | barras de skills en ASCII |
| `ls /ops` | listado de operaciones |
| `cat /ops/3` | detalle de la operación N (1–6) |
| `hack` | secuencia de breach simulado |
| `matrix` | unos 1s y 0s muy fotogénicos |
| `sudo` | la broma clásica de Linux |
| `clear` | limpia consola |
| `echo <txt>` | repite |

### CIPHER · la backdoor

Pulsa el switch fijo abajo (`PORTFOLIO ⇄ BACKDOOR`) y entras en la trastienda. CIPHER es un bot encapuchado que te pide un tema y te repinta la web. Reconoce keywords en español e inglés:

```
matrix · cyberpunk · fuego · ocean · oro · rosa · sangre · naranja · blanco
```

Acepta lenguaje natural (`"ponme algo morado"` → cyberpunk · `"halloween"` → naranja · `"2077"` → cyberpunk).

> 🔒 **Los temas son efímeros**: viven solo en memoria de la pestaña.  
> Al recargar o cerrarla, la paleta original siempre vuelve. Sin `localStorage`, sin cookies.

Y CIPHER tiene réplicas escondidas. Pruébale:

```
te quiero · kill · mario · quien eres · donde estoy · hack
```

### Konami code

```
↑ ↑ ↓ ↓ ← → ← → B A
```

Suelta a ver qué pasa.

---

## `> cat author.json`

```json
{
  "name": "Mario Rodríguez Carbonero",
  "alias": "M.R.C",
  "location": "Salamanca, ES",
  "role": "Full-Stack Developer",
  "studying": "Máster en Ciberseguridad",
  "background": ["DAM", "DAW"],
  "status": "open_to_work",
  "channels": {
    "linkedin": "/in/mario-rodriguez-carbonero-384a3032a",
    "github": "/tu-usuario"
  }
}
```

---

## `> cat license.txt`

MIT. Usa el código si te sirve. Si te inspira para hacer el tuyo, una mención no estaría mal — pero tampoco te lo voy a exigir.

---

<div align="center">

```
> echo $STATUS
ONLINE_AND_BUILDING

> _
```

**Si estás reclutando** y te ha gustado lo que has visto, ya sabes dónde estoy.

</div>
