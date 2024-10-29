Get_next_line project

Este proyecto consiste en crear una función que lea una línea de un descriptor de fichero especificado y devuelva la línea. Este proyecto introduce nuevos conceptos como la función read() y las variables estáticas. Utilizando una variable estática con un tamaño de búfer especificado, somos capaces de leer desde un archivo y devolver una línea (hasta un carácter "\n" o el final del archivo) sin importar el tamaño del búfer. Cada llamada posterior de la función devolverá la siguiente línea, ya que la función read() conserva su lugar en el archivo que se está leyendo. Mediante el uso de una matriz estática de cadenas, somos capaces de leer desde múltiples FDs al mismo tiempo conservando nuestro lugar en todos ellos.
