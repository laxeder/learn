# Lógica

Criei esta sessão afim de melhorar minha agilidade em tarefas de raciocínio lógico. Aqui está o resumo de todo o meu conhecimento adquerido sobre:

## Sumário

- [Lógica Formal](#lógica-formal)
  - [Conceitos Primitivos](#conceitos-primitivos)
    - [Valores lógicos](#valores-lógicos)
    - [Preposição](#preposição)
  - [Conectivos lógicos](#conectivos-lógicos)
    - [Símbolos](#símbolos)
    - [Conjunção](#conjunção)
    - [Disjunção](#disjunção)
    - [Condicional](#condicional)
    - [Equivalência](#equivalência)
    - [Negação](#negação)
  - [Fontes](#fontes)

## Lógica Formal

A [Lógica Formal](https://en.wikipedia.org/wiki/Formal_logic) é uma maneira de representar o raciocínio de forma que seja legível universalmente e contudo criando padrões para evitar conflitos de raciocínios.

- Abstraí o conteúdo de um argumento para focar na validação do mesmo.
- Estrutura o pensamento para organização do raciocínio.

### Conceitos Primitivos

São a base da lógica formal pois apartir deles a lógica é construída.

#### Valores lógicos

São representados como **_F_** ou **_0_** (para falso) e **_V_** ou **_1_** (para verdadeiro).

- Para facilitar a compreensão, prefiro pensar como se fosse um **Boolean** (F/V) ou **Byte** (0/1).

#### Preposição

É uma sentença que pode ser verdadeira ou falsa, ou seja, apresenta um fato ou informação sobre um sujeito que pode ser ou não verdadeira.

### Conectivos lógicos

Conecta os valores lógicos com expressões. Permitindo assim haver um raciocínio sobre tais informações.

- Por exemplo: "Se o valor de **A** for falso e o valor de **B** for verdadeiro, então o valor de **C** é falso".

#### Símbolos

| Nome         | Símbolo | Representação | Exemplo                                     |
| ------------ | ------- | ------------- | ------------------------------------------- |
| Cojunção     | **^**   | "e"           | { A=V, B=F } A^B = F , { A=V, B=V } A^B = V |
| Disjunção    | **v**   | "ou"          | { A=F, B=F } AvB = F , { A=V, B=F } AvB = F |
| Condicional  | **→**   | "se, então"   | { A=V, B=F } A→B = F , { A=V, B=V } A→B = V |
| Equivalência | **↔**   | "igualdade"   | { A=F, B=V } A↔B = F , { A=V, B=V } A↔B = V |
| Negação      | **´**   | "negação"     | { A=V } A´ = F , { B=F } A´ = V             |

#### Conjunção

Valida se as sentenças correspondem a um valor verdadeiro.

- Ex: "Se Paulo é bonito e Lucas também é bonito, então ambos são bonitos" (A^B = V).

#### Disjunção

Valida se pelo menos uma das sentenças correspondem a um valor verdadeiro.

- Ex: "Se Paulo não é bonito, mas Lucas é bonito, então há uma pessoa bonita" (AvB = V).

#### Condicional

Representa uma expressão condicional, validando se uma setença implica com a outra.

- Ex: "Se Paulo for bonito, então Lucas não é bonito" (A→B = F).

#### Equivalência

Valida se as sentenças correspondem a um mesmo valor.

- Ex: "Se Lucas é mais bonito que Paulo e Paulo é mais feio que Lucas, então Lucas é mais bonito que Paulo" (A↔B = V).

#### Negação

Valida se a sentença é false.

- Ex: "Se Paulo for bonito, então Lucas não é bonito, alguem está mentindo" ((A→B)´ = V)

## Fontes

- Wikipedia: [Lógica Formal](https://en.wikipedia.org/wiki/Formal_logic) - _03/08/2024_
- Documentos
  - [Lógica Formal](https://pt.slideshare.net/slideshow/01-logica-formal/34077255) - _03/08/2024_
