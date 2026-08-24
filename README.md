# 🤖 Automação de Cadastro de Produtos com Python

Automação desenvolvida em Python para **cadastrar produtos automaticamente em um sistema web a partir de uma planilha Excel**, eliminando grande parte do trabalho manual de preenchimento.

## 🚀 Como funciona

O programa:

1. Abre o Google Chrome automaticamente.
2. Acessa o sistema de cadastro.
3. Realiza o login.
4. Lê os produtos da planilha `20produtos.xlsx`.
5. Percorre os dados de cada produto.
6. Preenche os campos do sistema automaticamente.
7. Envia o cadastro de cada produto.
8. Ao final, informa que a tabela foi concluída.

### 🔄 Fluxo

```text
Planilha Excel
      ↓
    Pandas
      ↓
Leitura dos produtos
      ↓
   PyAutoGUI
      ↓
Preenchimento automático
      ↓
Sistema Web
      ↓
Produtos cadastrados
```

## 🛠️ Tecnologias utilizadas

* **Python**
* **Pandas** — leitura e manipulação da planilha Excel
* **PyAutoGUI** — automação do mouse e teclado
* **Pyperclip** — cópia e colagem de valores
* **Time** — controle dos intervalos da automação

## 📁 Estrutura do projeto

```text
Automacao_Cadastro_Produtos_Python/
│
├── AutomacaoPyautogui.py
├── 20produtos.xlsx
└── README.md
```

## ⚙️ Instalação

Clone o repositório:

```bash
git clone https://github.com/ruanpac/Automacao_Cadastro_Produtos_Python.git
```

Instale as bibliotecas necessárias:

```bash
pip install pyautogui pandas pyperclip openpyxl
```

Depois, execute:

```bash
python AutomacaoPyautogui.py
```

## 📊 Exemplo da planilha

A automação utiliza uma planilha Excel contendo os dados dos produtos que serão cadastrados.

| Produto   | Marca   | Tipo   | Categoria   | Preço Unitário | Custo | OBS          |
| --------- | ------- | ------ | ----------- | -------------: | ----: | ------------ |
| Produto 1 | Marca A | Tipo A | Categoria A |            100 |    70 | N/A          |
| Produto 2 | Marca B | Tipo B | Categoria B |            150 |    90 | Produto novo |

## 🎯 Objetivo

O projeto foi desenvolvido para praticar **Python, automação de processos (RPA), manipulação de dados e interação com sistemas web**, simulando uma tarefa que poderia ser automatizada em um ambiente empresarial.

## ⚠️ Observação

Este projeto utiliza automação baseada em posições, teclas e cliques na interface. Por isso, alterações no layout do sistema ou na resolução da tela podem exigir ajustes no código.

**Projeto desenvolvido para fins de estudo e portfólio.**
