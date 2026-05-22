# sesion-09a

# Bitácora — Primer acercamiento a KiCad y diseño PCB

Durante este primer encargo utilizando KiCad, comenzamos explorando las herramientas básicas para la creación de esquemáticos y placas PCB. Al inicio fue complejo comprender la relación entre los símbolos electrónicos y las huellas físicas, pero poco a poco se logró entender cómo funciona el flujo de trabajo dentro del programa.

Primero realizamos los esquemáticos utilizando distintos componentes electrónicos como switches, capacitores, baterías y speakers. Luego aprendimos a asignar footprints o huellas a cada componente para poder llevarlos posteriormente a la PCB. En esta etapa aparecieron varios errores debido a componentes sin huellas asignadas o conexiones incorrectas entre elementos.

Uno de los aprendizajes más interesantes fue la visualización 3D de la placa. Descubrimos que presionando:

```txt
Alt + 3
````

es posible renderizar la PCB y observar cómo se vería físicamente el proyecto terminado. Esta herramienta ayudó bastante a entender la distribución real de los componentes y detectar errores de espacio o posiciones incorrectas.

También aprendimos a crear los bordes de la placa utilizando la capa:

```txt
Edge.Cuts
```

En esta sección se dibuja manualmente la forma de la PCB mediante líneas. Comprendimos que si el borde no está completamente cerrado, KiCad genera errores al momento de visualizar o exportar el diseño final.

Otro aspecto importante fue aprender a agregar componentes externos y modelos 3D descargados desde internet. En varias ocasiones algunos componentes no existían en las librerías predeterminadas de KiCad, por lo que fue necesario buscar archivos y librerías adicionales en GitHub y otras páginas. Luego estos archivos debían vincularse manualmente a los componentes para que aparecieran correctamente tanto en la PCB como en el render 3D.

Durante el desarrollo aparecieron distintos errores técnicos, especialmente relacionados con:

* componentes sin footprint,
* conexiones mal realizadas,
* pistas cruzadas,
* errores ERC y DRC,
* y problemas al actualizar la PCB desde el esquemático.

Muchos de estos problemas ocurrieron por errores pequeños dentro del esquemático o por no comprender completamente el funcionamiento de ciertas herramientas. Aun así, investigar tutoriales y documentación en internet ayudó bastante a complementar la información vista en clases y permitió avanzar con mayor seguridad.

Finalmente, este primer acercamiento a KiCad permitió comprender de manera más práctica cómo se desarrolla una placa electrónica desde el esquemático inicial hasta su representación física en PCB y en render 3D. A pesar de las dificultades y errores durante el proceso, la experiencia ayudó a entender mejor tanto las capacidades del software como la lógica detrás del diseño electrónico.

<img width="1052" height="723" alt="esquematicoyerrores" src="https://github.com/user-attachments/assets/38b81455-ea6c-43e1-893a-b7b63561e343" /> 


El capítulo 1 habla sobre la importancia que tienen las imágenes en la vida humana y cómo estas han sido una herramienta para entender el mundo desde hace muchísimo tiempo. El autor explica que las imágenes no son solamente algo decorativo o artístico, sino que también ayudan a las personas a interpretar la realidad, recordar momentos y transmitir ideas o emociones. Antes incluso de la escritura, las personas ya utilizaban dibujos y símbolos para comunicarse y darle sentido a lo que veían a su alrededor. Por eso, las imágenes siempre han estado muy ligadas a la forma en que pensamos y entendemos las cosas.

Algo interesante del capítulo es la comparación que hace entre las imágenes y los textos. Las imágenes permiten entender algo de manera rápida y emocional; muchas veces una sola fotografía puede transmitir sentimientos o situaciones sin necesidad de palabras. En cambio, los textos requieren un proceso más lento, porque hay que leer, analizar y seguir un orden. El autor no dice que uno sea mejor que el otro, sino que funcionan de maneras distintas y se complementan. Gracias a esto, uno puede darse cuenta de cómo hoy en día estamos rodeados constantemente de imágenes: redes sociales, publicidad, televisión, fotografías y pantallas en general.

También se hace una crítica a cómo las imágenes pueden influir demasiado en nuestra forma de ver la realidad. Muchas veces creemos que lo que vemos en una foto o en una pantalla representa completamente la verdad, cuando en realidad sigue siendo solo una representación. Esto pasa mucho actualmente con las redes sociales, donde las personas muestran versiones editadas o seleccionadas de sus vidas. El capítulo invita a pensar de manera más crítica sobre las imágenes y entender que no solo muestran la realidad, sino que también pueden cambiar la forma en que la percibimos.
