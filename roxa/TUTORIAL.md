# Tutorial: Passo a passo do que foi feito

Este tutorial descreve passo a passo todas as ações realizadas para organizar, commitar e enviar os exercícios de Python.

## Estrutura do tutorial (pasta `roxa`)
- `TUTORIAL.md` — este arquivo (explicações e comandos)
- `index.html` — página simples com fundo roxo para destacar que é um tutorial

---

## Passos realizados (comandos)

1) Criar a pasta do repositório local:

```powershell
mkdir "C:\Users\viviane.norberto\Desktop\Passo-a-passo-tutorial"
cd "C:\Users\viviane.norberto\Desktop\Passo-a-passo-tutorial"
```

2) Inicializar um repositório Git local:

```powershell
git init
```

3) Adicionar arquivos e fazer o primeiro commit (versão inicial do tutorial):

```powershell
git add roxa/TUTORIAL.md README.md
git commit -m "Tutorial: adicionar TUTORIAL e README (v1)"
```

4) Adicionar página HTML demonstrativa (pasta `roxa`) e commitar como evolução:

```powershell
git add roxa/index.html
git commit -m "Tutorial: adicionar index.html com tema roxo (v2)"
```

5) Adicionar repositório remoto e enviar:

```powershell
git remote add origin https://github.com/Vivi-cyb/Passo-a-passo-tutorial-.git
git push -u origin master
```

> Observação: substitua a URL pelo remoto correto se necessário.

---

## O que cada commit representa
- Commit 1: versão inicial do tutorial (explicação em `TUTORIAL.md`)
- Commit 2: arquivos visuais e de apoio (página `index.html` com fundo roxo)

---

## Como visualizar a página roxa localmente
Abra `roxa/index.html` no navegador.

---

## Fim
Se quiser que eu converta este `TUTORIAL.md` em PDF ou que eu crie um release no GitHub com o ZIP, me avise.
