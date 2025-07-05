# jc-2025
Repositorio de laboratorios de capacitacion Jovenes Creativos 2025
<BR>
Autor: Andres Pinzón

# Proceso General

1. Proceso de creacion repositorio local
	1.1. Crear directorio local para el repositorio (intro-git-2025)
	1.2. Abrir la linea de comandos y navegar hacia la carpeta creada (comando cd)
	1.3. Crear el repositorio local mediante el comando git init
	1.4. Consultar intormacion del repositorio (comando git status)

2. Adicionar archivos al repositorio
	2.1. Crear nuevo archivo de texto (intro-01.txt)
	2.2. Adicionar archivo al área de trabajo (comando git add) => git add intro-01.txt
	2.3. Consultar cambios en el área de trabajo (comando git status) => git status
	2.3. Cargar archivo en el repositorio (comando git commit) => git commit -m "Se crea documento inicial."
	2.4. Consultar historial del repositorio (comando git log) => git log

3. Subir repositorio remoto
	3.1. Crear repositorio en portal de GitHub
	3.2. Enlazar repositorio local con repositorio remoto (git remote add origin https://github.com/aapinzonr/intro-git-2025.git)
	3.3. Enviar cambios al repositorio remoto (git push -u origin master)