---
speaker:
  name: "Stefano Borzì"
date: 2020-05-08T10:00:00
title: Storia dei sistemi operativi
linkcollegamento: ""
weight: 10
logo: "/img/tux.svg"
---

Chi ha creato il primo Personal Computer? Come sono nati e qual è la storia dei sistemi operativi moderni?
Questa presentazione cercherà di rispondere a queste domande illustrando le buone e/o cattive politiche adottate dalle aziende multinazionali che si sono affermate creando i sistema operativi oggi conosciuti come, Windows, Mac OS e Linux.

```c
#define MODULE
#define LINUX
#define __KERNEL__

#include <linux/module.h>
#include <linux/kernel.h>


int init_module(void){
   printk("<1>Speaker: Stefano Borzì\n");
}
```

[Link al collegamento](https://github.com/gohugoio/hugo/)