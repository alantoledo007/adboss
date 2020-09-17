# AdBoss

https://adboss.online

AdBoss está inspirado en **Google Ads** (anteriormente AdWords) y **Google AdSense**. Permite anunciar y monetizar sitios web con los anuncios publicados.

## Tecnologías utilizadas

- PHP (Laravel 7).
- JavaScript (jQuery).
- CSS (Bootstrap 4).
- Google Analitics.
- Google Maps.
- Mercado Pago.

## Features

- Registro de usuarios, login, logout, restablecimiento de contraseña, verificación de correo electrónico y modificación de datos personales (incluyendo el email).
- **Publicar anuncios**: Como empresa o usuario interezado en difundir productos y / o servicios, puedo crearme una cuenta en AdBoss y publicar los anuncios que desee (y se adapten a las políticas).
- **CPC**: El cliente (anunciante) decide cuanto quiere pagar por clic.
- **Autocometitivo / Subasta**: AdBoss tiene un algoritmo que permite determinar un precio recomendado para tu anuncio, basandode en la categoría del anuncio y **la puja de los demás anunciantes**. Además, le notifica al anunciante cuando su oferta es superada, para insentivarlo a competir por un mayor porcentaje de visibilidad.
- **Integración**: Como editor, puedo monetizar mi integrando los anuncios de AdBoss en mi sitio web.
- Los sitio web son verificado antes de poder publicar anuncios.
- **Mercado Pago**: Se integra la API de Mercado Pago en modo booleano. Permitiendo a los usuario cargar cŕedito en su cuenta de AdBoss (Esto permitira difundir anuncios).
- Cada anuncio es verificado antes de difundirce, si se modifica, su estado volverá a ser "En revisión".
- **Los anunciantes puede establecer un límite de crédito por campaña publicitara**.
- Se utiliza la geolocalización de **Google Maps Geocode Json API**, para permitir a los anunciantes selecciar una o más zonas especificas donde anunciar (Países, Provincias, Localidades). Además, se utiliza la geolozalización para determinar la posición del usuario visitante, de esta manera se imprimirán los anuncios correspondientes a cada usuario.
- **Detección de frautes y lista negra**: AdBoss detecta autoclicks, trafico directo y tráfico no valido (este último a travez de una base de datos con vpn) asegurando el dinero invertido por el anunciante. Los usuarios acusados son advertidos en primera instancia, automáticamente por email. Si vuelve a ocurrir, automáticamente se deja de imprimir anuncios en los sitios web del usuario y se banea tanto el usuario como sus dominios relacionados (automático).
- **Conversión de monedas**: AdBoss se maneja con USD, pero Mercado Pago no. Por eso mismo se consume una API para convertir la moneda del usuario en dólares estadounidenses.
