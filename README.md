# xAct-Workshop // Taller de xAct

**EN**:

**What is xAct?**:

*xAct* is a package in *Mathematica* for performing tensor calculations. This symbolic algebra package has proven to be a powerfull tool in some research in different areas of General Relativity. For further information see [https://josmar493.dreamhosters.com/](https://josmar493.dreamhosters.com/).

**About this workshop**:

This is a crash course on the use of xAct that I have given in different institutions. This xAct workshop is meant as an introduction for students and researcher interested in using xAct to perform tensor calculations. This short course is very practical and a notebook for the course has been created for this purpose.  The only prerequisits are to have a Mathematica lincense and to install xAct as described below. Previous knowledge of Mathematica is not assumed and can be easily followed by execuiting cell by cell the course notebook.

**ES**:

**¿Qué es xAct?**:

*xAct* es un paquete de *Mathematica* para realizar cálculo tensorial. Este paquete de algebra simbólica es una poderosa herramienta en diferentes áreas de Relatividad General. Para mayor información consulte  [https://josmar493.dreamhosters.com/](https://josmar493.dreamhosters.com/).

**Acerca de este curso**:

Este es un curso intensivo sobre el uso de xAct que he impartido en diferentes instituciones. Este taller de xAct está pensado como una introducción para estudiantes e investigadores interesados ​​en utilizar xAct para realizar cálculo tensorial. El taller es muy práctico y el curso usa un notebook que he creado con este objetivo.  Los únicos requisitos previos son tener una licencia de Mathematica vigente e instalar xAct como se describe a continuación. No se asumen conocimientos previos de Mathematica y se pueden seguir fácilmente ejecutando celda por celda el cuaderno del curso.

## xAct installation // Instalación de xAct

### Step 0 // Paso 0:

**EN**: Have Mathematica installed. Some institutions give Mathematica licences to their students and researchers. Check wether you are entitled to a Mathematica licence with your institution and install it.

**ES**: Asegúrese de tener Mathematica instalado en su computadora. Algunas instituciones otorgan licencias de Mathematica a sus estudiantes e investigadores. Verifique si tiene derecho a una licencia de Mathematica en su institución e instálela.

### Step 1 // Paso 1: 

**EN**: Go to 

[https://josmar493.dreamhosters.com/download.html](https://josmar493.dreamhosters.com/download.html)

and download the corresponding file (depending if you are using Linux or
Windows or Mac)

**ES**: Vaya a la pagina web

[https://josmar493.dreamhosters.com/download.html](https://josmar493.dreamhosters.com/download.html)

y descargue el archivo correspondiente (dependiendo si es usuario de Linux, Windows o Mac)

### Step 2 // Paso 2:
**EN**: Go to the directory where you downloaded the file (called
xAct_1.1.5.tgz or similar) and uncompress it.

**ES**: Vaya al folder donde descargó el archivo (cuyo nombre es xAct_1.1.5.tgz o similar) y descomprímalo. 

### Step 3 // Paso 3:

**EN**: Open a Mathematica notebook and type 
```
$UserBaseDirectory 
```
and press *shift* and *enter* (at the same time) to evaluate that cell.
Then, copy the location "X" it gives you. In my case X is
/home/gasperin/.Mathematica

**ES**: Abra un cuaderno de Mathematica y escriba 
```
$UserBaseDirectory 
```
 y oprima *shift* y *enter* (al mismo tiempo) para evaluar esa celda.
Luego, copie la ubicación "X" que te proporciona. En mi caso por ejemplo X es 
/home/gasperin/.Mathematica

### Step 4 // Paso 4: 

**EN**: Open the terminal and go inside "X" to check that there is a
subdirectory called *Applications*.

**ES**: Abra la terminal y entra en la carpeta "X" para comprobar que hay un
subdirectorio llamado *Applications*.

### Step 5 // Paso 5:

**EN**: Inside the directory xAct_1.1.5 there must be a subdirectory
called xAct. Copy this subdirectory called xAct into X/Applications.
**Make sure you have copied the subdirectory xAct into X/Applications and
not xAct_1.1.5.
since the latter is a common mistake in the installation**. The relevant
folder to copy is xAct which is inside xAct_1.1.5.

**ES**: Dentro del directorio xAct_1.1.5 debe haber un subdirectorio
llamado xAct. Copie este subdirectorio llamado xAct en X/Aplicaciones.
**Asegúrese de haber copiado el subdirectorio xAct en X/Applications y
no el directorio xAct_1.1.5 ya que esto último es un error muy común en la instalación.**
Es decir, la carpeta que se debe copiar se llama xAct y esta se encuentra dentro de xAct_1.1.5. 


### Setp 6 // Paso 6:

**EN**: To check you have installed xAct correctly open a mathematica
notebook and type (copy and paste) the following:  
```
 <<xAct`xTensor`
```

and press shift and enter (at the same time) to evaluate the cell. It should give message
about the copyrights of xAct.

**ES**:  Para comprobar que ha instalado xAct correctamente, abra un Mathematica
cuaderno y escriba (copie y pegue) lo siguiente: 
```
 <<xAct`xTensor`
```

y oprima *shift* y *enter* (al mismo tiempo) para evaluar la celda.  Si la instalación es correcta, la celda al evaluarse dará un mensaje
sobre los derechos de autor de xAct.

## Workshop notebook // Cuaderno del taller

**EN**: 

Crash course: The xAct workshop at the Division of Gravitation and Mathematical Physics (DGFM)  of the Mexican Physics Society consists of two sessions of 40mins each and the corresponding notebook can be found here: [crash-course-notebook](Notebooks/xActLectureMexico_workshop.nb)

**Suggestion**: do not execute the whole notebook at once as there are several "quit" commands inside to ensure each section is independent. Execute each cell from begining to end to see what each command does. Delete when necessary the semicolon (;) in each line to display the intermediate steps. The code snippets give begining-to-end examples of short and concrete calculations for applications in general relativity.

**ES**:

Curso corto: El taller de xAct que impartiré en la División de Gravitación y Física Matemática (DGFM) de la Sociedad Mexicana de Física consta de dos sesiones de 40mins cada una y el cuaderno correspondiente lo puede encontrar aquí: [cuaderno-mini-curso](Notebooks/xActLectureMexico_workshop.nb)

**Sugerencia**: no ejecute todo el cuaderno a la vez, ya que hay varios comandos de "quit" dentro para garantizar que cada sección sea independiente. Ejecute cada celda de principio a fin y vea que es lo que cada comando hace. Quite el punto y coma (;) en cada línea para ver los pasos intermedios. Los *code snippets* (fragmentos de código) brindan ejemplos de principio a fin de cálculos breves y concretos para aplicaciones de relatividad general.


## Additional material // Material complementario

**EN**: 

NP calculator: Here you can find a notebook that, given a null tetrad, computes the curvature and spin-coefficients of the Newman-Penrose formalism: [NPcalculator](Notebooks/NP_Calculator.nb)

**ES**:

Calculadora NP: Aqui puede encontrar un cuaderno que, dada una tetrada nula, calcula la curvatura y los coeficientes de espín del formalismo de Newman-Penrose: [CalculadoraNP](Notebooks/NP_Calculator.nb)

## Contact // Contacto

**EN**: If you have comments, suggestions or questions you can send me an email to 

edgar[dot]gasperin[at]tecnico.ulisboa.pt

I have used xAct in several of my research projects, you can have a look at my papers and my research here:

[https://edgargasperin.github.io/](https://edgargasperin.github.io/)

**ES**: Si tienes comentarios, sugerencias o preguntas puedes enviarme un correo a

edgar[dot]gasperin[at]tecnico.ulisboa.pt

He usado xAct en varios de mis proyectos de investigación, puedes echarle un vistazo a mis artículos y a mi investigación en 

[https://edgargasperin.github.io/](https://edgargasperin.github.io/)




