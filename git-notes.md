## GIT

### Criação de branch

```bash
git checkout -b exercicio-1
```

### Pegar arquivo da nuvem

```bash
git pull
```

### Trocar de branch

Ir para main no exemplo

```bash
git checkout main
```

### Merge de branches

Deixa o histórico de commits da branch a ser mergeada.

```bash
git merge branch-a-mergear
```

Outra forma de mergear

Escrever nova mensagem de commit, que fica só essa.

```bash
git merge branch-a-mergear --squash
```

### Mensagem de commit

```bash
git commit -m 'mensagem do commit'
```

### Adicionar arquivos para o stash

Adiciona todos os arquivos para o stash

```bash
git add .
```

Adiciona somente um arquivo para o stash

```bash
git add fileName
```

### Deletar branch

Não pode estar na branch que quer deletar. Geralmente na branch pai.

```bash
git branch -D branch-a-deletar
```

### Commitar uma nova branch

```bash
git push origin branch-a-commitar
```
