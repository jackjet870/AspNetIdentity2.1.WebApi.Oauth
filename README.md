# Tutorial para Implementar Oauth en una soluci�n WebApi con Identity 2.1

#### Autor:
> Victor Cornejo , rex2002xp (at) gmail (dot) com

#### Licencia:
> Creative Commons

####Aclaraci�n
* He tomado como referencia los excelentes art�culos publicados por Taiseer Joudeh sobre el tema, la �nica intenci�n es facilitar el acceso de esta informaci�n en el idioma Espa�ol. En ning�n momento deseo acreditarme o plagiar el excelente trabajo que Taiseer realiza en su blog. Te invito a revisar su blog en [bitoftech.net] no te arrepentir�s.

####Objetivo
Para esta soluci�n he tomado como base el c�digo fuente que se genero en el repositorio [AspNetIdentity2.1.WebApi.sendConfirmation] , de esta forma podemos reutilizarlo y ampliar las funcionalidades.

En esta ocasi�n cubriremos las siguientes funcionalidades:
* Implementacion de Autenticacion por medio de un Token tipo Bearer, enviando usuario y clave al servidor.
* Implementacion de Autorizacion utilizando JWT (Json Web Token) [1].




[AspNetIdentity2.1.WebApi.sendConfirmation]:https://github.com/rex2002xp/AspNetIdentity2.1.WebApi.sendConfirmation
[bitoftech.net]:http://bitoftech.net/
[1]:http://jwt.io/