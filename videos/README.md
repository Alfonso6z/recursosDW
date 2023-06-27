# Etiqueta `<video>` en HTML

La etiqueta `<video>` se utiliza para insertar videos en una página web. Permite reproducir archivos de video en diferentes formatos y proporciona opciones de control, como reproducción, pausa, volumen, etc.

A continuación, se muestra un ejemplo básico de cómo usar la etiqueta `<video>` en HTML:

```html
<video width="426" height="240" controls autoplay loop muted>
  <source src="assets/video.mp4" type="video/mp4">
  Tu navegador no admite la etiqueta de video HTML.
</video>
```

En este ejemplo, se define un video con las siguientes características:

- `width`: Establece el ancho del video en 426 píxeles.
- `height`: Establece la altura del video en 240 píxeles.
- `controls`: Muestra los controles de reproducción del video.
- `autoplay`: Inicia automáticamente la reproducción del video cuando la página se carga.
- `loop`: Reproduce el video en bucle.
- `muted`: Desactiva el sonido del video.

Dentro del elemento `<video>`, se utiliza la etiqueta `<source>` para especificar la ruta del archivo de video y su tipo MIME. Asegúrate de ajustar la ruta y el nombre del archivo de video según tus necesidades.

**Ejercicios**:

1. Crea una página web con dos videos insertados usando la etiqueta `<video>`. Personaliza los atributos, como el ancho, alto, reproducción automática, bucle y sonido.
2. Agrega controles personalizados para los videos, como botones personalizados de reproducción/pausa y barra de progreso personalizada.
3. Experimenta con diferentes formatos de video, como MP4, WebM y Ogg. Asegúrate de proporcionar los archivos de video correspondientes y ajustar la etiqueta `<source>` en consecuencia.
4. Agrega una descripción o subtítulos al video utilizando la etiqueta `<track>`.
5. Aplica estilos CSS a los elementos de video para personalizar su apariencia, como cambiar los colores de los controles y ajustar el diseño.