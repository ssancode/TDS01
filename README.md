# markdown

# título 1
## título 2
### título 3
#### título 4
##### título 5

__negrito__
==marcado==
sublinhado
~~riscado~~
*italico*

Em um paragrafo podemos usar todos os anteriores

## Listas
1. ordenadas
2. quando voce um número, o p
3. próximo item será automaticamente incrementado
    1. subitem
    2. outro subitem
    3. outro subitem
        1. subitem
    
- Não ordenadas
* Voce pode usar um asterisco ou hífen
+ Sinal de mais tambem é aceito
    - subitem
    - subitem
    - subitem
- o correto não é misturar os sinais

## Links
[Clique aqui](https://senac.br/)
[ancora](#markdown)

Este é um paragrafo com link [Clique aqui!](https://senac.br/ "Título para esse link") ou aqui é um parágrafo com um link: https://senac.br/

## Imagens
![Texto alternativo](https://git-scm.com/images/logos/2color-lightbg@2x.png)


### Imagens com link
[![Texto alternativo](https://git-scm.com/images/logos/2color-lightbg@2x.png)](https://google.com)

## Citação

> Iniciar minha citação

> <br>
> Iniciar minha citação
> <br><br>

> Citação
>> sub citação
> ### Título dentro de uma citação


## Toggle
<details>
Clique aqui para ver o conteúdo


## Separador
Pode ser 3 traços

---

ou pode ser 3 asteriscos

***


## Checklist
- [ ] Item 1
- [x] Item 2
- [ ] Item 3


## Tabela

Centralizado a Esquerda
| nome  | idade |
| ----  | ----  |
| Danny |  4    |
| Riel  | 26    |

Centralizado a direita
| nome  | idade |
| ----  | ----:  |
| Danny |  4    |
| Riel  | 26    |

Cemtralizado no centro
| nome  | idade |
| :----:  | :----:  |
| Danny |  4    |
| Riel  | 26    |


## Código
Em linha usamos 1 acento grave para abrir o código e outro para fechar
    <h1> Eu sou um título </h1>

<h1>Eu sou um título</h1>

    ` # Eu sou um título `

# Eu sou um título

    ` console.log('Olá, mundo!')`

## Bloco de código
Usaremos 3 acentos graves para abrir, seguido da linguagem que eu quero, e para fechar mais 3 acentos graves.

``` Html
<details>
    <summary>
        Clique aqui para ver o conteúdo
    <summary>
        Conteúdo
</details>

Python
num1 = int(input("Numero 1: ")) 
num2 = int(input("Número 2: "))
soma = num1 + num2
Print("a soma é {soma}")

```

## Emojis

:cat:
:frog:
:mouse:
:panda: