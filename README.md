# Delosfit — Propuesta de Alianza Comercial

Landing interactiva de la propuesta **Delosfit × El Empanadazo Margariteño**.
Sitio estático: un solo `index.html` sin dependencias ni build.

## Publicar en GitHub Pages

1. Crea un repositorio y sube el contenido de esta carpeta a la raíz.
2. Settings → Pages → Source: `Deploy from a branch` → rama `main`, carpeta `/ (root)`.
3. La página queda en `https://<usuario>.github.io/<repo>/`.

> Las metas sociales ya apuntan a la URL absoluta
> `https://vveronicasilva.github.io/alianza-delosfit/`. Si cambias de dominio o de
> repositorio, actualiza `og:url`, `og:image`, `og:image:secure_url`, `twitter:image`
> y `rel="canonical"` en `index.html`.
>
> WhatsApp guarda la vista previa en caché por URL. Después de subir el cambio,
> comparte el enlace con un parámetro nuevo (`...alianza-delosfit/?v=2`) o pásalo
> primero por el depurador de Facebook para refrescarla.

## Archivos

    index.html              landing completa. El logo y las fotos van incrustados
                            dentro del archivo, así que se ven aunque falte assets/
    assets/og-preview.jpg   ÚNICO archivo que debe existir en el repo para que
                            WhatsApp muestre la vista previa (1200×630, solo el logo)
    assets/og-preview.png   misma vista previa en PNG (opcional)

## Enlaces

- CTA "Agendar Reunión": https://wa.link/i1fkam
- Instagram: @delosfit
