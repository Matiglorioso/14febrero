# Página de regalo – San Valentín y aniversario

Página web sencilla para dedicar a tu pareja, con video de YouTube integrado.

## Cómo usar

1. **Abrir la página**  
   Haz doble clic en `index.html` o ábrela con tu navegador.

2. **Poner tu video de YouTube**  
   - Abre tu video en YouTube y copia el **ID** (ej: en `https://www.youtube.com/watch?v=abc123xyz`, el ID es `abc123xyz`).  
   - En `index.html`, busca `VIDEO_ID` y reemplázalo por ese ID:
   ```html
   src="https://www.youtube.com/embed/TU_VIDEO_ID_AQUI?rel=0"
   ```

3. **Personalizar textos** (opcional)  
   - **Hero:** el título "Para ti" y el subtítulo "San Valentín y nuestro aniversario".  
   - **Sección del video:** el título "Tu canción" y la frase "Esto es para ti. Te quiero."  
   - **Cierre:** el mensaje en cursiva y la firma "Con amor, para siempre".

## Subir a internet (opcional)

Puedes subir solo la carpeta (con `index.html`) a [Netlify](https://www.netlify.com) o [Vercel](https://vercel.com) arrastrando la carpeta al sitio, y te darán un enlace para compartir.
