# 📚 Biblioteca API

API simples de cadastro de livros, feita com Django e PostgreSQL.

## 🚀 Tecnologias

- Python
- Django
- Django REST Framework
- PostgreSQL

## ⚙️ Instalação

1. Clone o repositório:
```bash
git clone https://github.com/seu_usuario/biblioteca-api.git
cd biblioteca-api
```

2. Crie um ambiente virtual e ative:
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate   # Windows
```

3. Instale as dependências:
```bash
pip install -r requirements.txt
```

4. Configure seu `.env` baseado no arquivo `.env.example`.

5. Rode as migrações e o servidor:
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

## 🧪 Teste a API

Você pode acessar:
```
http://localhost:8000/api/livros/
```

Use ferramentas como Postman ou Insomnia para testar o CRUD.

---
Desenvolvido por [Seu Nome]
