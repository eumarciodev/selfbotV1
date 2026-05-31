# SelfBot Discord V1

## Descrição

Bot desenvolvido em Python utilizando a biblioteca `discord.py` para coletar o ID de todos os usuários online e enviar mensagens para todos eles.

## Funcionalidades

* Coletar o ID de todos os membros online.
* Enviar mensagens para todos os IDs presentes no arquivo `online_ids.txt`.

## Requisitos

* Python 3.10 ou superior
* discord.py
* python-dotenv

## Instalação

```bash
pip install discord.py python-dotenv
```

Crie um arquivo `.env`:

```env
TOKEN=SEU_TOKEN_AQUI
```

## Uso

Execute o bot:

```bash
python main.py
```
