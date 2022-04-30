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
				<td>FECHA DE PRESENTACIÓN:</td>
				<td>29-Abr-2022</td>
				<td>HORA DE PRESENTACIÓN:</td>
				<td> 11:55 pm.</td>
			</tr>
			<tr>
				<td colspan="3">ALUMNO:
					<ul>
					<li><a href="https://github.com/Mario-Chura">Mario Franco Chura Puma</a></li>
					</ul>
				</td>
				<td colspan="">NOTA:</td>
				<td></td>
			</tr>
			<tr>
				<td colspan="6">DOCENTE:
					<ul>
					<li>Richart Smith Escobedo Quispe (<a href="rescobedoq@unsa.edu.pe">rescobedoq@unsa.edu.pe</a>)</li>
					</ul>
				</td>
			</tr>
		</tdbody>
</table>
</div>

# Mi proyecto Git PROGRAMACIÓN WEB 2
## Alumno: Mario Franco Chura Puma
## Laboratorio E

## Descripcion

Pasos realizados en este proyecto:

- Se creo una cuenta en Github
- Se configuro la cuenta de estudiante
- Crearemos un archivo Readme.md con contenido Markup
- Agregaremos este archivo al staging area usando git add . 
- Hacemos un primer commit en nuestro repositorio local git commit -m “mi
primer proyecto en github”
- Actualizamos el repositorio remoto con git push origin master

## Comandos de Git utilizados

En el presente proyecto se usaron los siguientes comandos.

- [git config](#git_config)
- [git init](#git_init)
- [git clone](#git_clone)
- [git add](#git_add)
- [git commit](#git_commit)
- [git status](#git_status)
- [git push](#git_push)

## git_config

Establece valores de configuración para tu usuario, email, gpg key, algoritmo diff preferido, formatos de archivo y más. Ejemplos:

```sh
git config --global user.name "Mi nombre"
git config --global user.email "usuario@dominio.com"
```

## git_init

Inicializa un repositorio git – crea el directorio .git inicial en un proyecto nuevo o existente. Ejemplo:

```sh
Initialized empty Git repository in /home/username/GIT/.git/
```

## git_clone

Crea una copia de repositorio GIT de una fuente externa. También añade la ubicación original como remota de modo que puedas traerlo de nuevo y lanzarlo si tienes permisos. Ejemplo:

    ```md
    git clone git@github.com:user/test.git
    ```

## git_add
Añade cambios de archivos en tu directorio de ensayo a tu index. Ejemplo:

    ```md
    git add .
    ```

## git_commit
Toma todos los cambios escritos en el index, crea un nuevo objeto de confirmación que apunta a él y establece la rama para que apunte a esa nueva confirmación. Ejemplos:

    ```md
    git add .
    ```
## git_status
Te muestra el estado de los archivos en el index en comparación con los del directorio de trabajo. Enumerará los archivos que no están rastreados (solo en su directorio de trabajo), modificados (rastreados pero aún no actualizados en tu index), y almacenados (añadidos a tu index y listos para comprometerse). Ejemplo:

    ```md
    git status 
    ```
## git_push
Envía todos los objetos modificados localmente al repositorio remoto. Ejemplo:

    ```md
    git push origin master
    ```
