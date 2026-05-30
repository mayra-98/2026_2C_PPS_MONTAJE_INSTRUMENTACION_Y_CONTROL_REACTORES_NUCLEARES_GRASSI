

# Ingeniería de montaje y construcción de instrumentación y control del sistema de rotación de silicios para reactores de investigación de pileta abierta 
### Universidad Nacional de Lomas de Zamora — Facultad de Ingeniería 
### Práctica Profesional Supervisada – Ingeniería Mecatrónica
**Año:** 2026

**Alumno:** Grassi Mayra Anabel

## Índice
- [Introducción](#introducción)
- [Objetivo](#objetivo)
- [Detalle del trabajo realizado](#detalle-del-trabajo-realizado)
- [Conclusiónes](#conclusiónes)
- [Autor](#autor)

---

## Introducción

El desarrollo del reactor nuclear está compuesto de una gran cantidad de sistemas, los cuales poseen funciones específicas e ingeniería correspondiente. En esta oportunidad he trabajado y colaborado en el Sistema de Rotadores de Silicio, el cual es solo una pequeña parte del proyecto. El sistema de rotadores consiste en suministrar agua a presión mediante un grupo de bombeo a turbinas que comandan la rotación de lingotes de silicio dentro del tanque reflector del núcleo del reactor, con la finalidad de que estos materiales sean irradiados con neutrones uniformemente durante un período de tiempo determinado, produciendo el dopado del material y mejorando así su conductividad. Esto luego es utilizado en el mercado de materiales semiconductores. Hay lingotes de silicio de distintos tamaños y se distribuyen alrededor del núcleo tal como se muestra en la imagen 1. El grupo de bombeo está conformado por 3 bombas idénticas en las cuales, 2 de ellas se encuentran operativas y la restante funciona de respaldo, aunque van rotando periódicamente. Los motores de las bombas son de velocidad variable a través de un variador de frecuencia. En el presente informe se detallan las tareas que he realizado en el área de instrumentación y control vinculadas al sistema de rotadores, las cuáles consisten en la colaboración y desarrollo de la constatación o verificación, montaje y conexionado de los instrumentos, programación del PLC y visualización en el SCADA.

### Objetivo

Coordinar y ejecutar el montaje y conexionado de la instrumentación de campo y la programación y control de PLC del sistema de rotadores de silicio de un reactor nuclear multiproósito.


### Detalle del trabajo realizado
- **Constatación, montaje y conexionado de instrumentos de campo.**
El sistema de rotadores cuenta con la siguiente instrumentación para las 
mediciones de las variables: Un transmisor de presión en la descarga de las 
bombas, caudalímetros, sensores de velocidad y de flujo neutrónico para las 
turbinas y válvulas ON/OFF. 
En esta práctica colaboré en el proceso de verificación, montaje y conexión del 
transmisor de presión y las válvulas ON/OFF, el cual, se desarrolla a 
continuación. 
Transmisor de presión (PIT): 
Lo primero que se debe realizar una vez que el instrumento se encuentra 
disponible en la obra es una constatación o verificación interna en el laboratorio 
de instrumentación para corroborar el correcto funcionamiento y si cumplen con 
las especificaciones de la hoja de datos. 
Para la prueba se utilizó una fuente de alimentación de 24 VCC, un multímetro 
digital, un calibrador de procesos con comunicación HART marca Fluke 753 y 
una bomba de presión marca Fluke 700HTP con indicador digital acorde al rango 
de verificación del instrumento. El transmisor de presión utilizado pertenece a la 
marca Rosemount de Emerson modelo 3051 y, también viene con una válvula 
de bloqueo o manifold de 2 vías.

- **Lógica de control con PLC Siemens.**
El propósito del dispositivo es permitir detectar y registrar cada giro de los de los 
rotadores de silicio detectado por el sensor de proximidad inductivo utilizado para 
este propósito en las turbinas. Los registros deben poder exportarse para su 
posterior análisis. 
La programación se realizó para un PLC S7-1200 de Siemens y se utilizó el 
software TIA Portal V13.

## Conclusiónes

En el presente informe se aplicaron muchos conceptos y herramientas adquiridas 
en la carrera. Se llevó a cabo la verificación del funcionamiento del transmisor 
de presión y las válvulas ON/OFF y su montaje final, incorporando los 
conocimientos adquiridos tanto en electrónica para la parte del cableado y 
conexionado eléctrico, como en mecánica para su montaje mecánico, teniendo 
en cuenta el tipo de conexiones de proceso, materiales y accesorios necesarios. 
También se realizó el programa en el PLC para permitir detectar y almacenar 
cada giro de los de los rotadores de silicio, utilizando los conocimientos 
adquiridos en lenguajes de programación de código y programación en PLC. 
Materias como automatización industrial, diseño de componentes de máquinas, 
mecánica de los materiales, instrumentación industrial y electrónica general y de 
potencia fueron muy útiles para el desarrollo de esta práctica profesional 
supervisada. 
Personalmente considero que la ingeniería mecatrónica es la disciplina ideal 
para un especialista en instrumentación y control, ya que abarca un poco de 
varias disciplinas como en este caso son la mecánica, electrónica y control y que 
son fundamentales para desempeñarse en esta área de la ingeniería en la 
industria. La carrera permite abrir un amplio horizonte de posibilidades en donde 
la persona se puede desempeñar en una empresa, teniendo la oportunidad de 
elegir especializarse en varias disciplinas y no estar acotado inicialmente en una 
sola como poseen otras áreas de la ingeniería. 


## Autor
**Grassi Mayra Anabel**

**Ingeniería Mecatrónica – Universidad Nacional de Lomas de Zamora (FI-UNLZ)**
