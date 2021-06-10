# Informe de laboratorio N°2
**Integrantes:**

Christian Bonifaz, Jean Jacome, Kevin Sandoval

**NRC:** 5406

**Docente:** Ing. Darwin Alulema

**Tema:** ANÁLISIS DE MALLAS

#### 1. OBJETIVOS 

-Comprender y analizar el concepto de malla y sus caracteristicas, asi como tambien su metodo de solucion para resolver circuitos planos.

#### 2. MARCO TEÓRICO 

<img src="imagenes/malla.png">

#### 3. EXPLICACIÓN DEL PROCEDIMIENTO
3.1 El equipo requerido y utilizado para la elaboracion del circuito es el siguiente:

![materiales](https://user-images.githubusercontent.com/84586968/121449049-993db900-c95e-11eb-907d-aba4af4aab30.png)

3.2 Implemente el circuito que se presenta en la figura 2.1.

![DCircuito](https://user-images.githubusercontent.com/84586968/121449055-9b077c80-c95e-11eb-9498-f4293c17eb78.png)
<img src="imagenes/SCircuito.png" width="600">


3.3 Compare los valores de la tabla y realice sus conclusiones

![tabla](https://user-images.githubusercontent.com/84586968/121449753-09990a00-c960-11eb-991c-5f74692ec33f.png)

#### 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR 
El Flujo de la corriente va a tomar este sentido

![flujo](https://user-images.githubusercontent.com/84586968/121452083-6a2a4600-c964-11eb-8ec1-4e8d9f7ed2bb.png)

Encontramos la corriente aplicando la ley de voltajes de Kirchhoff

![mallas](https://user-images.githubusercontent.com/84586968/121451776-c345aa00-c963-11eb-8644-46c5f0ebbd4a.png)

Se armo un sistema de ecuaciones

![ECU](https://user-images.githubusercontent.com/84586968/121452383-f3417d00-c964-11eb-8a6b-b83a09d35fb1.png)

Resolviendo el sistema de Ecuaciones obtenemos

![Resultado](https://user-images.githubusercontent.com/84586968/121452387-f472aa00-c964-11eb-9913-1dfe45848fcb.png)

Mediante el simulador Tinkercad calculamos los resultamos simulados:

<img src="imagenes/Muestra.png" width="600">

Calculo de Error

![error](https://user-images.githubusercontent.com/84586968/121453237-71eaea00-c966-11eb-8f89-e8eedbd87244.png)

#### 5. VIDEO

#### 6. CONCLUSIONES 

-Por el método de resolucion de mallas podemos resolver circuitos planos complejos por medio de un sistema de ecuaciones, simplificando asi en muchos casos los procesos.

#### 7. BIBLIOGRAFÍA

Salazar, A. (2021). ANÁLISIS POR NODOS Y MALLAS. Retrieved 9 June 2021, from http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf

Ley de Kirchhoff: Análisis de mallas. - HETPRO/TUTORIALES. (2018). Retrieved 9 June 2021, from https://hetpro-store.com/TUTORIALES/ley-de-kirchhoff-analisis-de-mallas/
