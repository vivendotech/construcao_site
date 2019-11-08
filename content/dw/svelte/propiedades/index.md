---
title: "Como passar propiedades"
date: 2019-11-06T21:43:24-03:00
draft: false
vivencia: "svelte"
descricao: "123123"
tempo: "10 min"
---

# Como passar propiedades

Passando propiedades para os componentes. Precisa expor que a variavel é na verdade uma propiedade. Para isso use a linha abaixo:
```
export let propiedade = "oi";
```

Sendo assim é possivel acessar essas propiedes a partir da prototipação do componente:
```
<Componente string={ "hallo123"}/>
```

# É possivel passar funções ?

