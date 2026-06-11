[README.md](https://github.com/user-attachments/files/28835888/README.md)
# toma

**Deja de hacer scroll. Dale al play.**

*toma* es una PWA móvil que te recomienda películas y series **disponibles de verdad en tus plataformas de streaming**, según tu mood, el tiempo que tienes y tus gustos. Sin registros, sin servidores, sin algoritmos opacos: un solo archivo HTML.

<p align="center">© 2026 Frescocan · CC BY-NC-SA 4.0</p>

---

## ✦ Qué hace

- **Recomendaciones reales**: consulta [TMDB](https://www.themoviedb.org) en directo y filtra por las plataformas que tú tienes (Netflix, Prime Video, HBO Max, Apple TV+, Disney+) en tu país (España, Italia, EE. UU.).
- **Filtros con intención**: género, mood (*tensión, para pensar, reír, visualmente bello, un clásico…*), formato (peli/serie) y tiempo disponible (< 1h, ~2h, maratón).
- **Aprende de ti sin pedirte nada**: cada *Guardar*, *Vista* (¿te gustó?) o *Descartar* afina el porcentaje de afinidad de las siguientes propuestas. Todo se guarda localmente.
- **Ficha completa**: póster, sinopsis en tu idioma, nota, duración y la plataforma exacta donde está disponible.
- **Mi lista**: tu watchlist persistente, con las incorporaciones más recientes arriba.
- **"Otras 4 propuestas"**: re-roll infinito que nunca repite títulos en la misma sesión.

## ✦ Filosofía de diseño

Interfaz editorial sobre fotografía: cápsulas blancas sobre fondo degradado, tipografía [Gabarito](https://fonts.google.com/specimen/Gabarito), logotipo propio. Mobile-first, pensada para usarse como app instalada (Add to Home Screen). Menos es más: una pantalla para decidir, una para tu lista, una para ajustes.

## ✦ Stack

- **1 archivo**: HTML + CSS + JavaScript vanilla. Cero dependencias, cero build.
- **API**: TMDB v3 (gratuita) — descubrimiento, watch providers, vídeos.
- **Persistencia**: almacenamiento local del navegador.
- **Peso**: ~85 KB con el fondo y el logo incrustados.

## ✦ Ponerla en marcha

1. Consigue una clave gratuita de TMDB: [themoviedb.org](https://www.themoviedb.org) → Ajustes → API.
2. Abre `index.html` y pega tu clave en la línea:
   ```js
   const TMDB_KEY='TU_CLAVE_AQUI';
   ```
3. Publícala donde quieras — es 100 % estática:
   - **GitHub Pages**: sube `index.html` → Settings → Pages → branch `main`, carpeta `/root`.
   - **Netlify / Vercel**: arrastra la carpeta.
   - **iPhone**: ábrela en Safari → Compartir → *Añadir a pantalla de inicio*.

## ✦ Potencial / hoja de ruta

Ideas abiertas a contribución:

- [ ] Más plataformas (Filmin, Movistar+, MUBI…) y más países
- [ ] Modo "noche de cine" para decidir en grupo (votación compartida)
- [ ] Trailers integrados in-app
- [ ] Historial visual de lo que has visto, con estadísticas anuales (estilo *Wrapped*)
- [ ] Exportar/importar el perfil
- [ ] Notificación cuando un título guardado cambia de plataforma
- [ ] PWA completa: service worker + offline de Mi lista

## ✦ Contribuir

Las mejoras son bienvenidas. Haz fork, crea tu rama y abre un pull request. Al contribuir aceptas que tu aportación se distribuya bajo la misma licencia del proyecto.

## ✦ Licencia y propiedad intelectual

Este proyecto es **propiedad intelectual de Frescocan** (© 2026) y se publica bajo **[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)**:

- ✅ Puedes usarlo, estudiarlo, modificarlo y mejorarlo.
- ✅ Debes dar crédito y compartir las mejoras bajo la misma licencia.
- ❌ **No puedes usarlo con fines comerciales** sin autorización escrita.
- ❌ La marca y el logotipo de *toma* no se licencian para proyectos derivados.

Datos de películas por [TMDB](https://www.themoviedb.org). Este producto usa la API de TMDB pero no está avalado ni certificado por TMDB.

---

<p align="center">Hecho con criterio en un solo archivo · <a href="https://github.com/frescocan">@frescocan</a></p>
