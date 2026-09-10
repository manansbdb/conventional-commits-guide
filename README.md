# Conventional Commits Guide / Guia de Conventional Commits

## Overview / Visão geral

**EN:** Bilingual cheatsheet for [Conventional Commits](https://www.conventionalcommits.org/).

**PT:** Folha de consulta bilingue para [Conventional Commits](https://www.conventionalcommits.org/).

## Format / Formato

```
<type>(optional scope): <description>

[optional body]

[optional footer(s)]
```

## Types / Tipos

| Type | EN | PT |
|------|----|----|
| `feat` | New feature | Nova funcionalidade |
| `fix` | Bug fix | Correção de bug |
| `docs` | Documentation only | Apenas documentação |
| `style` | Formatting, no logic change | Formatação, sem lógica |
| `refactor` | Code change, no feat/fix | Refatoração sem feat/fix |
| `perf` | Performance improvement | Melhoria de desempenho |
| `test` | Add or fix tests | Adicionar/corrigir testes |
| `chore` | Build, tooling, misc | Build, tooling, misc |
| `ci` | CI configuration | Configuração de CI |

## Examples / Exemplos

```
feat(auth): add login rate limiting
fix(api): handle null user id
docs: update README installation steps
feat!: drop support for Node 16
```

**EN:** `!` or `BREAKING CHANGE:` footer marks a breaking change.

**PT:** `!` ou o footer `BREAKING CHANGE:` marca uma alteração incompatível.

See `CHEATSHEET.md` for more.

## License / Licença

MIT © 2026 manansbdb

## Support / Apoio

See [SUPPORT.md](SUPPORT.md) · Ver [SUPPORT.md](SUPPORT.md).
