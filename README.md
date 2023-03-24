# atividadeintro
 Uma atividade introdutória para treinar algumas ferramentas do Python

## Então você precisa entender Python

Python é uma linguagem que nos permite muita liberdade. Ela pode ser utilizada para pequenos scripts de automação de tarefas. Ou pode ser utilizada para criar poderosos serviços de backend. Também é possível trabalhar com inteligência artificial e mineração de dados.

Algo interessante é que esta linguagem foi desenvolvida pensando na facilidade de aprendizado.

## Qualidade de código é importante

Para a atividade de hoje precisamos trabalhar o conceito de qualidade de código. O grande diferencial entre um desenvolvedor inexperiente e um que tem história na carreira é o quanto se empenha para manter a qualidade do código.

Neste quesito, como auxílio, muitos de nós seguimos certas convenções que dependem da linguagem em que trabalhamos.

A comunidade Python sugere utilizar um estilo de programação que ficou registrado no documento PEP-8.

Neste documento encontramos uma série de regras de boa convivência entre programadores. É interessante que você se aproprie destas recomendações.

Mas existem ferramentas que nos forçam a seguir estas e outras boas práticas de programação. Elas são conhecidas como linters. Uma ferramenta de lint analisa nossos códigos, verifica o que se adequa a configurações definidas pelos gerentes ou pela equipe de um projeto, verifica se há código duplicado, se nomes de variáveis, funções, classes e métodos estão adequados, e dá uma nota para isso.

Elas também podem verificar se há comentários documentando o código. Veja um exemplo abaixo, imaginando que é o conteúdo do arquivo exemplo.py:

```python
""" Exemplo.py é um módulo que faz mágica.

    O objetivo deste módulo é fornecer coisas mágicas, como um coelho numa cartola ou um baralho com todas as cartas iguais.
"""
import os


def func():
    """ Esta função faz algo legal.
    
        Imagine que ela faz mesmo. Mas ela só retorna o diretório atual onde o programa está executando.
    """
    return os.getcwd()

```

Note que todo o código está com comentários significativos. O primeiro comentário é a documentação do módulo (ou arquivo python). O segundo é a documentação da função func. Além disso a formatação apresentada respeita os preceitos da PEP-8.

## Qual a tarefa?

- Ler sobre a PEP-8 para entender as regras de formatação. Você pode encontrar ela em português [aqui](https://dev.to/immurderer/guia-de-estilo-python-pep-8-lm8)
- No arquivo atividadeintro/app.py você deve adicionar comentários de documentação e implementar o que é pedido abaixo seguindo as recomendações da PEP-8.
- Você deve implementar uma função que receba dois valores numéricos e retorne como resposta o maior dentre eles.

## Quais os requisitos?

Já há uma ferramenta presente que irá dar uma nota para a qualidade do seu código (um linter). Esta é a ferramenta mais utilizada para fazer este tipo de avaliação no Python, o Pylint.

Seu objetivo é que ela dê uma nota acima de 7 para o seu código.
