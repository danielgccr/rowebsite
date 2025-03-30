+++
title = 'Genésis'
date = 2025-01-15T09:00:00-07:00
draft = false
tags = ['hugo']
description = '¿Cómo nació esta página web?'
+++

¿Cómo nació esta página?

```bash
hugo new site robledo && cd $_
hugo new theme aesthetics
echo 'theme = "aesthetics"' >> hugo.toml
git init
hugo server
```

¡Y hala! Un sitio en funcionamiento mientras, por otro lado, iba editando el tema que generé en Zed. Cuando me di por satisfecho con esto, lo subí a Git y ahí, en Github Actions, me monté un autómata para subirlo a Neocities cada vez que escribiese algo y sincronizase esta página con mi repositorio remoto. ¿Cómo?
