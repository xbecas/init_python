# Python Turtle - uma aventura de programação!

Este guião pretende ajudar a começar a programar em Python 3 - uma linguagem de programação que te permite criar os teus próprios programas no computador. Os passos que se seguem são uma aventura que permitir-te-ão compreender os conceitos básicos de programação enquanto fazes desenhos e jogos fantásticos baseado num módulo chamado `turtle`! Irás, também, aprender a estruturar o pensamento para mais tarde desenvolveres programas e jogos ainda mais espetaculares!

A aventura começa agora!

## Como começar

Para começarmos a programar em Python 3 é necessário termos o interpretador de Python no nosso computador e um editor de texto. Recomendamos o Editor Mu por ser simples de utilizar e trazer uma instalação de Python, simplificando o início desta aventura!

```mermaid
  graph TD
  
    subgraph "PYTHON - INSTALAÇÃO"
      %% Python - como começar
      Instalar("INSTALAR PYTHON<br>-----------------------<br>https://www.python.org<br>https://codewith.mu")
      Ambiente("AMBIENTE<br>--------------<br>REPL<br>Editor de texto vs IDE")
      Mu("EDITOR MU (IDE)<br>---------------------<br>Vem com uma instalação de Python<br>Editor simples e fácil de usar")
      Instalar-->Mu
      Ambiente-->Mu
    end
```

```mermaid
  graph TD
  
    subgraph "PYTHON - CONCEITOS BÁSICOS"
      Fundamental("FUNDAMENTAL SABER<br>--------------------------<br>Iniciar o Mu ou o Python<br>Utilizar o teclado<br>Ler e gravar ficheiros")
      Importante("IMPORTANTE SABER<br>-----------------------<br>Copiar e colar texto<br>Escrever comentários e docstrings"<br>'Formatar' o código)
      Erros("APRENDER COM OS ERROS<br>--------------------------------<br>Identificar a linha do erro<br>Interpretar e corrigir erros<br>'Verificar' se há erros no código")
    end
```

## Python turtle - parte 1

O Python conhece uma tartaruga que nos vai ensinar a programar, enquanto desenha no ecrã! Queres conhecê-la?

```mermaid
  graph TD

    subgraph "PYTHON TURTLE - PARTE 1"

      subgraph "Para começar"
        %% Python turtle
        Comecar("COMEÇAR<br>------------<br>Iniciar Mu<br>Modo Python 3")
        PrimeiroPrograma("PRIMEIRO PROGRAMA<br>--------------------------<br>import turtle<br><br>turtle.forward(100)")
        Comecar-->PrimeiroPrograma
      end

      subgraph "Movimentos básicos"
        %% Movimentos básicos
        MovimentoBasico("MOVIMENTOS BÁSICOS<br>---------------------------<br>fd, bk, lt, rt<br>Espaço cartesiano x-y<br>Rotação com ângulos 0-360°")
        Viajar("VIAJAR<br>--------<br>up, down<br>goto, setpos<br>setx, sety<br>home")
        MovimentoBasico-->Viajar
      end
      
    end
``` 

## Python turtle - truque e dicas

Vamos conhecer alguns truques para ser mais fácil e mais giro programar!

```mermaid
  graph TD
  
    subgraph "PYTHON TURTLE - TRUQUES E DICAS"
      %% Truques para conforto e eficiência
      ScreenSetup("CONFIGURAÇÃO DA JANELA GRÁFICA<br>--------------------------------------------<br>Screen().setup")
      Velocidade("VELOCIDADE<br>--------------<br>speed")
      Limpar("LIMPAR<br>----------<br>clear, reset")
      Undo("DESFAZER<br>------------<br>undo")
    end
```

## Python turtle - parte 2

Agora que já sabemos como fazer desenhos simples vamos aprender a fazer desenhos mais completos... e a cores!

```mermaid
  graph TD

    subgraph "PYTHON TURTLE - PARTE 2"

      subgraph "Movimentos circulares"
        %% Movimentos circulares
        MovimentoCircular("MOVIMENTOS CIRCULARES<br>--------------------------------<br>circle(r)<br>circle(r, e)")
        PoligonosRegulares("POLÍGONOS REGULARES<br>-----------------------------<br>circle(r, e, s)")
        MovimentoCircular-->PoligonosRegulares
      end

      subgraph "Estilização"
        %% Estilização - cores e espessuras
        Estilizar("ESTILIZAR<br>-------------<br>penwidth<br>pencolor('color')<br>pencolor(r, g, b - 0.0..1.0)<br>pencolor(r, g, b - 0..255)")
        Fundo("COR/IMAGEM DE FUNDO<br>-----------------------------<br>Screen().bgcolor<br>Screen().bgpic")
        Formas("FORMAS<br>---------<br>shape<br>shapesize<br>register_shape")
        Estampas("ESTAMPAS/CARIMBOS<br>--------------------------<br>dot<br>stamp<br>undostamp")
        Estilizar-->Fundo
        Formas-->Estampas
      end
  end
```
