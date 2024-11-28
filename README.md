# ft_printf

## 📜 Descrição

O projeto **ft_printf** consiste em recriar a função `printf` da biblioteca padrão do C. Este é um desafio que testa sua capacidade de manipular strings, números e argumentos variáveis em C.

## 🚀 Objetivo

Implementar a função `ft_printf` com suporte para os seguintes especificadores:
- `%c`: Caracteres.
- `%s`: Strings.
- `%d`/`%i`: Inteiros com sinal.
- `%u`: Inteiros sem sinal.
- `%x`/`%X`: Hexadecimal (minúsculo/maiúsculo).
- `%%`: O caractere `%`.

## 📂 Estrutura do Projeto

- **ft_printf.c**: Implementação principal da função `ft_printf`.
- **ft_printf_utils.c**: Funções auxiliares para manipulação de strings e números.
- **Makefile**: Automação da compilação do projeto.

## 🛠️ Execução

Para compilar o projeto:
```bash
make
```
A biblioteca libftprintf.a será gerada e poderá ser utilizada para substituir o printf padrão. Exemplo de uso:
```
#include "ft_printf.h"

int main(void)
{
    ft_printf("Olá, %s! Você tem %d anos.\n", "João", 25);
    return 0;
}
```
## 📖 Conceitos Envolvidos

- Manipulação de argumentos variáveis com stdarg.h.
- Conversão e formatação de números e strings.
- Gerenciamento de buffers para saída formatada.
