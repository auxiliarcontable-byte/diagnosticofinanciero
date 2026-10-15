# Diagnóstico Financiero

Calculadora de liquidez publicada con Cloudflare Workers (recursos estáticos).

## Estructura

```
.
├── public/
│   └── index.html      <- la calculadora (aquí debe estar tu HTML)
├── wrangler.jsonc      <- configuración del Worker
├── .gitignore
└── README.md
```

## Despliegue

Cada commit a la rama principal se despliega automáticamente en
https://diagnosticofinanciero.auxiliarcontable.workers.dev

Nota: el nombre en `wrangler.jsonc` debe coincidir con el nombre del Worker en Cloudflare.
