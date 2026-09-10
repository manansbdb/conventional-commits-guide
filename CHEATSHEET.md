# Conventional Commits Cheatsheet / Folha de consulta

## English

### Good messages
- Use imperative mood: "add", not "added"
- Keep the subject ≤ ~72 characters
- Scope is optional but helpful: `feat(api): ...`
- Separate body from subject with a blank line

### Breaking changes
```
feat(api)!: rename /users to /accounts

BREAKING CHANGE: clients must call /accounts
```

### Related issues
```
fix(ui): correct modal focus trap

Closes #42
```

## Português

### Boas mensagens
- Usa modo imperativo: "add", não "added" / "adiciona", não "adicionou"
- Mantém o assunto ≤ ~72 caracteres
- O scope é opcional mas útil: `feat(api): ...`
- Separa o corpo do assunto com uma linha em branco

### Alterações incompatíveis
```
feat(api)!: rename /users to /accounts

BREAKING CHANGE: clients must call /accounts
```

### Issues relacionadas
```
fix(ui): correct modal focus trap

Closes #42
```
