# Prisma Client Python Example

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/RobertCraigie/prisma-py-async-quickstart)

This repository showcases the minimum steps required to get started using [Prisma Client Python](https://github.com/RobertCraigie/prisma-client-py).


## Usage

For a more detailed explanation see the Prisma Client Python [documentation](https://github.com/RobertCraigie/prisma-client-py/blob/main/docs/quickstart.md).

```sh
python3 -m venv .venv
source .venv/bin/activate
pip install -U -r requirements.txt
prisma db push
```

You can now run the python script
```sh
python main.py
```
And type check it with pyright
```sh
pyright
```
