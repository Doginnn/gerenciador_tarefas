# GERENCIADOR DE TAREFAS

# [DiTarefas](https://github.com/Doginnn/gerenciador_tarefas)

Sistema Integrado de Gerenciamento de Tarefas baseado em Python, Django e Bootstrap

Projeto independente open-source desenvolvido em Python 3 no Ubuntu/Linux 20.04LTS Focal Fossa, não testado no Windows mas deve rodar sem problemas ;)


## Dependências

- [Python](https://www.python.org/downloads/) - Versão 3.8
- [django](http://www.djangoproject.com) - 3.1

## Instalação:

1. Instalar e ativar Virtualenv ([Pypa](https://virtualenv.pypa.io/en/latest/installation.html))

2. Instalar dependências:

    ```bash
    pip install -r requirements.txt
    ```

3. Instalar o MySQL e criar uma nova `"database"` com o nome do projeto, nesse caso `"gerenciador_tarefas".`

4. Sincronize a base de dados:

    ```bash
    python manage.py migrate
    ```

5. Crie um usuário (Administrador do sistema): Nesse caso o meu Usuário ADM é `"teste"` e Senha ADM é `"123Teste!"`, não esqueça de configurar esse usuário e senha lá em `settings.py`>>`DATABASES`.

    ```bash
    python manage.py createsuperuser
    ```

6. Teste a instalação carregando o servidor de desenvolvimento (http://127.0.0.1:8000/ no navegador):

    ```bash
    python manage.py runserver
    ```

## Implementações

- Login/Logout
- Tarefas
    - Criar
    - Alterar
    - Remover
- Interface simples e em português

## Créditos

- [Diógenes Dantas](https://github.com/Doginnn)

## Ajuda

Para relatar bugs ou fazer perguntas utilize o [Issues](https://github.com/Doginnn/gerenciador_tarefas/issues) ou via email diogenesemmanuel@gmail.com

Esse é um projeto em constante desenvolvimento, qualquer ajuda será bem vinda, inclusive Feedbacks.

Esse projeto está licenciado com a licença permitiva MIT. Para mais informações sobre licenças clique [AQUI](http://escolhaumalicenca.com.br/)