# Realidad virtual bosque encantado

Un ecosistema virtual renderizado con técnicas de modelado 3D que recrea la atmósfera de un bosque encantado, combinando precisión técnica con narrativa mágica para crear una experiencia inmersiva única.

### Herramientas utilizadas
- A-frame
- HTML
- Blender

### Descripción
Un entorno de realidad virtual detalladamente diseñado en Blender, donde cada elemento ha sido modelado y compuesto. El proyecto incluye:
1. Terreno base personalixado desde cero.
2. Texturizado de cesped.
3. Modelos 3D importados de Sketchfab.
4. Iluminación configurada con técnicad de Blender.
5. Implementación del ambiente virtual utilizando A-Frame para interactividad y visualización 3D en navegador. 

### Proceso de creación
El bosque encantado virtual se contruyó mediante un modelado del terreno base en Blender. Aplicación de texturas de césped con la herramienta de hair. 

### Código de html y A-Frame
El archivo HTML utiliza el framwork A´Frame para crear una escena 3D interactiva que se puede visualizar directamente en un navegador web. La escena está diseñada para simular un bosque nocturno con iluminación personalizada y animaciones de luciérnagas. 

#### Estructura general
Se importa la biblioteca de A´Frame para habilitar la ccreación de elementos 3D y realidad virtual.
<a-scene> contiene todos los elementos de la escena.

1. Se define un modelo 3D en formato .glb con el ID modelo, el cual representa el bosque.
  
![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/code1.png)

2. Se establece un cielo estático con un color azul oscuro para simular un ambiente nocturno.

![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/code2.png)

3. Iluminación

![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/code3.png)

- Luz ambiental: Una luz general suave para iluminar toda la escena con baja intensidad.
- Luz direccional: Una luz más intensa que simula la luz de la luna, posicionada en un punto elevado.
- Luz puntual: Una luz adicional para iluminar áreas más oscuras

4. Luciérnagas
Tres esferas animadas simulan luciérnagas que se mueven de forma alternada entre puntos específicos.
Estas esferas tienen materiales emisivos para emitir un brillo azul y un efecto translúcido.

![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/code4.png)

5. Modelo
Carga un modelo 3D del bosque desde el archivo especificado y lo posiciona en el centro de la escena.

![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/code5.png)

6. Cámara
Una cámara fija situada a 1.6 unidades de altura con una vista frontal inicial.

![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/code6.png)

### Modelo del bosque encantado en Blender

![codigo](https://github.com/BritneyG26/realidadvirtual/blob/main/modelo.png)

