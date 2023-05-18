<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <h1>Instrucciones generales:</h1>
    <ul>
      <li>Tu proyecto deberá estar escrito en C.</li>
      <li>Tu proyecto debe estar escrito siguiendo la Norma. Si tienes archivos o funciones adicionales, estas están incluidas en la verificación de la Norma y tendrás un 0 si hay algún error de norma en cualquiera de ellos.</li>
      <li>Tus funciones no deben terminar de forma inesperada (segfault, bus error, double free, etc) ni tener comportamientos indefinidos. Si esto pasa tu proyecto será considerado no funcional y recibirás un 0 durante la evaluación.</li>
      <li>Toda la memoria asignada en el heap deberá liberarse adecuadamente cuando sea necesario. No se permitirán leaks de memoria.</li>
      <li>Si el enunciado lo requiere, deberás entregar un Makefile que compilará tus archivos fuente al output requerido con las flags -Wall, -Werror y -Wextra y por supuesto tu Makefile no debe hacer relink.</li>
      <li>Tu Makefile debe contener al menos las normas $(NAME), all, clean, fclean y re.</li>
      <li>Para entregar los bonus de tu proyecto deberás incluir una regla bonus en tu Makefile, en la que añadirás todos los headers, librerías o funciones que estén prohibidas en la parte principal del proyecto. Los bonus deben estar en archivos distintos _bonus.{c/h}. La parte obligatoria y los bonus se evalúan por separado.</li>
      <li>Si tu proyecto permite el uso de la libft, deberás copiar su fuente y sus Makefile asociados en un directorio libft con su correspondiente Makefile. El Makefile de tu proyecto debe compilar primero la librería utilizando su Makefile, y después compilar el proyecto.</li>
      <li>Te recomendamos crear programas de prueba para tu proyecto, aunque este trabajo no será entregado ni evaluado. Te dará la oportunidad de verificar que tu programa funciona correctamente durante tu evaluación y la de otros compañeros. Y sí, tienes permitido utilizar estas pruebas durante tu evaluación o la de otros compañeros.</li>
      <li>Entrega tu trabajo en tu repositorio Git asignado. Solo el trabajo de tu repositorio Git será evaluado. Si Deepthought evalúa tu trabajo, lo hará después de tus compañeros. Si se encuentra un error durante la evaluación de Deepthought, esta habrá terminado.</li>
    </ul>
  </body>
</html>
<!DOCTYPE html>
<html>
  <head>
  </head>
  <body>
    <h1>Parte obligatoria:</h1>
    <ul>
      <li>Nombre de programa: libftprintf.a</li>
      <li>Archivos a entregar: Makefile, *.h, */*.h, *.c, */*.c</li>
      <li>Makefile: NAME, all, clean, fclean, re</li>
      <li>Funciones autorizadas: malloc, free, write, va_start, va_arg, va_copy, va_end</li>
      <li>Se permite usar: libft (sí)</li>
      <li>Descripción: Escribe una librería que contenga la función ft_printf(), que imite el printf() original. Debes reprogramar la función printf() de la libc. El prototipo de ft_printf() es: int ft_printf(char const *, ...).</li>
      <li>Aquí tienes los requisitos:
        <ul>
          <li>No implementes la gestión del buffer del printf() original.</li>
          <li>Deberás implementar las siguientes conversiones: cspdiuxX %</li>
          <li>Tu función se comparará con el printf() original.</li>
          <li>Tienes que usar el comando ar para crear tu librería. El uso de libtool command is forbidden.</li>
          <li>Tu archivo libftprintf.a deberá ser creado en la raíz de tu repositorio.</li>
        </ul>
      </li>
    </ul>
  </body>
</html>
