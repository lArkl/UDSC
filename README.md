# Asignaciones de UDSC

<h2>Grupo 01</h2>

<b>Flujo de trabajo</b>

Para descargar el archivo, en consola usar el comando:
<pre>$ git clone https://github.com/lArkl/UDSC.git</pre>

Para ejecutarlo:
<pre>$ cd UDSC
$ jupyter-notebook [nombre del archivo].ipynb</pre>

<h3>Modificaciones externas del repositorio</h3>

Pueden crear sus ramas directamente con:
<pre>$ git branch [nombre de rama]
$ git checkout [nombre de rama]</pre>

Por ejemplo:
<pre>$ git branch rama1</pre>


Cuando terminen de modificar, guarden sus cambios y despues usen los siguientes comandos:
<pre>$ git add .
$ git commit -m "titulo de las modificaciones"</pre>

Por ejemplo:
<pre>$ git commit -m "Mod del modelo SVC"</pre>

*No olviden actualizar a la última versión de los archivos
<pre>$ git pull origin master</pre>

Las modificaciones se suben al repositorio remoto (el de github) con el siguiente comando:
<pre>$ git push origin [nombre de rama]</pre>

Por ejemplo:
<pre>$ git push origin rama1</pre>

