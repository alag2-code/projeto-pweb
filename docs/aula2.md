# Configurar github conectando ao nosso projeto local

## 1. Criar conta e novo repositório no github 
Uma vez que o repositório foi criado, ele sugere os seguintes comandos:
```sh
git remote add origin https://github.com/alag2-code/projeto-pweb.git
git branch -M main
git push -u origin main
```

Dando tudo certo, o seu repositório na nuvem (github) vai ter seus aqruivos atualizados 

## E dando errado
### Problema 1 - Repositórios com trabalhos desalinhados
Há trabalhos/arquivos/modificações/ no repositório remoto e não estão localmente.

Para trazer o trabalho do remoto, execute:
```sh
git pull origin main
```

Ainda assim, pode haver erros **FATAIS**. Que podem ser devido a um
desalinhamento das branchs. Elevai acusar que as branchss estão desalinhadas