<div align="center">
<table>
    <theader>
        <tr>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/epis.png?raw=true" alt="EPIS" style="width:50%; height:auto"/></td>
            <th>
                <span style="font-weight:bold;">UNIVERSIDAD NACIONAL DE SAN AGUSTIN</span><br />
                <span style="font-weight:bold;">FACULTAD DE INGENIERÍA DE PRODUCCIÓN Y SERVICIOS</span><br />
                <span style="font-weight:bold;">ESCUELA PROFESIONAL DE INGENIERÍA DE SISTEMAS</span>
            </th>
            <td><img src="https://github.com/rescobedoq/pw2/blob/main/abet.png?raw=true" alt="ABET" style="width:50%; height:auto"/></td>
        </tr>
    </theader>
    <tbody>
        <tr><td colspan="3"><span style="font-weight:bold;">Formato</span>: Guía de Práctica de Laboratorio / Talleres / Centros de Simulación</td></tr>
        <tr><td><span style="font-weight:bold;">Aprobación</span>:  2022/03/01</td><td colspan="2"><span style="font-weight:bold;">Código</span>: GUIA-PRLD-001</td></tr>
    </tbody>
</table>
</div>

<div align="center">
<span style="font-weight:bold;" colspan="6">GUÍA DE LABORATORIO</span><br />
<span>(Formato estudiante)</span>
</div>
<div align="center">
	<span style="font-weight:bold;">INFORME DE LABORATORIO</span>

<table>
		<theader>
			<tr><th colspan="6">INFORMACIÓN BÁSICA</th></tr>
		</theader>
		<tbody>
			<tr>
				<td><span style="font-weight:bold;">ASIGNATURA:</span></td>
				<td colspan="5">Programación Web 2</td>
			</tr>
			<tr>
				<td><span style="font-weight:bold;">TÍTULO DE LA PRÁCTICA:<span></td>
				<td colspan="5">Git - GitHub</td>
			</tr>
			<tr>
				<td>NÚMERO DE PRÁCTICA:</td>
				<td>01</td><td>AÑO LECTIVO:</td>
				<td>2022 A</td>
				<td>NRO. SEMESTRE:</td>
				<td>III</td>
			</tr>
			<tr>
				<td>FECHA DE PRESENTACIÓN::</td>
				<td>28-Abr-2022</td>
				<td>HORA DE PRESENTACIÓN:</td>
				<td> 20:00</td>
			</tr>
			<tr>
				<td colspan="3">INTEGRANTES:
					<ul>
					<li><a href="https://github.com/Mario-Chura">Mario Franco Chura Puma</a></li>
					</ul>
				</td>
				<td colspan="">NOTA:</td>
				<td></td>
			</tr>
			<tr>
				<td colspan="6">DOCENTE(s):
					<ul>
					<li>Richart Smith Escobedo Quispe (<a href="rescobedoq@unsa.edu.pe">rescobedoq@unsa.edu.pe</a>)</li>
					</ul>
				</td>
			</tr>
		</tdbody>
</table>
</div>

<div align="center">
<table>
<theader>
<tr><th colspan="6">SOLUCIÓN Y RESULTADOS</th></tr>
</theader>
<tbody>

<tr><td>I. SOLUCIÓN DE EJERCICIOS/PROBLEMAS:<br>
Primer repositorio en GitHub
- Creamos un nuevo proyecto en GitHub
    - ![Nuevo Proyecto GitHub](github_proyecto_programacion.png)

- Crearemos un repositorio local usando git init
    ```sh
    pwd
    /home/richart/unsa/proyecto
    git init
    ```

- Crearemos un archivo Readme.md con contenido Markup
    ```sh
    echo "# Mi proyecto Git" > README.md
    ```

- Agregaremos este archivo al staging area usando git add .
    ```sh
    git status
    ```
    <pre>
    En la rama main

    No hay commits todavía

    Archivos sin seguimiento:
    (usa "git add <archivo>..." para incluirlo a lo que se será confirmado)
	README.md
    no hay nada agregado al commit pero hay archivos sin seguimiento presentes (usa "git add" para hacerles seguimiento)
    </pre>
    ```sh
    git add README.md
    ```

- Hacemos un primer commit en nuestro repositorio local 
    ```sh
    git commit -m "Mi primer proyecto en github"
    ```
- Asociamos el repositorio local con el repositorio remoto 
    ```sh
    git remote add origin https://github.com/rescobedoq/proyecto
    ```

- Actualizamos el repositorio remoto
    ```sh
    git push -u origin main
    ```

- Ahora podemos verificar en GitHub que nuestro repositorio se actualizó con el proyecto local
    - ![Readme.md](Readme.md.png)

- Cree una clase Java HolaMundo.java que imprima un saludo, compílelo, ignore archivos binarios, agregue archivo al stating area, haga commit y súbalo al repositorio GitHub.
    ```sh
    vim HolaMundo.java
    ```
    <pre>
    public class HolaMundo
    {
        public static void main(String args[]) {
        
            /** */
            System.out.println ("¡Hola mundo!");

        }
    }
    </pre>
    ```sh    
    java -version
    ```
    <pre>
    openjdk version "11.0.14" 2022-01-18
    </pre>
    ```sh
    javac HolaMundo.java
    java HolaMundo
    ```
    <pre>
    ¡Hola mundo!
    </pre>
    ```sh
    vim .gitignore
    ```
    <pre>
    *.class
    .gitignore
    </pre>
    ```sh
    git add HolaMundo.java
    git commit -m "Hola Mundo"
    git push -u origin main
    ```
<br><br></td></tr>
<tr><td>II. SOLUCIÓN DEL CUESTINARIO<br>
Aquí
<br><br></td></tr>
<tr><td>II. SOLUCIÓN DEL CUESTINARIO<br>
<---
<br><br></td></tr>
</tbody>
</table>
</div>

<div align="center">
<table>
<theader>
<tr><th colspan="6">RETROALIMENTACIÓN GENERAL</th></tr>
</theader>
<tbody>
	<td>
	-
	</td>
</tbody>
</table>
</div>

<div align="center">
<table>
<theader>
<tr><th colspan="6">REFERENCIAS Y BIBLIOGRAFÍA</th></tr>
</theader>
<tbody>
	<td>
	-
	</td>
</tbody>
</table>
</div>

