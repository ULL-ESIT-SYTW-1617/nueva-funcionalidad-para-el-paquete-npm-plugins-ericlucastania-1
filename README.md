![](http://arunoda.me/images/blog/npm-love-github-thumb.png)



# Descripción

El objetivo de la práctica es llegar a que el usuario puede descargar el plugin gitbook-start-plugin-iaas-ull-es-ericlucastania y el paquete gitbook-start-elt de manera local en su maquina.El usuario tiene que tener en cuenta que tiene que tener previamente un cuenta en el iaas 
y tener un clone de su repositorio. Una vez que se tiene claro los anteriores aspectos comenzamos a explicar los pasos llevar a cabo el correcto funcionamiento de la práctica.



## Pasos a ejecutar 

**1. Instala nuestro paquete de forma global**

```npm install -g gitbook-start-elt```

**2. Instala el plugin del iaas de forma global**

```npm install -g gitbook-start-plugin-iaas-ull-es-ericlucastania```

**3. Ejecuta el binario para el render del template**

```gitbook-start -dir Carpeta``` !!Si no ejecutas el -dir se creará una carpeta con tu nombre de usuario

**4. Entra en la carpeta**

```shell
cd Carpeta
```
**5. Ejecuta el plugin que desees**

```gitbook-start -d iaas``` !! También puedes usar la opción --deploy

**6. Ejecuta el comando npm install para instalar las dependencias**

```npm install```

**7. Ejecuta el gulp creado**

```gulp deploy-iaas```

#### Explicación

Cunado se ejecuta el gitbook-start -d iaas se te lanzará el initialize del módulo,
el initialize crea una tarea en el gulp para realizar el deploy. Además de guardarte el paquete
elegido en el package.json.

## Opciones

    gitbook-start [OPTIONS]
        -d nombre del directorio a crear node gitbook-star -d miDirectorio
        -a autor del libro a crear node gitbook-star -a AutorDelLibro
        -r repositorio github contra el que se va a trabajar -r github.com/repo.git
        -i direccion a la que se pueden reportar los bugs (en forma de issues de github) -i github.com/repo/issues
        -f url de la homepage del libro -f github.com/repo#readme.md
        -w direccion web de la wiki en github -w github.com/repo.wiki.git
        -h muestra ayuda sobre las opciones disponibles


## Ejemplo


```$npm install gitbook-start-elt```

```$ gitbook-start -dir MiLibro```



## Enlaces interesantes 
 
* [NPM](https://www.npmjs.com/package/gitbook-start-elt)
* [Enlace al Repositorio de la práctica](https://github.com/ULL-ESIT-SYTW-1617/nueva-funcionalidad-para-el-paquete-npm-plugins-ericlucastania-1)
* [Enlace a gitbook-start-plugin-iaas-ull-es](https://github.com/ULL-ESIT-SYTW-1617/gitbook-start-plugin-iaas-ull-es-ericlucastania)
* [Enlace a NPM gitbook-start-plugin-iaas-ull-es](https://www.npmjs.com/package/gitbook-start-plugin-iaas-ull-es-ericlucastania)

## Componentes del grupo de trabajo

* [Eric Ramos](https://github.com/alu0100786330)
* [Lucas Ruiz](https://github.com/alu0100785265)
* [Tania González](https://github.com/tania77)


