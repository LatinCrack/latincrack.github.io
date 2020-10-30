---
layout: post
title: Página personal de Code de LatinCrack!
---

Primer artículo de bienvenida

## Sección 1
``` Assembler
    org  0x100        
    ; int 21h is going to want...

    mov  dx, msg      
    mov  ah, 9        
    int  0x21         

    mov  ah, 0x4c     
    int  0x21         

    msg  db 'Hello, GitHub!', 0x0d, 0x0a, '$'
```
