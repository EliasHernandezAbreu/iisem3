# Interfaces Inteligentes seminario 3

1. **Qué funciones se pueden usar en los scripts de Unity para llevar a cabo traslaciones, rotaciones y escalados.**
Translaciones:
Translate
Rotaciones:
LookAt
Rotate
RotateAround
Escalados:
Usar propiedad localScale

2. **Como trasladarías la cámara 2 metros en cada uno de los ejes y luego la rotas 30º alrededor del eje Y?. Rota la cámara alrededor del eje Y 30ª y desplázala 2 metros en cada uno de los ejes. ¿Obtendrías el mismo resultado en ambos casos?. Justifica el resultado**
	transform.Translate(2, 2, 2);
	transform.Rotate(0, 30, 0);

	No se obtiene el mismo resultado ya que translate usa los ejes locales del objeto, que cambian al realizar la rotación.
3. **Sitúa la esfera de radio 1 en el campo de visión de la cámara y configura un volumen de vista que la recorte parcialmente.**

4. **Sitúa la esfera de radio 1 en el campo de visión de la cámara y configura el volumen de vista para que la deje fuera de la vista.**

5. **Como puedes aumentar el ángulo de la cámara. Qué efecto tiene disminuir el ángulo de la cámara.**
	Aumentando el FOV (Field of View). Tiene efecto de zoom, haciendo que todo se vea más grande
6. **Es correcta la siguiente afirmación: Para realizar la proyección al espacio 2D, en el inspector de la cámara, cambiaremos el valor de projection, asignándole el valor de orthographic**

7. **Especifica las rotaciones que se han indicado en los ejercicios previos con la utilidad quaternion.**

8. **¿Como puedes averiguar la matriz de proyección en perspectiva que se ha usado para proyectar la escena al último frame renderizado?.**

9. **¿Como puedes averiguar la matriz de proyección en perspectiva ortográfica que se ha usado para proyectar la escena al último frame renderizado?.**

10. **¿Cómo puedes obtener la matriz de transformación entre el sistema de coordenadas local y el mundial?.**

11. **Cómo puedes obtener la matriz para cambiar al sistema de referencia de vista**

12. **Especifica la matriz de la proyección usado en un instante de la ejecución del ejercicio 1 de la práctica 1.**

13. **Especifica la matriz de modelo y vista de la escena del ejercicio 1 de la práctica 1.**

14.**Aplica una rotación en el start de uno de los objetos de la escena y muestra la matriz de cambio al sistema de referencias mundial.**

15. **¿Como puedes calcular las coordenadas del sistema de referencia de un objeto con las siguientes propiedades del Transform:?: 
 Position (3, 1, 1), Rotation (45, 0, 45)**
