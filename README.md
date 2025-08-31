# 🚀 Integración de la API de Khipu

En este proyecto probé la API de Khipu en un entorno de desarrollo, configurando las claves secretas, el webhook y realizando solicitudes directamente en Postman. En este documento explico paso a paso lo que hice.

## ⚠️ Aclaración
Esta prueba se realizó utilizando exclusivamente **Postman**. No se desarrolló código en ningún lenguaje de programación.
_⚡ Nota: Antes de esta prueba no tenía experiencia con APIs ni con Postman. Agradezco la oportunidad de aprender mientras realizaba esta integración y de poder mostrar lo que fui aprendiendo sobre la API de Khipu._

## 📌 Descripción

La integración incluye la configuración de la API en entorno de desarrollo, con aspectos como:

- Alta de cuenta y generación de claves secretas en el entorno de desarrollo.
- Configuración de la URL de notificación del webhook.
- Creación de un entorno en Postman con las claves secretas y la firma.
- Ejecución de solicitudes POST según la documentación oficial de Khipu.
- Exportación de la prueba en formato JSON desde Postman.

## 🖼 Capturas y pasos que realicé

1.	**Alta de claves y configuración del webhook**
   
<img width="975" height="497" alt="image" src="https://github.com/user-attachments/assets/3f95de55-baf2-4e10-be8d-b3caacbe3331" />



2.	**Creación del entorno en Postman**
   
<img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/f3c0e988-c2e7-4203-89ea-94714b460451" />



3.	**Configuración de la solicitud**
Configuré el tipo de autorización, los headers y el cuerpo de la petición.
   
<img width="975" height="516" alt="image" src="https://github.com/user-attachments/assets/aa0f7c89-3c24-4ae1-a4ee-85d5588b2f20" />



4.	**Obtención de respuesta exitosa y URL de pago**
   
<img width="975" height="520" alt="image" src="https://github.com/user-attachments/assets/d487a097-c5a4-456e-88dd-a59a24277558" />



5. **Pago exitoso**
   
<img width="975" height="492" alt="image" src="https://github.com/user-attachments/assets/5d66759b-3d76-4522-b2d4-a8b64a151c7c" />
   
<img width="975" height="494" alt="image" src="https://github.com/user-attachments/assets/dd6c5650-796c-40a1-a1a7-0f8da573fe04" />



6.	**Generación automática de firma**
Utilicé la IA en Postman para generar un script pre-request que crea la firma y envía la notificación según la guía de Khipu.

<img width="975" height="519" alt="image" src="https://github.com/user-attachments/assets/063fe641-0d01-4cc6-a394-dfbcae392fea" />



7. **Recepción de la notificación del webhook**
Verifiqué que la URL recibiera la notificación con el formato indicado en la documentación de Khipu.

<img width="975" height="495" alt="image" src="https://github.com/user-attachments/assets/82e77a08-655a-42c1-85de-4b72cc2b7fa7" />


<img width="975" height="497" alt="image" src="https://github.com/user-attachments/assets/b7ad2d6c-b431-4714-8b57-0eb027ec5e36" />



8. **Exportación de la colección**
Finalmente, exporté la colección en formato JSON para subirla al repositorio en GitHub.

<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/7cfe8e3c-53a0-4bc5-b705-b7164142722c" />




## ⚙️ Resumen

1. Crear cuenta de desarrollo en Khipu.
2. Registrar las claves secretas y configurar la URL de notificación del webhook.
3. Crear un entorno en Postman con las claves secretas y la firma.
4. Crear una colección en Postman y configurar autorización, headers y scripts.
5. Preparar y ejecutar los requests POST.
6. Verificar la respuesta 200 OK y la correcta recepción de notificaciones.

---
