---
title: Theses Supervision
summary: Supervision of PhD, Master and Bachelor Students
tags:
date: '2025-08-18'

# Optional external URL for project (replaces project detail page).
# external_link: ''

# image:
#   caption: 
#   focal_point: 

# links:
#   - icon: 
#     icon_pack: 
#     name: 
#     url: 
# url_code: ''
# url_pdf: ''
# url_slides: ''
# url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

# Table of Contents
- [Table of Contents](#table-of-contents)
  - [Looking for a Supervisor?](#looking-for-a-supervisor)
  - [Preliminary steps](#preliminary-steps)
  - [Introduction to LaTeX](#introduction-to-latex)
  - [Templates](#templates)
  - [Supervised Works](#supervised-works)
    - [PhD Thesis](#phd-thesis)
    - [Master Thesis (TFM)](#master-thesis-tfm)
    - [Bachelor Thesis (TFG)](#bachelor-thesis-tfg)

<div style="text-align: justify"> 

## Looking for a Supervisor?

If you are looking for Bachelor, Master, or PhD Thesis supervision, please [contact me](/#contact) for more information.

---

## Preliminary steps

To register your project on the platform of the University of Málaga you must fill in the following information (that can be sent to me via _Teams_). All the data must be submitted to the platform as plain text, so please, send it to me in this format, do not prepare a formatted document.

- Name
- First Surname
- Second Surname
- NIF/NIE
- Contact phone number
- E-mail address
- Photo (optional)
- Background and Purpose: \
  <em> A paragraph of about 300 words about the motivation of the project. It should answer (somehow and in a general way) the following questions:
  - What is the motivation/importance of doing this dissertation?
  - What problem do you aim to solve?
  - What is the main contribution of the work?
  - What are the expected goals of this dissertation?</em>
- Work plan: \
  <em>Here you have to define what and how is going to be done to achieve them. You should make a short list divided into a series of activities/tasks and/or subtasks (that should be slightly general) and not to describe specific aspects/details of the project. This should also be about 300-400 words spread over a list of 4-6 bullet points depending on the needs of each project. You don't need to be super specific. The section should include the following:
  - How will you work to achieve the previous goals? (documentation, hardware, software, design, manufacturing, implementation, experiments, dissertation writing, etc.)
  - How do you plan to distribute the work over time? There is no need to detail specific days, but to define the (approximated) hours of work that will be devoted to each task: As you may already know, the B.S. theses are 12 ECTS. And 1 ECTS is equivalent to about 25 hours of student work, so you can get an idea of how many hours you have to distribute in total.</em>
- Bibliography: \
  <em>Prepare a list of about 10 references of scientific articles and books (if possible) related to your dissertation. Some of these can be taken from the documents/information I have given you to start preparing your project.</em>


An example of the previous sections is included below (in Spanish):
<details>
<summary><em>Show example</em></summary>

<em>

**Antecedentes y Objeto:**\
  En la actualidad, el uso de manipuladores roboticos se extiende a multitud de aplicaciones, desde entornos industriales, hasta aplicaciones médicas, pasando por la industria del entretenimiento o ayuda en el cuidado de personas mayores. Sin embargo, la mayoría de estas aplicaciones intentan minimizar el contacto físico de los robots con el entorno, especialmente si existe la posibilidad de interactuar físicamente con personas. En este sentido, los contactos se consideran colisiones no deseadas y, en la mayoría de los casos, cuando el robot detecta un contacto, se para. Ésto resulta ineficiente desde el punto de vista de las tareas que pueden realizar estos robots. Por otro lado, si la tendencia es que en los próximos años sea más y más común ver robots coexistiendo con las personas, será necesario el desarrollo de tecnologías, algoritmos y estrategias que les permitan interactuar físicamente con el entorno y con las personas de forma segura y eficiente, es decir, sin pararse ante contactos, si no adaptándose a ellos o incluso usándolos para el beneficio de la tarea. Este problema se puede abordar desde distintos frentes. Por simplificar, un conjunto de líneas de investigación se centran en el hardware, desarrollando sistemas robóticos flexibles, ligeros o blandos; otros, se cnetran en el software, desarrollando sistemas de control adaptativos que permitan a manipuladores robóticos tradicionales adaptarse a los contactos con el entorno de forma segura. La mayoría de estos sistemas se han llevado a cabo para brazos manipuladores de cadena abierta fijos, o en manipuladores móviles. Sin embargo su uso en manipuladores aéreos permanece prácticamente inexplorado. El motivo principal reside en que las fuerzas que se ejercen sobre un manipulador montado en un dron pueden provocar inestabilidades en el propio dron. El desarrollo de manipuladores aéreos que puedan interactuar físicamente y de forma segura y estable con el entorno es aún un desafío para el que la ciencia aún tiene que encontrar una solución válida. Este es un problema muy extenso y complejo como para ser tratado en un TFG en su totalidad. Así, aunque este proyecto se centra en el desarrollo de sistemas de control adaptativos para manipuladores aéreos y no pierde de vista el problema gloibal, pone su foco en la implementación de estos controladores para un manipulador paralelo ligero de tres grados de libertad. Este manipulador ha sido desarrollado por investigadores del departamento de Ingeniería de Sistemas y Automática y ha sido montado y probado en un dron de grandes dimensiones. El objetivo final sería el uso del manipulador aéreo en tareas de búsqueda y rescate, existiendo el requerimiento de interactuar con el entorno o, incluso, con víctimas. Sin embargo, actualmente el manipulador, aunque diseñado para ello a nivel hardware, no dispone de un sistema de control adaptativo que le permita interactuar físicamente con el entorno. El objetivo de este TFG será, por tanto, la implementación de un controlador adaptativo para este manipulador, inlcuyendo el desarrollo de un sistema sensorial que permita conocer las interacciones (fuerzas) y realizar experimentos para evaluar el comportamiento del controlador en diferentes condiciones.


**Plan de Trabajo:**\
  El proyecto seguirá el siguiente plan de trabajo:
  Documentación: Se llevarán a cabo investigaciones bibliográficas y análisis de soluciones existentes que utilicen controladores adaptativos en manipuladores. Se tiene previsto dedicar 10 horas a esta tarea.
  
  Desarrollo del hardware para percepción de fuerzas e instrumentación: se trabajará en la construcción y diseño de un sensor de esfuerzos, colocado en el efector final del manipulador. Se llevará a cabo una solución basada en microcontrolador. que permita obtener las fuerzas de interacción en el efector final y mandárselas como entradas al controlador. Se prevé dedicar 60 horas.
  
  Diseño de un controlador adaptativo. Diseño e implementación de un controlador adaptativo que tenga en cuenta las fuerzas aplicadas en el efector final, así como parámetros proprioceptivos del manipulador (posición y velocidades articulares y cartesianas), y a través los modelos cinemáticos del manipulador, genere la señal de control adecuada para los motores. Se prevé dedicar 130 horas.
  
  Implementación y experimentación: Se llevarán a cabo experimentos con el objetivo de verificar la eficacia y la respuesta del controlador ante diversas condiciones.  Se prevé dedicar 70 horas.
  
  Escritura de la memoria y presentación: Esta parte consiste en la elaboración del documento técnico que se presentará al finalizar el trabajo. Contendrá todos los objetivos establecidos, los aspectos técnicos detallados de la solución desarollada y los experimentos y pruebas para evaluarla. Para esta tarea se pretende emplear 40 horas.

**Bibliografía:**

- J.Noberto Pires, Tiago Godinho (2008, diciembre), Control difuso de fuerza en robótica industrial. Universidad de Coimbra.
- I. Ruano Ruano, L.M. Nieto Nieto, J. Gómez Ortega, F.R. Rubio, Herramientas MATLAB/SIMULINK para el Control de Fuerza de Robots manipuladores. Universidad de Sevilla.
- Adrián Gil Llorente (2019, 10 de octubre), Desarrollo de un controlador de admitancia para el robot humanoide TEO. [Trabajo Fin de Grado] Universidad Carlos III de Madrid.
- Christian Ott, Yoshihiko Nakamura, Admittance Control using a Base Force/Torque Sensor. “IRT Foundation to Support Man and Aging Society”, IFAC Proceedings Volumes, Volume 42, Issue 16, 2009.
- C. Ott, R. Mukherjee and Y. Nakamura, "Unified Impedance and Admittance Control," 2010 IEEE International Conference on Robotics and Automation, Anchorage, AK, USA, 2010, pp. 554-561, doi: 10.1109/ROBOT.2010.5509861.
- Keemink AQ, van der Kooij H, Stienen AH. Admittance control for physical human–robot interaction. The International Journal of Robotics Research. 2018;37(11):1421-1444.
- H. Seraji, "Adaptive admittance control: an approach to explicit force control in compliant motion," Proceedings of the 1994 IEEE International Conference on Robotics and Automation, San Diego, CA, USA, 1994, pp. 2705-2712 vol.4, doi: 10.1109/ROBOT.1994.350927.
- W. Yu, J. Rosen and X. Li, "PID admittance control for an upper limb exoskeleton," Proceedings of the 2011 American Control Conference, San Francisco, CA, USA, 2011, pp. 1124-1129, doi: 10.1109/ACC.2011.5991147.
- K. P. Tee, R. Yan and H. Li, "Adaptive admittance control of a robot manipulator under task space constraint," 2010 IEEE International Conference on Robotics and Automation, Anchorage, AK, USA, 2010, pp. 5181-5186, doi: 10.1109/ROBOT.2010.5509874.
- Sharkawy A-N, Koustoumpardis PN. Human–Robot Interaction: A Review and Analysis on Variable Admittance Control, Safety, and Perspectives. Machines. 2022; 10(7):591.
- Pal A, Dasgupta R, Saha A and Nandi B. (2016). Human-Like Sensing for Robotic Remote Inspection and Analytics. Wireless Personal Communications: An International Journal. 88:1. (23-38). Online publication date: 1-May-2016.
- Joseph, L., & Cacace, J. (2018). Mastering ROS for Robotics Programming: Design, build, and simulate complex robots using the Robot Operating System. Packt Publishing Ltd.

</em>
</details>

---

## Introduction to LaTeX

I leave [here a LaTeX tutorial](https://github.com/jmgandarias/tutorial_latex) that I have made for those who are entering in the fantastic world of LaTeX.If you have already used it, it's not a bad idea to take a look at it (especially the bibliography section, which is one of the most problematic).

I suggest you to create an [Overleaf](https://www.overleaf.com/) profile to start working with LaTeX documents. 
You can share the dissertation docuemtn with me once you have created it. Also, you can make me an owner of the document if you want to take advantage of the _Overleaf Premium_ benefits.

---

## Templates

- **Dissertation template:** A [LaTeX template for the dissertation](https://github.com/jmgandarias/template_TFE). It also incluse some interesting info on how to fill this document.
- **Presentation template:** A presentation template with the official colors and logos of the University
  - [Download the Power Point TFE template.](extra_doc/TFE_template.pptx)
  - [Download the Power Point presentation template.](extra_doc/presentation_template.pptx)
  - [Use the LaTeX template.](https://github.com/jmgandarias/UMA_slides_template)

---

## Supervised Works

### PhD Thesis


- [Safe Manipulation of Humans in Robot-driven Physical Human-Robot Interaction](https://riuma.uma.es/xmlui/handle/10630/30776) 
  - Author: Francisco J Ruiz-Ruiz
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2023
  - PDF available: [Download](theses/PhD_FranciscoRuiz.pdf)

### Master Thesis (TFM)

- [Dynamic modeling of an underactuated gripper for Physical Human-Robot Interaction](https://jabega.uma.es/permalink/34CBUA_UMA/1o1oa5r/alma991010856716204986)
  - Author: Adrián Bañuls Arias
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2020
  - PDF available: [Download](theses/TFM_AdrianBanuls.pdf)

### Bachelor Thesis (TFG)

- [Design and evaluation of variable-stiffness robotic links based on granular jamming](theses/TFG_Tanya_Ilieva.pdf)
  - Author: Tanya Ilieva Timova
  - Supervisors: Juan M. Gandarias and Francisco Pastor
  - Year: 2025
  - [GitHub repository](https://github.com/jmgandarias/TFG_TanyaIlieva)

- [A Reinforcement Learning Framework for Manipulation Tasks with the Franka Robotic Manipulator](theses/TFG_Diego_Caruana.pdf)
  - Author: Diego Caurana Montes
  - Supervisors: Juan M. Gandarias and Juan-Antonio Fernández-Madrigal
  - Year: 2025
  - [GitHub repository](https://github.com/uncore-team/franka_rl) 

- [Implementation of a ROS2-based environment with a sensory system on the Donatello mobile robot of the RoboRescue UMA competition robotics team]()
  - Author: Pablo Lozano Lozano,
  - Supervisors: Juan M. Gandarias and Mauel Castellano Quero
  - Year: 2025
  - [GitHub repository](https://github.com/RoboRescueUMA/donatello_ros2) 

- [Development of a unity-ros2 simulation environment for slam evaluation for autonomous vehicles](theses/TFG_Luis_Arce.pdf)
  - Author: Luis Arce Aranda
  - Supervisors: Juan M. Gandarias and Alonso Llorente Landero
  - Year: 2025
  - PDF available: [Download]

  - 
- [Development of the digital twin of a four-joint robotic arm with ros 2](theses/TFG_Pascual_Gonzalez.pdf)
  - Author: Pascual González Redondo
  - Supervisors: Juan M. Gandarias and Antonio J. Muñoz-Ramírez
  - Year: 2025

- [Development of a simulation model for a mobile manipulator with an omnidirectional robotic base](theses/TFG_Mario_Alber.pdf)
  - Author: Mario Alber Gil
  - Supervisors: Juan M. Gandarias and Jesus M. Gómez-de-Gabriel
  - Year: 2024
  - [GitHub repository](https://github.com/TaISLab/rafi_sim)

- [Development of a software interface for the control of a mobile manipulator with omnidirectional wheels](theses/TFG_Rodrigo_Castro.pdf)
  - Author: Rodrigo Castro Ochoa
  - Supervisors: Juan M. Gandarias and Jesus M. Gómez-de-Gabriel
  - Year: 2024
  - [GitHub repository](https://github.com/TaISLab/Rafi)

- [Adaptive control of a 3-Degree-of-Freedom lightweight parallel manipulator](theses/TFG_Victor_Rosillo.pdf)
  - Author: Víctor Rosillo Suero
  - Supervisors: Juan M. Gandarias and Dahui Lin-Yang
  - Year: 2024
  - [GitHub repository (Admittance Controller)](https://github.com/Robotics-Mechatronics-UMA/admittance_controller)
  - [GitHub repository (3D Force sensor)](https://github.com/Robotics-Mechatronics-UMA/force_sensor_3D)
  - 
- [Design and control of a 3-degree-of-freedom robotic wrist for a lightweight delta manipulator](theses/TFG_David_Rodriguez.pdf)
  - Author: David Rodriguez Onieva
  - Supervisors: Juan M. Gandarias and Fransciso Pastor
  - Year: 2024
  - [GitHub repository](https://github.com/Robotics-Mechatronics-UMA/spherical_wrist_delta)
  
- [Experimental analysis of jamming-based variable stiffness links for robotic manipulators](theses/TFG_Estrella_Isla.pdf)
  - Author: Estrella Isla Sulimma
  - Supervisors: Juan M. Gandarias
  - Year: 2024

- [Development of a high-level ROS package for robotic systems actuated by smart motors](theses/TFG_Maksym_Saldat.pdf)
  - Author: Maksym Saldat
  - Supervisors: Juan M. Gandarias and Jesus M. Gómez-de-Gabriel
  - Year: 2024
  - [GitHub repository](https://github.com/TaISLab/dynamixel_ros_library)
  
- [Low consumption system for remote monitoring of robotic walkers](theses/TFG_Pablo_Aguilar.pdf)
  - Author: Pablo Aguilar Orellana
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2020

- [Design of an underactuated robotic hand with a flexible tactile sensor](theses/TFG_Trinidad_Sanchez.pdf)
  - Author: Trinidad Sánchez Montoya
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2019

- [Sensorized human arm model for researching in physical Human-Robot Interaction](theses/TFG_Jose_Figuerola.pdf)
  - Author: Jose Antonio Figuerola Palacios
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2019

- [Visual control of a parallel aerial manipulator](theses/TFG_Miguel_Medicis.pdf)
  - Author: Miguel de Médicis Barrionuevo
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2019

- [Wearable sensorized wristband for victims monitoring](theses/TFG_Fran_Ruiz.pdf)
  - Author: Francisco J Ruiz-Ruiz
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2018

- [Pressure images data acquisition system for an array, resisitve-based tactile sensor](theses/TFG_Maria_Fernandez.pdf)
  - Author: Maria Fernández Hijano
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2018

- [Connected, portable force measurement device](theses/TFG_Andres_Lorenzo.pdf)
  - Author: José Andrés Lorenzo Robles
  - Supervisors: Jesus M. Gómez-de-Gabriel and Juan M. Gandarias
  - Year: 2018

   </div>