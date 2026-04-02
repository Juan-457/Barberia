# Barberia

Landing estatica de Skol Barberia con foco en servicios, galeria, branding premium y reserva de turnos.

## Contenido

- `index.html`: pagina principal.
- `barber.webp`: imagen principal del hero.

## Funcionalidad

El sitio incluye:

- hero comercial
- seccion de servicios
- galeria de estilos
- CTA de reserva
- integracion visual con Calendly para turnos
- footer con informacion comercial

## Stack

- HTML estatico
- Tailwind via CDN
- Google Fonts
- widget externo de Calendly

No requiere build.

## Verlo localmente

```bash
cd Barberia
python3 -m http.server 8000
```

Abrir `http://localhost:8000`.

## Deploy

Sitio apto para hosting estatico. Revisar al publicar:

- URL de Calendly
- datos de contacto del footer
- redes o enlaces que hoy figuran como placeholder

## Notas

- El contenido comercial actual parece de demo o MVP. Antes de una salida productiva conviene reemplazar telefono, email, direccion y redes de ejemplo.
