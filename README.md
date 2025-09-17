# THE BOYS EGEL PLUS 2025 — Quiz Interactivo (HTML)

Repositorio listo para publicar en **GitHub Pages**.

## ¿Qué incluye?
- `index.html`: **Banco completo** en un solo archivo, con bloque único para **clave oficial** y **justificaciones clínicas extensas**.
- `preview.html`: demo/vista previa del motor del quiz.
- `data/ANSWER_BLOCK.example.json`: ejemplo de bloque con justificaciones (respuestas en `null` para que pegues tu clave).
- `assets/`: (opcional) PDF de origen, si decides publicarlo.

> **Aviso legal**: Verifica que tienes derecho a **redistribuir** el contenido textual del banco de preguntas. El código del simulador se ofrece bajo licencia MIT, pero **las preguntas** y **textos derivados** del PDF pertenecen a sus respectivos titulares.

## Publicación rápida en GitHub Pages
1. Crea un repositorio y sube estos archivos a la **raíz**.
2. En *Settings → Pages*, elige **Deploy from branch** y selecciona la rama (p. ej. `main`) y la carpeta `/ (root)`.
3. Guarda. GitHub publicará tu sitio en unos segundos/minutos.

## Cómo cargar la clave
1. Abre `index.html` en el navegador.
2. Ve a la sección **“Bloque único: Clave oficial + Justificaciones extensas”**.
3. En el editor, pega la clave estilo: `1=C,2=B,3=A,4=A,5=C,...` o pega un JSON con el formato:
   ```json
   {"1": {"answer": "C", "justification": "…"}, "2": {"answer": "B", "justification": "…"}}
   ```
4. Pulsa **Importar bloque** y luego **Guardar en archivo** para descargar tu HTML final con la clave integrada.
