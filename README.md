# Sistema Âncora

O Sistema Âncora é um software que ajuda escolas a monitorar e a intervir em casos de evasão escolar. Um modelo de Machine Learning analisa a frequência dos alunos, identifica padrões de ausência que indicam risco de evasão e avisa a direção e a assistência social com antecedência.

## O problema

A evasão escolar é um problema persistente, que afeta principalmente estudantes em situação de vulnerabilidade social.

Hoje, o acompanhamento costuma ser manual e reativo: a escola percebe o problema quando o aluno já faltou por semanas, e a intervenção chega tarde. Sem uma ação preventiva, o aluno vai se distanciando até abandonar a escola.

## Objetivo

O Sistema Âncora acompanha a frequência dos alunos de forma contínua e automatizada e identifica padrões de ausência que podem levar à evasão. Com o alerta antecipado, a direção e a assistência social conseguem intervir antes que o quadro se torne irreversível e ter mais chance de manter o aluno na escola.

O sistema apenas alerta. A decisão e a ação continuam sendo das pessoas da escola.

## Como contribuir

Para manter o projeto organizado, toda a equipe segue estas convenções.

### Branches

- A branch `main` sempre contém código funcionando. Não fazemos commit direto nela.
- Cada tarefa do quadro kanban tem uma branch própria, criada a partir da `main`.
- Formato do nome: `tipo/descricao-curta`, em minúsculas e com hífens.

```
feat/tela-de-login
fix/calculo-ausencia-feriado
docs/readme-inicial
```

### Commits

Usamos o padrão Conventional Commits:

```
tipo(escopo): descrição curta no imperativo
```

| Tipo | Quando usar |
|------|-------------|
| `feat` | Funcionalidade nova |
| `fix` | Correção de bug |
| `docs` | Documentação |
| `refactor` | Reorganização sem mudar o comportamento |
| `test` | Testes |
| `chore` | Configuração e manutenção |

Exemplo:

```
feat(frontend): adiciona tela de login
```

### Pull Requests

1. Abra o PR com título no mesmo padrão dos commits.
2. Descreva o que foi feito e qual cartão do quadro ele resolve.
3. Peça a revisão de pelo menos uma pessoa da equipe.
4. O merge só acontece depois da aprovação.

### Segurança

Nunca faça commit de dados reais de alunos, senhas ou chaves de acesso.
Use o `.gitignore` e variáveis de ambiente.
