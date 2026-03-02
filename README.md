# CS50 — Hello

Programa desenvolvido como parte do curso **CS50 de Harvard**.

Este projeto solicita o nome do usuário e exibe uma saudação personalizada no terminal.

---

## 📌 Descrição

O programa utiliza a biblioteca do CS50 para capturar a entrada do usuário e imprime uma mensagem de boas-vindas formatada.

Exemplo de execução:

```c
#include <cs50.h>
#include <stdio.h>

int main (void)
{
    string name = get_string ("what's your name ? ") ;
    printf ("hello, %s\n", name) ;
}
```


---

## Conceitos praticados

- Entrada de dados com `get_string`
- Saída formatada com `printf`
- Uso de bibliotecas (`cs50.h` e `stdio.h`)
- Estrutura básica em C
- Compilação e execução no terminal

---

## Tecnologias utilizadas

- Linguagem C  
- CS50 Library  
- GCC (compilador)

---

## Como executar

No terminal do CS50:

```bash
make hello
./hello
```
<img width="305" height="82" alt="image" src="https://github.com/user-attachments/assets/2296c31a-ac3f-453e-a0d2-e020223e4afd" />
