> **Lista de repositorios utilizados para el desarrollo de la propuesta y experimentación de PFC**
> 
> Todo el código en uno solo zip: https://drive.google.com/file/d/1D2lK-qZKLRjVAmlqAvO_89WufFQEtnb8/view?usp=sharing

## Módulo Cache adaptado a edge

- Código relacionado *sólo al módulo*: https://github.com/senabi/incremental-cache-next/tree/main/src/lib/cache.
  - Repositorio donde se utilizó el módulo:
    - Integrado con framework de JS Next.JS https://github.com/senabi/incremental-cache-next
    - Integrado con framework de JS Astro https://github.com/senabi/astro-incremental-cache

## Experimentación
- Código relacionado a la experimentación de la región de N. Virginia `us-east-1`.
  - Repositorio: https://github.com/senabi/unstable-cache-us-east-1-vercel
  - Sitio Web: https://unstable-cache-us-east-1-vercel.vercel.app/close/uncached
- Código relacionado a la experimentación de la región de São Paulo `sa-east-1`.
  - Repositorio: https://github.com/senabi/unstable-cache-sa-east-1-vercel
  - Sitio Web: https://unstable-cache-sa-east-1-vercel.vercel.app/close/uncached
- Código relacionado a la experimentación de `edge`
  - Repositorio: https://github.com/senabi/incremental-cache-next
  - Sitio web: https://incremental-cache-next.pages.dev/
  - Ruta simulando acceso a fuente de datos: https://incremental-cache-next.pages.dev/far/uncached
  - Rutas usando caché: https://incremental-cache-next.pages.dev/far/cached/cache-api - https://incremental-cache-next.pages.dev/far/cached/kv
