# Python Turtle · Mini-curso de 10 horas · Parte 1

## Ambiente de desenvolvimento

Objetivos:
- [X] Garantir o bom funcionamento do Mu
- [X] Testar o modo Python 3
- [X] Ler e gravar ficheiros
- [X] Correr o primeiro programa com o Python Turtle!

```mermaid
graph LR

  subgraph "INSTALAR MU / PYTHON"
    InstalarMu("Instalar Mu<br>(inclui Python)")
  end

  subgraph "TESTAR REPL NO MU"
    TestarREPL("Testar REPL<br>Cálculos algébricos<br>`import turtle`<br>turtle.forward(100)")
  end

  subgraph "EDITOR MU"
    TestarMu("Modo Python 3<br>Instruções sequenciais<br>Ler e gravar ficheiros")
  end

  subgraph "TESTAR O PYTHON TURTLE"
    DesenharUmaLinha("import turtle<br><br>turtle.forward(100)")
  end

  InstalarMu-->TestarREPL-->TestarMu-->DesenharUmaLinha

```

## Diversos mini-programas

Objetivos:
- [X] Explorar o conceito de programa, com instruções sequenciais
- [X] Analisar mensagens de erros e como ultrapassar os erros
- [X] Explorar o sistema de coordenadas cartesiano x-y e a rotação em graus
- [X] Fazer desenhos de linhas no ecrã com os métodos `forward`/`fd`, `backward`/`bk`, `left`/`lf` e `right`/`rt`
- [X] Posicionar o cursos em diferentes locais do ecrã com os métodos `penup`/`up` e `pendown`/`down`

```mermaid
graph LR
    
  subgraph "UM QUADRADO"
    UmQuadrado("Um quadrado de<br>tamanho 100")
  end

  subgraph "QUADRADO IGUAIS"
    DoisQuadradosIguais("Dois quadrado de<br>tamanho 100,<br>rodados 180˚")
  end

  subgraph "QUADRADOS DIFERENTES"
    DoisQuadradosDiferentes("Dois quadrado de<br>tamanho 100<br> e tamanho 150")
  end

  subgraph "QUADRADOS AFASTADOS"
    DoisQuadradosAfastados("Dois quadrado de<br>tamanho igual ou<br>diferente, afastado<br>entre si")
  end

  UmQuadrado-->DoisQuadradosIguais-->DoisQuadradosDiferentes-->DoisQuadradosAfastados

```

## Missão 1: desenhar uma figura para um novo cursor

Objetivos:
- [X] Tornar o Python Turtle mais apelativo com um cursor personalizado
- [X] Introduzir o conceito de geometria (polígono) fechado
- [X] Mostrar as formas existentes para o cursor com os métodos `shape` e `shapesize`
- [X] Alterar a forma do cursor com os métodos `register_shape`/`addshape`

```mermaid
graph LR

  subgraph "Requisitos Python"
    Coordenadas("Números(int, float)<br>Coordenadas 2D<br>Listas e tuplos")
  end

  subgraph "Requisitos gerais"
    EspacoCartesiano("Espaço Cartesiano")
  end

  subgraph "Requisitos Turtle"
    GoTo("turtle.goto()")
  end

  subgraph "Objetivo"
    RegistarForma("turtle.register_shape()")
  end

  click RegistarForma "https://docs.python.org/3/library/turtle.html#turtle.register_shape"

  subgraph "Trabalho voluntário / TPC"
    DesenharForma("Desenhar uma nova<br>forma para o nosso cursor")
  end

  Coordenadas--> GoTo
  EspacoCartesiano-->GoTo
  GoTo-->RegistarForma-->DesenharForma
  
```

Diverte-te!
