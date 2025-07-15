# Login
INSTUTUTO TECNOLOGICO DE OAXACA

INGENIERIA EN SISTEMAS COMPUTACIONALES

MATERIA: PROGRAMACION WEB

DOCENTE: MARTINEZ NIETO ADELINA

ALUMNAS: RAMOS JIMENEZ XOCHITL ITAHY, VARELA VERA BIANI BISALUA 

GRUPO: VSI

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

  **Tecnologías Usadas**
  
*Angular:* Framework para desarrollo de aplicaciones SPA (Single Page Application).

*Angular Material:*	Biblioteca de componentes UI con diseño Material Design.

*TypeScript:*	Lenguaje principal del proyecto (superset de JavaScript).

*RxJS:*	Programación reactiva utilizada para trabajar con HttpClient y eventos.

*MockAPI / DummyJSON:*	APIs simuladas usadas para validar inicio de sesión y mostrar productos.

*HTML & CSS:*	Estructura y estilos personalizados de componentes.

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Explicación del Código (Flujo de la App y Métodos Principales)**

*1. Inicio de sesión (IniciarSesion)*

  *Componentes Material usados:* MatInput, MatCard, MatButton, MatSnackBar.
  
  *Formulario reactivo:* (FormBuilder) para capturar email y password.
  
  *Método onSubmit():*
      1. Valida campos requeridos.
      2. Llama a una API (mockapi.io) para obtener la lista de usuarios.
      3. Verifica si el usuario existe y si la contraseña es correcta.
      
  *Si todo es válido:*
      1. Guarda usuario en localStorage.
      2. Muestra mensaje de éxito.
      3. Redirige a pagina-bienvenido.

2. Página de bienvenida (PaginaBienvenido)
Carga datos del usuario desde localStorage y muestra su nombre e imagen.

Carga productos desde la API https://dummyjson.com/products (primeros 9).

Permite:

Filtrar productos por texto (productosFiltrados).

Agregar un nuevo producto mediante un modal (AgregarProducto).

Editar productos (EditarProducto).

Eliminar productos con confirmación (ConfirmDialog).

Ver más detalles de un producto (MensajesProductos).

Cerrar sesión, lo que borra el localStorage y redirige al login.

Abrir modal con logo (LogoModal).


<img width="2874" height="1576" alt="image" src="https://github.com/user-attachments/assets/ca3b28ae-a56b-4522-8fab-d4c5c1132c2b" />

<img width="2866" height="1556" alt="image" src="https://github.com/user-attachments/assets/230db28d-768a-4e73-ad12-4eef02393798" />

<img width="2879" height="1583" alt="image" src="https://github.com/user-attachments/assets/cc73b736-b4e2-490a-84eb-0df9dddf6528" />

<img width="1070" height="1368" alt="image" src="https://github.com/user-attachments/assets/8b8e5c4f-6ac1-45b7-9906-b6d6cd822770" />

<img width="1051" height="1394" alt="image" src="https://github.com/user-attachments/assets/6fd962d9-26ac-4107-b439-5e4fdef791bb" />

<img width="1051" height="1377" alt="image" src="https://github.com/user-attachments/assets/b7162cd2-2b48-465e-85fd-ef8a28ecd728" />

<img width="2761" height="553" alt="image" src="https://github.com/user-attachments/assets/95ff0a4b-f754-4d3f-81f0-7641b15ec224" />

<img width="1039" height="1344" alt="image" src="https://github.com/user-attachments/assets/9576b18c-fbfa-4243-9e47-faee0e23556f" />

<img width="930" height="391" alt="image" src="https://github.com/user-attachments/assets/4a0842b7-913b-4da5-b63f-a1340f592a52" />

<img width="774" height="126" alt="image" src="https://github.com/user-attachments/assets/4c478e0b-2ba6-49e1-b047-018529014711" />

<img width="2775" height="1274" alt="image" src="https://github.com/user-attachments/assets/05dc2bdb-b12e-4ba0-a785-3b5a3ecc0813" />

<img width="1099" height="1359" alt="image" src="https://github.com/user-attachments/assets/fcaf430a-71c2-4d60-ac67-0997abba29b7" />

<img width="2760" height="583" alt="image" src="https://github.com/user-attachments/assets/6c082220-14b5-4651-bb28-f430bd477c44" />

<img width="1034" height="1304" alt="image" src="https://github.com/user-attachments/assets/012b956b-8ec6-45d5-8b56-4bc04320582a" />

<img width="2879" height="1581" alt="image" src="https://github.com/user-attachments/assets/b91569b7-1e62-4732-9aaf-187452ec6dc2" />








