# Casa del Aroma - Landing Page

Landing page minimalista para Casa del Aroma con enlaces a WhatsApp y Facebook.

##  Comandos

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala las dependencias                         |
| `npm run dev`             | Inicia el servidor local en `localhost:4321`     |
| `npm run build`           | Construye el sitio para producción en `./dist/`  |
| `npm run preview`         | Previsualiza la build localmente                 |

##  Configuración

Antes de desplegar, actualiza los siguientes enlaces en `src/pages/index.astro`:

1. **WhatsApp**: Cambia `https://wa.me/1234567890` por tu número de WhatsApp (incluye código de país sin +)
2. **Facebook**: Cambia `https://facebook.com/casadelaroma` por tu página de Facebook

##  Desplegar en Vercel

1. Sube el logo a `public/logo.png`
2. Conecta tu repositorio de GitHub a Vercel
3. Vercel detectará automáticamente que es un proyecto Astro
4. ¡Despliega!

O usa el CLI de Vercel:
```sh
npm install -g vercel
vercel
```

##  Estructura

```
/
├── public/
│   └── logo.png          # Logo de Casa del Aroma
├── src/
│   └── pages/
│       └── index.astro   # Landing page principal
└── vercel.json           # Configuración de Vercel
