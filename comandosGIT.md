# Comandos GIT

### Iniciar um novo repositorio git local vazio
```bash
git init
```

---

### Linkar o repositorio local criado anteriormente com o repositorio remoto do github. 'Origin' -> nome dado ao repositorio
```bash
git remote add origin 'link do repositorio no github'
```

---

### Mandar o arquivo especificado para o staging do repositorio
```bash
git add nomearquivo.extensao
```

---
### Mandar todos os arquivos disposniveis para serem enviados para o staging
```bash
git add .
```

---

### Mostrar os status atual do repositorio, por exemplo, se ha arquivos a serem commitados
```bash
git status
```

---

### commita os arquivos presentes no staging no repositorio
```bash
git commit -m "mensagem do commit"
```

---

### Renomeiar a branch (usualmente se altera o nome da branch "master" para "main")
```bash
git branch -M nome
```

--- 

### Adicionar os arquivos do repositorio local no repositorio do github (primeira vez)
```bash
git push -u origin main
```

---

### Adicionar/atualizar os arquivos no repositorio do github (a partir da segunda vez)
```bash
git push origin main
```

---

### Criar uma nova branch para novas alteracoes (criar antes de realizar as modificações). Pode ser utilizado para alternar entre as branches
```bash
git checkout -b nomedabranch
```

---

### Juntar as branches em uma só. Dar checkout na branch que deseja adicionar as alteracoes.
```bash
git merge nome_branch
```

---

### Clonar o projeto presente no github para a maquina em que esta
```bash
git clone link.git
```

---

### Puxar as alterações realizadas no repositorio do github por outra máquina
```bash
git pull
```
