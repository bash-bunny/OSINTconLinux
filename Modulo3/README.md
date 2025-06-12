# Modulo 3: Herramientas de búsqueda de Perfiles

Conjunto de herramientas para buscar perfiles online, sin necesidad de API, solo a traves de la terminal.

## Recursos

- Sherlock: https://github.com/sherlock-project/sherlock
- Whatsmyname: https://github.com/webbreacher/whatsmyname
	- Web: https://whatsmyname.app
- Profil3r: https://github.com/Greyjedix/Profil3r
- Nexfil: https://github.com/thewhiteh4t/nexfil

**Nota**: el proyecto de `whatsmyname` ya no tiene herramienta publica, pero podeis encontrar una en mi repositorio.

### WhatMyName by BashBunny

En el repositorio https://github.com/bash-bunny/WhatsMyName podeis encontrar una version propia de la herramienta.

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
