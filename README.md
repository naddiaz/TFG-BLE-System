# TFG-BLE-System

## Jerarquía de repositorios.
```bash
.
├── App-System
│   ├── Employee-Module
│   └── Manager-Module
└── Server-Module

```

## App-System
Este va a ser el contenedor que disponga de las dos partes de la APP, los empleados y los directores.

### Employee-Module
[Repositorio](http://github.com/naddiaz/App-Employee-Module)

Un empleado tendrá opciones limitadas, más bien unas opciones totalmente diferentes, por lo que se conectará al servidor y consumirá una serie de datos específicos.

### Employee-Module
[Repositorio](http://github.com/naddiaz/App-Manager-Module)

Un Director tendrá un conjunto de operaciones amplias para el control de usuarios, se conectará al servidor buscando datos diferentes al otro rol.

## Server-Module
[Repositorio](http://github.com/naddiaz/Server-Module)

En el servidor es donde se realizarán las operaciones de localización y la gestión de los datos.
