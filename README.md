# CAYO Uruguay Landing

Landing mobile-first en HTML/CSS, lista para subir a GitHub Pages o Vercel.

## Archivos principales

- `index.html`: landing principal con botón a WhatsApp.
- `styles.css`: estilos mobile-first.
- `assets/whatsapp-icon.png`: logo de WhatsApp usado en la tarjeta y favicon.
- `politica-de-privacidad.html`: página legal básica.
- `terminos-y-condiciones.html`: página legal básica.

## Cambiar WhatsApp

Abrí `index.html` y reemplazá esta línea:

```js
const phoneNumber = "5490000000000";
```

Por tu número real en formato internacional, sin `+`, sin espacios y sin guiones.

Ejemplo Argentina:

```js
const phoneNumber = "5491123456789";
```

## Cambiar el mensaje automático

En `index.html`, podés editar esta línea:

```js
const message = "Hola, quiero iniciar una conversación.";
```

## Subir a GitHub y Vercel

1. Creá un repositorio nuevo en GitHub.
2. Subí todos los archivos de esta carpeta.
3. En Vercel, importá el repositorio.
4. Usá Framework Preset: `Other` o `Static`.
5. Deploy.


## Versiones con Pixel y números

- `index.html`: versión principal con número 1.
- `index-numero1.html`: WhatsApp `5527992691977`.
- `index-numero2.html`: WhatsApp `5516988310528`.
- Meta Pixel aplicado: `767728059169192`.
- Evento personalizado aplicado al botón: `WhatsAppClick`.

Para usar el segundo número como landing principal, renombrá `index-numero2.html` a `index.html`.
