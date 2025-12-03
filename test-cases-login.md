Test Cases – Login básico (Web App)

Autor: Sofía Brandi
Fecha: 30/11/2025
Descripción: Conjunto de casos de prueba para validar la funcionalidad de Login en una aplicación web estándar.


TC-001 – Login válido

Objetivo: Verificar que un usuario con credenciales correctas pueda iniciar sesión.
Precondiciones: Usuario registrado.
Pasos:

Abrir la página de login.

Ingresar email válido.

Ingresar contraseña válida.

Presionar “Login”.
Resultado esperado: El sistema redirige al dashboard del usuario.


TC-002 – Contraseña incorrecta

Objetivo: Validar que el sistema no permita login con contraseña errónea.
Pasos:

Abrir la página de login.

Ingresar email válido.

Ingresar contraseña incorrecta.
Resultado esperado:
Se muestra mensaje de error: “Credenciales inválidas” y NO inicia sesión.


TC-003 – Email con formato inválido

Objetivo: Asegurar que el sistema valide el formato del email.
Pasos:

Abrir login.

Ingresar email sin “@” o sin dominio.

Ingresar contraseña válida.
Resultado esperado:
Se muestra error de validación: “Ingrese un email válido”.


TC-004 – Campos vacíos

Objetivo: Verificar que no se pueda enviar el formulario vacío.
Pasos:

Abrir login.

No ingresar datos.

Presionar “Login”.
Resultado esperado:
Mensajes de error debajo de los campos requeridos.


TC-005 – Recordar contraseña

Objetivo: Validar que el checkbox “Recordarme” funcione correctamente.
Pasos:

Abrir login.

Ingresar email y contraseña válidos.

Activar “Recordarme”.

Iniciar sesión.

Cerrar sesión.

Volver al login.
Resultado esperado:
El email aparece pre-cargado.
