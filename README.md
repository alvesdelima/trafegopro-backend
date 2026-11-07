# TráfegoPro · Backend

API em **FastAPI** que será a base do TráfegoPro, uma ferramenta de gestão de tráfego pago.

> 🚧 **Em desenvolvimento.** Por enquanto, só a estrutura inicial da API e da camada de banco de dados.

## Stack

- Python 3.11
- FastAPI + Uvicorn
- SQLAlchemy 2
- Pydantic 2

## Como rodar

```bash
python -m venv venv
venv\Scripts\activate        # Windows
# source venv/bin/activate   # Linux/macOS
pip install -r requirements.txt
uvicorn main:app --reload
```

A API sobe em `http://localhost:8000`, e a documentação interativa fica em `http://localhost:8000/docs`.

## Estrutura

```
app/
├── core/       # configurações
├── models/     # modelos do banco
├── routes/     # rotas da API
└── database.py # conexão com o banco
main.py         # ponto de entrada
```
