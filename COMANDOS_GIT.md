# Comandos Git

Use estes comandos dentro da pasta do projeto:

```bash
git add .
git commit -m "Adiciona simulado com 25 questões de Português e 25 de Informática"
git push
```

Se os arquivos estiverem dentro de uma pasta no repositório, mova para a raiz:

```bash
shopt -s dotglob
mv nome-da-pasta/* .
rm -rf nome-da-pasta
git add .
git commit -m "Move arquivos para a raiz"
git push
```
