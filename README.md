# SelfBot Discord V1

## Descrição

Bot desenvolvido em Python utilizando a biblioteca `discord.py` para monitorar a presença de membros em um servidor Discord.

## Funcionalidades

* Identificação de membros online.
* Coleta de estatísticas de presença.
* Exportação de IDs para análise administrativa.
* Registro de atividades em arquivos de log.
* Interface simples via terminal.

## Requisitos

* Python 3.10+
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

O sistema exibirá informações sobre os membros atualmente online e poderá gerar relatórios para administradores autorizados.

## Aviso

Este projeto deve ser utilizado apenas em servidores nos quais você possui autorização para coletar e analisar informações dos membros. Respeite os Termos de Serviço do Discord e a privacidade dos usuários.

## Licença

Projeto destinado para fins educacionais e administrativos.

