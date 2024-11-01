![Banner de login](login-html.png)

# Login de correo dinamico.
<p align="left">
<a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a>
</p>

Formulario 
El formulario utiliza onsubmit="e => preventDefault()" para evitar que la página se recargue al enviar el formulario. Esto es útil si deseas procesar los datos de manera dinámica (por ejemplo, con JavaScript), en lugar de hacer que la página se envíe y recargue.
Campo de Correo Electrónico:

Etiqueta (<label>): La etiqueta tiene la clase form-group__label y se estructura de manera que cada letra de la palabra "Email" esté envuelta en un elemento <span> separado, lo que permite estilos personalizados para cada carácter (usando data-splitting para dividir cada letra de manera animada o decorativa).
Campo de Entrada (<input>): Este es el campo de entrada para el correo electrónico. Tiene el tipo email, lo que significa que el navegador verificará automáticamente si el formato del correo electrónico es válido. También utiliza el atributo required, que indica que el campo debe completarse antes de enviar el formulario.
Mensaje de Error: Un mensaje de error que se muestra solo si el usuario no proporciona una dirección de correo válida.
Campo de Contraseña:

Etiqueta (<label>): Al igual que el campo de correo, tiene la palabra "Password" dividida por caracteres individuales para aplicar estilos personalizados.
Campo de Entrada (<input>): Este campo tiene el tipo password, lo que oculta el texto mientras se escribe. También utiliza required, pattern=".{8,}" para validar que la contraseña tenga al menos 8 caracteres, y un title que muestra una pista sobre la longitud requerida.
Mensaje de Error: Muestra un mensaje de error si la contraseña no cumple con el requisito de longitud mínima.
Botón de Envío:

Botón (<button type="submit">): Un botón que, al hacer clic, intenta enviar el formulario. Si hay errores de validación, estos mensajes de error aparecerán según los atributos required y pattern.




<!---[![Login1.png](https://i.postimg.cc/9Q0GsMWb/Login1.png)](https://postimg.cc/5XcYCfQQ)


2.Cuando la contraseña es corta 

[![Login2.png](https://i.postimg.cc/GhhYs2sR/Login2.png)](https://postimg.cc/grQrCGDt)


3.Al escribir

[![Login3.png](https://i.postimg.cc/m2tksFHP/Login3.png)](https://postimg.cc/KRhx7jQb)



4.Validación.

[![Login4.png](https://i.postimg.cc/pLBLQYN1/Login4.png)](https://postimg.cc/SnJ4k9xW)



Ejemplo del codigo!!!!
https://codepen.io/johnjairoac/pen/bGmrGvz --->


