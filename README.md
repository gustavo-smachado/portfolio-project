# Portfolio Project

Site de portfólio pessoal desenvolvido com Django para exibição de trabalhos e projetos (`jobs` app), com suporte a arquivos estáticos e imagens.

## Tecnologias utilizadas

- Python 3
- Django
- SQLite
- HTML / CSS (arquivos estáticos em `static/`)

## Como executar

1. Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/macOS
   # venv\Scripts\activate   # Windows
   ```

2. Instale o Django (e `pillow` caso utilize campos de imagem):
   ```bash
   pip install django pillow
   ```

3. Aplique as migrações e inicie o servidor de desenvolvimento:
   ```bash
   python manage.py migrate
   python manage.py runserver
   ```

4. Acesse `http://127.0.0.1:8000/` no navegador.
