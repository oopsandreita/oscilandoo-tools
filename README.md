# Unir múltiples PDFs (Herramienta Oscilandoo)

Esto te permite unir todos los archivos PDF de una carpeta en un solo documento, sin límites de cantidad ni tamaño.
Ideal si tienes libros separados por capítulos o muchos archivos que necesitas juntar en uno solo.

Previamente necesitas tener Python instalado, y después instalar una librería que se llama pypdf.
Eso lo haces en el terminal, escribiendo "pip install pypdf"

📁 Paso 1: Preparar tus archivos

1. Crea una carpeta en tu computador
2. Guarda TODOS los PDFs que quieres unir dentro de esa carpeta
3. Asegúrate de que estén ordenados correctamente

⚠️ IMPORTANTE: nombres de archivos
Para evitar errores en el orden, nombra tus archivos así:

01_capitulo.pdf  
02_capitulo.pdf  
03_capitulo.pdf  
...   

❌ Evita esto:
1.pdf  
2.pdf  
10.pdf  
(porque se ordenan mal)

💻 Paso 2: Configurar el código

1. Abre el archivo `libro_final.py`
2. Busca esta línea:

carpeta_pdfs = r"C:\Users\xxxxxxxxx\xxxxxx\xxxxxxx\xxxxxxx"

3. Reemplaza la linea anterior con la ruta de tu carpeta (esta parte r"C:\Users\xxxxxxxxx\xxxxxx\xxxxxxx\xxxxxxx")

▶️ Paso 3: Ejecutar el script

1. Ejecuta: 
python libro_final.py

📘 Resultado

Se generará automáticamente un archivo:

libro_completo.pdf

en la misma carpeta donde están tus PDFs.

💡 Tips

- Si el orden no queda bien, revisa los nombres de los archivos
- Puedes agregar una portada como "00_portada.pdf"
- Puedes usarlo para libros, guías, apuntes, etc.


Creado por @oscilandoo 💖  
