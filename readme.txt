=== Validar RUT Chile con CF7 ===
Contributors: rafaelcrony
Donate link: https://www.paypal.com/donate/?hosted_button_id=FY3HV6276L26Q
Author: Rafael Andrews
Website: https://www.crony.io
Tags: rut, contact, contact form 7, form, validar, validate 
Requires at least: 5.0
Tested up to: 5.8.3
Stable tag: 1.2
License: GPLv3 or later
License URI: https://www.gnu.org/licenses/gpl-3.0.txt

Validate Chilean RUT field using Contact Form 7 plugin

== Description ==

Validar RUT Chile con CF7, es un plugin simple y sencillo que te permitirá incluir un campo de texto en tu formulario de Contact Form 7 y verificar que sea un RUT chileno válido.
Si el usuario que ingresa datos en el formulario introduce un RUT inválido, al pulsar el botón "Enviar" el sistema le devolverá un error de validación.

Este plugin valida solo el campo de nombre "rut" en tu formulario creado utilizando Contact Form 7.

Ej.: [text* rut]

Valida automáticamente el RUT con puntos y sin puntos, pero siempre es necesario que la persona ingrese el rut con guión, para diferenciar el digito verificador

= ENGLISH DESCRIPTION =

Validate RUT Chile with CF7, will allow you to include a text field in your Contact Form 7 form to validate RUT field.
If the user enters an invalid RUT, on clicking the send button the system will return a validation error.

This plugin validates a field named "rut" in a form created using CF7.

i.e.: [text* rut]

It automatically validates the rut with and without dots, but the dash is required for the RUT verification.

= PRIVACY =

Validar RUT Chile con CF7 does not collect or store any user related data. It does not set cookies, and it does not connect to any third-party websites. It only uses Contact Form 7, related hooks to get a field named rut.

In those terms, Validar RUT Chile con CF7 does not affect your website’s user privacy in any way.

== Installation ==

1. Asegúrese que ha instalado y activado previamente el plugin Contact Form 7
2. Instale el plugin a través del directorio de plugins de WordPress.org o cargando los archivos en su servidor.
3. Active el plugin

Este plugin no necesita configuración y funcionará automáticamente al ser activado.
Agregar un campo en su formulario CF7 con nombre "rut" 
Ej.: [text* rut]

= ENGLISH =

1. Make sure you have previously installed and activated the Contact Form 7 plugin
2. Install the plugin via the WordPress.org plugin directory or by uploading the files to your server.
3. Activate the plugin

This plugin works automatically when activated, it does not need configuration.
Add a field in your CF7 form named "rut"
i.e.: [text * rut]

== Frequently Asked Questions ==

= ¿Puedo usar este plugin si Contact Form 7 no está instalado o activado? =
No, este plugin solo funciona cuando Contact Form 7 está instalado y activado.

= ¿Este plugin se puede configurar? =
No, este plugin funciona automáticamente al ser activado, no necesita ningún tipo de configuración adicional.

= ¿En qué tipo de formato se debe ingresar el RUT? =
Este plugin valida rut con y sin puntos, pero siempre es necesario que la persona ingrese el RUT con guión.

= ¿Se puede traducir a mi idioma? =
Si, puedes ayudarnos a traducir este plugin a tu idioma utilizando el sistema de traducción de plugins de WordPress <a target="_blank" href="https://translate.wordpress.org/projects/wp-plugins/validar-rut-chile-con-cf7/">Traducir plugin.</a><br>Gracias por contribuir.

= ¿Cómo puedo aportar al desarrollo de este plugin? =
Existe un repositorio en GitHub en el que se pueden realizar aportes al código - <a target="_blank" href="https://github.com/crony-io/validar-rut-chile-con-cf7">Repositorio GitHub</a>.

= ¿Puedo modificar el código de este plugin a mi gusto? =
Si, este plugin es de código abierto, por lo que puede ser descargado y modificado.

== Screenshots ==
1. Formulario

== Changelog ==

= 1.2 = 
* Change default strings to english

= 1.1 = 
* Internationalize Plugin for translations
* Remove Unused Chunks

= 1.0.1 = 
* Update Strings

= 1.0.0 =
* Initial release