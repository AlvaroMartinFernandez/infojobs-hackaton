# Hackaton-Infojos

Esta seria un APi para Backend en Node.JS y express.(Anticipadamente pido disculpas no tuve tiempo ha hacer el front pero me parece un proyecto interesante)

FUNCIONALIDAD:

1-Busqueda ofertas filtradas por provincia donde vive el solicitante y las subcategorias preferidas (inicialmente queria añadirse tambien las opciones de solo teletrabajo,
pero la API no devuelve dicho campo se tiene que notificar a ingojobs).

   Mediante solicitudes a la API de Infojobs solicitaremos la siguiente informacion del perfil:
      - Mi codigo de CV.
      - Mi datos academicos.
      - Mi experecia Laboral.
      - Habilidades tecnicas
      - Mis preferencias laborales
     Toda esta informacion la utilizaremos para realizar una seleccion de las ofertas en el lugar que se reside y con las categorias preferidas.
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/8148e9f4-04e9-42bb-8ea4-a83aa3a54f74)
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/c134a276-d084-43c7-97cc-b879803fef3f)
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/e65fa25e-2ae2-457c-b4fa-40683a0b6190)
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/7a68b7e2-7879-48f7-b7bc-4c5c6f983d47)
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/643b3546-52b3-4236-bc4f-c52986f8acc8)



     
2-Filtrado de las 2 ofertas mas compatibles con tu perfil segun chat gpt:
  
    Para evitar el uso innecesario de recursos en al api en estado inicial hemos mandado solo 5 ofertas a chat gpt y mediante la informacion de nuestro perfil basada en la experencia los datos academicos
    y las habilidades tecnicas le hemos indicado que elija las 2 ofertas mas compatibles con nuestro perfil.
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/a460761c-8693-4394-a218-9282e328f4c2)

3- Se procedera a incribirse en la ofertas preseleccionadas de manera autonoma
    Mediante chat gpt responderemos a las preguntas en funcion de nuestro perfil en caso de que las haya y procederemos a incribir la oferta tal y como vemos en las imagenes.
 ![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/003a9bb1-601d-4e8f-99e3-b7e937511ddc)
![image](https://github.com/AlvaroMartinFernandez/infojobs-hackaton/assets/91843474/6d205f74-9e3a-45a3-a581-a51c99a63f86)

