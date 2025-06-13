# Modulo 3: Herramientas de búsqueda de Perfiles

Conjunto de herramientas para la busqueda de nicks en diversas paginas web y redes sociales.

## Vídeos

### Módulo 3.1: Sherlock

[![Módulo 3.1: Sherlock](https://img.youtube.com/vi/7DliXgvP034/0.jpg)](https://www.youtube.com/watch?v=7DliXgvP034)

### Módulo 3.2: WhatsMyName

[![Módulo 3.2: WhatsMyName](https://img.youtube.com/vi/sFiCj6X1gSw/0.jpg)](https://www.youtube.com/watch?v=sFiCj6X1gSw)

### Módulo 3.3: Profil3r

[![Módulo 3.2: Profil3r](https://img.youtube.com/vi/3M1mjn1iOog/0.jpg)](https://www.youtube.com/watch?v=3M1mjn1iOog)

### Módulo 3.4: Nexfil

[![Módulo 3.2: Nexfil](https://img.youtube.com/vi/QLSVaeVIQd4/0.jpg)](https://www.youtube.com/watch?v=QLSVaeVIQd4)

### Módulo 3.5: EagleEye

[![Módulo 3.5: EagleEye](https://img.youtube.com/vi/dVd13tTwC1s/0.jpg)](https://www.youtube.com/watch?v=dVd13tTwC1s)

## Recursos

- Sherlock: [https://github.com/sherlock-project/sherlock](https://github.com/sherlock-project/sherlock)
- Whatsmyname: [https://github.com/webbreacher/whatsmyname](https://github.com/webbreacher/whatsmyname)
	- Web: [https://whatsmyname.app](https://whatsmyname.app)
- Profil3r: [https://github.com/Greyjedix/Profil3r](https://github.com/Greyjedix/Profil3r)
- Nexfil: [https://github.com/thewhiteh4t/nexfil](https://github.com/thewhiteh4t/nexfil)

**Nota**: el proyecto de `whatsmyname` ya no tiene herramienta publica, pero podeis encontrar una en mi repositorio.

### WhatMyName by BashBunny

En el repositorio [https://github.com/bash-bunny/WhatsMyName](https://github.com/bash-bunny/WhatsMyName) podeis encontrar una version propia de la herramienta.

Como se indica en el repositorio hace uso del fichero `wmn-data.json` que es propio de WebBreacher, y conviene actualizarlo a menudo.

#### Instalación

```bash
git clone https://github.com/bash-bunny/WhatsMyName.git
cd WhatsMyName
python -m venv venv
. venv/bin/activate
pip install -r requirements.txt
```

#### Uso

Basta con pasarle el nick que se esta buscando por parametro.

```bash
python whatsmyname.py username
```
