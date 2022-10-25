---
marp: true
author: Grupo 4
theme: default
paginate: true
---

<style>
    :root {
        color: black;
        font-family: H;
        background: linear-gradient(0deg, rgba(0,121,255,1) 0%, rgba(255,255,255,1) 16%, rgba(255,255,255,1) 100%);

    }
    
    h1 {
        text-align: center;
    }

    h2 {
        color: #333c87;
        text-align: center;
        font-weight: bold;
    }

</style>

# PORTADA

---

## ¿Qué es una inyección SQL?

Es una vulnerabilidad que permite al atacante insertar sentencias SQL de forma maliciosa para la manipulación de bases de datos.

![bg right w:500](https://nullsector.co/wp-content/uploads/2018/01/sqlinjection2.png)


--- 

## Pasos para prevenir y mitigar ataques de inyección SQL.

- Usar declaraciones prediseñadas o consultas parametrizadas.
- Validar la entrada del usuario.
- Mostrar mensajes de error genéricos.
- Limitar los privilegios del administrador de la BBDD.

![bg left w:400](https://cdn-icons-png.flaticon.com/512/564/564631.png)

---

## Medidas de monitorización.

- Herramientas de empresas especializadas.
- SQLiHelper 2.7 SQL Injection.
- Pangolin.
- SQLMap.

![bg right w:450](https://static.vecteezy.com/system/resources/previews/001/923/518/non_2x/laptop-computer-with-magnifying-glass-isolated-icon-free-vector.jpg)

---

## EJEMPLO

---

## ¿Cuáles son las fases de un ciberataque?

![bg right w:350](https://www.incibe-cert.es/sites/default/files/blog/CyberKillChain/fases.png)



---

## Fase de Reconocimiento

Esta es la etapa en la que los ciberdelincuentes recopilan información sobre sus objetivos. Para ello, monitorea información sobre los detalles públicos de la organización y busca información sobre la tecnología utilizada, así como datos en redes sociales e incluso interacciones a través de correo electrónico.

![bg right w:400](https://static.wikia.nocookie.net/werewolf20online20espac3b1ol/images/7/7f/Detective.png/revision/latest?cb=20200508235627&path-prefix=es)

---
## Herramienta de Reconocimiento

El atacante realiza una recopilación de datos sobre el comportamiento de la empresa y sus trabajadores, también usa scanners con los cuales puede hacerse una idea de los sistemas y programas que se utilizan. Los datos de la empresa y trabajadores generan, esto incluye redes sociales. está muy relacionados con todo lo que publicamos en Internet.

![bg left w:400](https://images.emojiterra.com/google/noto-emoji/v2.034/512px/1f50d.png)

---
## Fase de Preparación

En esta etapa, el ataque se prepara específicamente para el objetivo. Por ejemplo, un atacante puede crear un documento PDF o de Microsoft Office e incluirlo en un correo electrónico, haciéndose pasar por una persona legítima con la que la empresa suele hacer negocios.

![bg right w:400](https://cdn-icons-png.flaticon.com/512/2644/2644373.png)

---
## Fase de Distribución
En esta fase, por ejemplo, ocurre abriendo documentos infectados enviados por correo electrónico, accediendo a un phishing, etc. Ser conscientes de este tipo de ataques y aprender a reconocerlos será nuestra primera opción de defensa.

![bg right w:550](https://www.creativefabrica.com/wp-content/uploads/2021/05/26/Mail-phishing-icon-simple-style-Graphics-12525333-1.jpg)

---
## Herramienta de Distribución 

ZPHISHER: Es una herramienta que permite suplantar páginas web y obtener de forma ilícita correos, contraseñas y direcciones ip de los usuarios que caigan en este ataque.

![bg left w:400](https://securetechware.com/wp-content/uploads/2020/08/zphisher1.png)

---
## Fase de Explotación

Consiste en "detonar" el ataque, comprometiendo el ordenador infectado y la red a la que pertenece. Esto generalmente se debe a la explotación de vulnerabilidades conocidas que ya tienen parches de seguridad, como la vulnerabilidad de Escritorio remoto, que, si no se corrige, permitiría el acceso externo a su computadora.

![bg right w:500](https://static.vecteezy.com/system/resources/previews/006/842/158/non_2x/cybersecurity-vulnerability-black-glyph-icon-system-weakness-and-flaw-cybercriminal-gains-access-errors-exploitation-silhouette-symbol-on-white-space-isolated-illustration-free-vector.jpg)

---
## Herramienta de Explotación

RAT: Es un troyano de acceso remoto, que incluye una puerta trasera para el control administrativo del ordenador de destino. Generalmente se descargan de manera invisible con un programa solicitado por el usuario, juego o archivo adjunto de email. 

![bg left w:400](https://cdn-icons-png.flaticon.com/512/1995/1995646.png)

---
## Fase de Instalación

Es la etapa en la que el atacante instala el malware a la víctima. También puede haber situaciones en las que no se requiera la instalación, como el robo de credenciales.
 
![bg right w:400](https://cdn-icons-png.flaticon.com/512/2687/2687521.png)

---
## Herramienta de Instalación

ICEPACK realiza todo el proceso de infección y distribución sin necesidad de la intervención inicial de un hacker que manipule páginas web. Dicha herramienta apareció debido a la demanda de la venta de este tipo de software. 

![bg left w:400](https://thumbs.dreamstime.com/b/l%C3%ADnea-icono-del-vector-de-malware-114919577.jpg)

---
## Fase de Comando y control

En este punto, el atacante toma el control del sistema de la víctima, donde puede realizar o iniciar acciones maliciosas desde un servidor central llamado C&C (Command and Control), donde es capaz de robar credenciales, tomar capturas de pantalla, obtener archivos confidenciales, instalar otros programas, conocer cómo es la red del usuario y más.

![bg right w:400]()

---
## Herramienta de Comando y control

**ALCHIMIST C2:**  Puede generar una carga útil configurada, establecer sesiones remotas, implementar la carga útil en las máquinas remotas, ejecutar la terminal ...
- Obtener tamaños de archivo.
- Obtener información del sistema operativo.
- Ejecutar comandos arbitrarios a través de cmd[.]exe.
- Actualizar el implante Insectkt actual.
- Ejecutar comandos arbitrarios como un usuario diferente.
- Dormir por periodos de tiempo definidos por el C2.
- Iniciar/dejar de tomar capturas de pantalla.

![bg left w:400]()

---
## Fase de Acciones sobre los objetos

 Esta es la etapa final en la que los atacantes pueden obtener datos e intentar extender su comportamiento malicioso a múltiples objetivos. Esto explica por qué la kill chain no es lineal sino circular, ya que cada paso se repite para infectar a más víctimas. 

![bg right w:400](https://cdn.icon-icons.com/icons2/390/PNG/512/cycle_38373.png)

---
## Herramienta de Acciones sobre los objetos

![bg left w:400]()

---
##

---
##

---
##

---
##

---
##

---
##

---
##

---
##

---
##

---
##

---
##

---
##
