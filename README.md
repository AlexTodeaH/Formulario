# Formulario

El formulario está creado con __HTML5__ , __CSS3__ y __JavaScript__.Para que aparezca 
un formulario o otro se oculta y se muestra. Los valores de los `input` está controlado
con el atributo ___pattern___. 

### Cookies
Se han creado 3 funciones para utilizar las __cookies__:
1. _setCookie(nom,val)_ -> Crea la cookie con su nombre y valor
2. _getCookie(nom)_ -> Devuelve la cookie según el nombre
3. _dropCookie(nom)_ -> Eliminia la cookie según el nombre

Cuando se registra el usuario se guarda el nombre y la contraseña (encriptada) en cookies. Y una vez
que vaya a conectarse se busca si coinciden el nombre y la contraseña y se crea una nueva cookie
'conectado' con el nombre del usuario. Así cuando se carga la página _index.html_ se comprueba si
existe una cookie 'conectado' con un nombre y se añadiría en el lugar del usuario. También tiene la
opción de desconectarse y en ese caso se borraría la cookie 'conectado'.