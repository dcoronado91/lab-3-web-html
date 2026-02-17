# El Forastero de Dust Creek
Laboratorio 3 - Sistemas y Tecnologias Web - CC3062

**Nombre:** Derek Friedhelm Coronado Chilin

**Carnet:** 24732

**Sección:** 10

---

## 📖 Descripción

Año 1881.  
Llegas al pequeño y polvoriento pueblo de Dust Creek.  
Tu pasado te persigue y cada decisión puede llevarte a la redención… o a la muerte.

El lector puede:
- Entrar al saloon y enfrentar un duelo
- Alejarse hacia el cañón
- Descubrir un campamento oculto
- Encontrar distintos finales

La historia no es lineal y contiene loops que permiten regresar a escenas anteriores.

---

## 🛠 Tecnologías utilizadas

- HTML5
- Navegación con rutas relativas
- Carga de imágenes con rutas absolutas

---

## 📁 Estructura del proyecto
```text
lab_3/
│
├── index.html
│
├── town/
│   ├── saloon.html
│   └── duel.html
│
├── desert/
│   ├── canyon.html
│   └── camp.html
│
└── images/
    ├── cowboy.jpg
    ├── saloon.jpg
    ├── duel.jpg
    ├── canyon.jpg
    └── camp.jpg
```

- `index.html` es la página principal.
- Las escenas están distribuidas en carpetas.
- Todas las imágenes se encuentran en la carpeta `images`.
- Las imágenes se cargan utilizando rutas absolutas.
- La navegación entre escenas usa rutas relativas.

--# lab-3-web-html
