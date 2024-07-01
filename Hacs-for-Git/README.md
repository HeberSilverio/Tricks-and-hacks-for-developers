
#### Comandos úteis no git
// força a mostrar se tem algum alteração de outros dev
```bash
git remote update origin --prune
```

// Salva as minhas alterações no stash para eu fazer o pull de outro dev 
```bash
git stash
```
// Apos o pull eu coloco as minhas alterações novamente que estavam salvas no stash
```bash
git stash pop
```