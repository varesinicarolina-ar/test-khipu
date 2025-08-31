# 🚀 Integración de la API de Khipu

En este proyecto integré la **API de Khipu** en un entorno de desarrollo, configurando las claves secretas, el webhook y probando los requests en Postman. En este documento cuento paso a paso lo que hice.

## ⚠️ Aclaración
Esta prueba se realizó utilizando exclusivamente **Postman** para probar la API de Khipu. No se desarrolló código en ningún lenguaje de programación.
_⚡ Nota: Antes de esta prueba no tenía experiencia con APIs ni con Postman. Agradezco la oportunidad de aprender mientras realizaba esta integración y de poder mostrar lo que fui aprendiendo sobre la API de Khipu._

## 📌 Descripción

Realicé la integración de la API de Khipu en entorno de desarrollo. Esto incluye:

- Alta de cuenta y claves secretas en la cuenta de desarrollo.
- Configuración de la URL de notificación de webhook.
- Creación de entorno en Postman con las claves secretas.
- Ejecución de requests POST según la documentación oficial de Khipu.
- Exportar la prueba en formato JSON con Postman.

## 🖼 Capturas y pasos que realicé

1.	Dí de alta las claves en entorno de Desarrollo y añadí la URL del webhook.
   
<img width="975" height="497" alt="image" src="https://github.com/user-attachments/assets/3f95de55-baf2-4e10-be8d-b3caacbe3331" />



2.	En Postman, creé el entorno con la clave secreta y la firma.
   
<img width="975" height="514" alt="image" src="https://github.com/user-attachments/assets/f3c0e988-c2e7-4203-89ea-94714b460451" />



3.	Configuré el tipo de autorización, headers y cuerpo de la petición.
   
<img width="975" height="516" alt="image" src="https://github.com/user-attachments/assets/aa0f7c89-3c24-4ae1-a4ee-85d5588b2f20" />



4.	Obtuve respuesta exitosa y URL de pago
   
<img width="975" height="520" alt="image" src="https://github.com/user-attachments/assets/d487a097-c5a4-456e-88dd-a59a24277558" />



5.	Pago exitoso
   
<img width="975" height="492" alt="image" src="https://github.com/user-attachments/assets/5d66759b-3d76-4522-b2d4-a8b64a151c7c" />
   
<img width="975" height="494" alt="image" src="https://github.com/user-attachments/assets/dd6c5650-796c-40a1-a1a7-0f8da573fe04" />



6.	En postman, le pedí a la IA que genere un Script pre-request para generar la firma y que llegue la notificación según lo indicado en la guía de Khipu

<img width="975" height="519" alt="image" src="https://github.com/user-attachments/assets/063fe641-0d01-4cc6-a394-dfbcae392fea" />



7.	Recibí la notificación al URL de webhook con el formato que indicaba la documentación de Khipu

<img width="975" height="495" alt="image" src="https://github.com/user-attachments/assets/82e77a08-655a-42c1-85de-4b72cc2b7fa7" />


<img width="975" height="497" alt="image" src="https://github.com/user-attachments/assets/b7ad2d6c-b431-4714-8b57-0eb027ec5e36" />



8. Exporté la colección en formato JSON para subir al repositorio en GitHUB

<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/7cfe8e3c-53a0-4bc5-b705-b7164142722c" />




## ⚙️ Resumen

1. Crear cuenta de desarrollo en [Khipu](https://khipu.com/).
2. Dar de alta las claves secretas y configurar la URL de notificación de webhook.
3. Crear un **entorno** en Postman con las claves secretas y la firma.
4. Crear una **colección** y configurar el tipo de autorización, headers y scripts.
5. Preparar y ejecutar los requests POST.
6. Recibir respuesta 200 OK

---
