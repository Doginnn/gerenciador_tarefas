# GERENCIADOR DE TAREFAS

# [DiTarefas](https://github.com/Doginnn/gerenciador_tarefas)

Sistema Integrado de Gerenciamento de Tarefas baseado em Python, Django e Bootstrap

Projeto independente open-source desenvolvido em Python 3 no Ubuntu/Linux 20.04LTS Focal Fossa, não testado no Windows mas deve rodar sem problemas ;)


## Dependências

- [Python](https://www.python.org/downloads/) - Versão 3.8
- [django](http://www.djangoproject.com) - 3.1

## Instalação:

1. Instalar Virtualenv ([Pypa](https://virtualenv.pypa.io/en/latest/installation.html))

2. Instalar dependências:

    ```bash
    pip install -r requirements.txt
    ```

3. Gere um `.env` local

    ```bash
    python contrib/env_gen.py
    ```


4. Sincronize a base de dados:

    ```bash
    python manage.py migrate
    ```

5. Crie um usuário (Administrador do sistema):

    ```bash
    python manage.py createsuperuser
    ```

6. Teste a instalação carregando o servidor de desenvolvimento (http://localhost:8000 no navegador):

    ```bash
    python manage.py runserver
    ```

## Implementações

- Cadastro de produtos, clientes, empresas, fornecedores e transportadoras
- Login/Logout
- Criação de perfil para cada usuário.
- Definição de permissões para usuários.
- Criação e geração de PDF para orçamentos e pedidos de compra/venda
- Módulo financeiro (Plano de Contas, Fluxo de Caixa e Lançamentos)
- Módulo para controle de estoque
- Módulo fiscal:
    - Geração e armazenamento de notas fiscais
    - Validação do XML de NF-e/NFC-es
    - Emissão, download, consulta e cancelamento de NF-e/NFC-es **(Testar em ambiente de homologação)**
    - Comunicação com SEFAZ (Consulta de cadastro, inutilização de notas, manifestação do destinatário)
- Interface simples e em português

## Créditos

- [AdminBSBMaterialDesign](https://github.com/gurayyarar/AdminBSBMaterialDesign)
- [geraldo](https://github.com/marinho/geraldo)
- [jQuery-Mask-Plugin](https://igorescobar.github.io/jQuery-Mask-Plugin/)
- [DataTables](https://datatables.net/)
- [JQuery multiselect](http://loudev.com/)

## Ajuda

Para relatar bugs ou fazer perguntas utilize o [Issues](https://github.com/thiagopena/djangoSIGE/issues) ou via email thiagopena01@gmail.com

Como este é um projeto em desenvolvimento, qualquer feedback será bem-vindo.
