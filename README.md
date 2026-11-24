# Atividade — Módulo 4: GitHub Actions

## Objetivo

Introdução à automação de tarefas com GitHub Actions.

## Workflow

O arquivo `.github/workflows/dotnet-build.yml` define um workflow acionado por push na branch `main`, executado em Ubuntu, com checkout do repositório e tentativa de execução de `./scripts/custom-script.sh`.

## Pendência de revisão

A pasta de scripts identificada está em `.github/workflows/scripts`, enquanto o comando aponta para `./scripts` na raiz. Recomenda-se verificar o caminho. A execução do workflow não foi testada.

## Material original

# atividade-modulo4
Introdução ao git hub action
