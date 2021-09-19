# ProyectoPersonal_asistentevirtual
Proyecto Asistente Virtual

Esquema 1.0-
Objetivos: Crear una asistente virtual que aprenda o guarde en memoria respuestas que yo le asigne 

Pasos:
1. Crear la voz hablante y escucha de usuario. (CHECK)
2. Añadirle funcionalidades basicas como sacar definiciones, abrir aplicaciones, darme datos personales.
 2.1 Añadi abrir paginas de internet e implemente accesos automatizados (por ahora en disneyplus)
4. Conectarla con una base de datos de pregunta y respuesta. (CHECK)

Problemas encontrados:
1. El speech_recognition (libreria) es muy lento, le cuesta reconocer ciertas palabras.
2. Al utilizar jupyter labs en remoto encuentro problemas de hacer run a reconocimientos de teclas.
3. El os o subprocesos no me permite mandar comandos como administrador. (Solucionado, lo reemplace)
4. El profesor me elimino el usuario de la base de datos (Solicionado, cree una base de datos en local).
5. Al conectar las paginas adquiriendo el href no me permitia ingresar otros href debido a que no tenia un inicio de sesion activo (Solucionado, utilice selenium en vez de webbrowser).
