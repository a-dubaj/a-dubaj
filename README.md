### Hi there 👋
# Define Design Develop Automate

* Full Stack Engineer
* Rev Engineering
* DevOps
* InfoSec
* Get me to do it for you ;)

![](https://komarev.com/ghpvc/?username=coffeina&color=ee959e) <a href="https://www.handsonprogramming.io" target="_blank"><img alt="Website" src="https://img.shields.io/badge/Website-www.handsonprogramming.io-blue?style=flat&logo=google-chrome"></a> <a href="https://www.linkedin.com/in/andrzejdubaj/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Andrzej%20Dubaj-blue?style=flat-square&logo=linkedin"></a> [![Twitter Badge](https://img.shields.io/badge/-AndrzejDubaj-1ca0f1?style=flat&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/)](https://twitter.com/AndrzejDubaj)

``` asm
section .rodata
    msg:    db 'hello, world', 10
    msglen: equ $-msg

section .text
    main:
        ; write(1, msg, msglen)
        mov rdi, 1
        mov rsi, msg
        mov rdx, msglen
        mov rax, 1
        syscall
```
