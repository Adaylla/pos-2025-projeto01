# Projeto da Unidade 02 de POS

## Aluna
- Adaylla Alannis

## Instalação

Siga os seguintes passos para rodar o projeto localmente.

- Crie um ambiente virtual

```bash
python -m venv .venv
```

- Ative o ambiente virtual

*powershell*
```powershell
.venv/Scripts/activate
```

- Instale as dependências do projeto

```bash
pip install -r requirements.txt
```

- Crie um arquivo `.env` e adicione as informações da API do SUAP

```
SECRET_KEY='development'
CLIENT_ID= <seu client id>
CLIENT_SECRET= <seu client secret>
```

- Rode o servidor

```bash
flask run
```

---