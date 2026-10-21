<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=175&color=0:0F172A,55:164E63,100:0891B2&text=Restaurantes%20e%20Card%C3%A1pio&fontColor=FFFFFF&fontSize=34&fontAlignY=38&desc=Orienta%C3%A7%C3%A3o%20a%20objetos%20em%20Python&descAlignY=61&descSize=15" alt="Capa do projeto Restaurantes e Cardápio" width="100%" />

![Tecnologia](https://img.shields.io/badge/Python-0F172A?style=flat-square) ![Idioma](https://img.shields.io/badge/documentação-pt--BR-0891B2?style=flat-square) ![Tipo](https://img.shields.io/badge/projeto-de%20estudo-334155?style=flat-square)

</div>

# Sistema de Restaurante e Cardápio 🍽️

Projeto de console desenvolvido durante os estudos de **Programação Orientada a Objetos com Python**. A aplicação monta um restaurante de exemplo e exibe um cardápio com pratos, bebidas e sobremesas.

## O que o projeto demonstra

- Cadastro de restaurantes em memória;
- Ativação e desativação de restaurantes;
- Registro de avaliações e cálculo da média;
- Organização de itens de cardápio em uma classe base;
- Especialização de pratos, bebidas e sobremesas;
- Aplicação de descontos por tipo de item;
- Exibição dos itens do cardápio no terminal.

O arquivo `app.py` cria um restaurante de exemplo, adiciona três itens ao cardápio e chama a exibição. Os dados são de demonstração e não são gravados em banco de dados.

## Conceitos praticados

- Classes, objetos e encapsulamento;
- Herança e polimorfismo;
- Classes abstratas com `ABC`;
- Propriedades e métodos de classe;
- Módulos e pacotes Python.

## Tecnologias

- Python 3.12 ou superior;
- Biblioteca padrão do Python — não há dependências externas.

> A versão 3.12 ou superior é necessária por causa da sintaxe de f-string usada no código.

## Como executar

1. Clone o repositório e acesse a pasta:

   ```bash
   git clone https://github.com/elitohn/Sistema-de-Restaurante-e-Cardapio-Python.git
   cd Sistema-de-Restaurante-e-Cardapio-Python
   ```

2. Confira a versão do Python:

   ```bash
   python --version
   ```

3. Execute o exemplo:

   ```bash
   python app.py
   ```

No Windows, se o comando `python` não estiver configurado, use `py app.py`.

A saída mostra o cardápio de exemplo no terminal. Não é necessário instalar pacotes com `pip`.

## Estrutura do projeto

```text
.
├── app.py
└── modelos/
    ├── avaliacao.py
    ├── restaurante.py
    └── cardapio/
        ├── item_cardapio.py
        ├── bebida.py
        ├── prato.py
        └── sobremesa.py
```

- `app.py`: cria os dados de demonstração e inicia a exibição;
- `modelos/restaurante.py`: representa restaurantes, avaliações e cardápios;
- `modelos/avaliacao.py`: representa uma avaliação;
- `modelos/cardapio/`: reúne a classe base e os tipos de item do cardápio.

## Contexto

Projeto educacional desenvolvido durante cursos de Python da Alura, com foco em orientação a objetos. O repositório demonstra regras e modelos em memória; não é um sistema comercial, não possui interface web e não persiste dados.

Desenvolvido por **Wellyton Huan**.
