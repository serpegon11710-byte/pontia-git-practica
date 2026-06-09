# Ejercidio práctico

Repositorio para realizar la práctica del módulo de versionado de código

---

## 1.- Creación del repositorio y primer commit

Creamos la carpeta en el sistema de archivos local donde ubicaremos el repositorio.

Abrimos el bsh de git en Windows en dicha carpeta y ejecutamos:

```bash
git init
```

```Salida
Initialized empty Git repository in D:/Proyectos/Pontia/pontia-git-practica/.git/
```

A continuació0n vamos a nuestro github y creamos el repositorio. Obtenemos la URL y vinculamos nuestro repositorio local con el remoto

```bash
git init
git clone https://github.com/serpegon11710-byte/pontia-git-practica
```

```Salida
Cloning into 'pontia-git-practica'...
warning: You appear to have cloned an empty repository.
```

Añadimos éste fichero al stagging

```bash
git add README.md
```


Y realizamos el commit y el push

```bash
git commit -m "Primer commit del ejercicio práctico del módulo de versionado de código"
git remote add origin git@github.com:serpegon11710-byte/pontia-git-practica.git
git push -u origin main
```

NOTA: Salida no disponible en éste primer commit
