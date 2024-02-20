# Requisitos generales

- El sistema deberá solicitar al usuario cargar documentos pdf escaneados, imágenes en formatos jpeg, jpg, png.

- El sistema deberá tener la opción de confirmar los documentos cargados, para proseguir con el procesado OCR.

- El sistema debe ser capaz de reconocer áreas de texto, columnas, listas, títulos, índices; para poder aplicarle el OCR y darle al usuario un archivo de texto con el texto extraído, y una descripción breve de la ubicación del text extraído por cada .

    > Exactitud
- El texto extraído de los documentos deberá ser lo más fiel al original, es decir, el OCR deberá ser exacto.

    > Seguridad
- EL sistema se restrigirá a extraer el texto de los documentos y entregarlo al usuario, no deberá haber otro proceso que toque los documentos otorgados por el usuario o el texto extraído de estos.

    > Robustez
- El sistema deberá ser capaz de soportar grandes cantidades de documentos, esto puede ser una carpeta contenedora.

