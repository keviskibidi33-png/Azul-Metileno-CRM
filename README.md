# Azul Metileno CRM

Microfrontend Vite/React para el formulario de Azul Metileno consumido por `iframe` desde `crm-geofal`.

## Dominio productivo

- `https://azul.metileno.geofal.com.pe`

## Variables

- `VITE_API_URL=https://api.geofal.com.pe`
- `VITE_CRM_LOGIN_URL=https://crm.geofal.com.pe/login`
- `VITE_MODULE_SLUG=azul-metileno`

## Desarrollo

```bash
npm install
npm run dev
```

## Deploy Coolify

El `Dockerfile` ya compila este repo en la raiz `/` con `VITE_MODULE_SLUG=azul-metileno`, listo para `https://azul.metileno.geofal.com.pe`.
