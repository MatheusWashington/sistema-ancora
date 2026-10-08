# Sistema Âncora

<!-- 1. O sistema âncora é um software voltado a auxiliar escolas com o monitoramento e intervenção em casos de evasão escolar, o problema usará um modelo de Machine Learning pra aprender e auxiliar nessa identificação e antecipação. -->

## O problema

<!-- 2. A evasão escolar é um problema persistente que afeta principalmente estudantes em situação de vulnerabilidade social. O acompanhamento atual é manual e reativo, dificultando intervenções preventivas eficazes. Isso pode levar cada vez mais alunos a se distanciarem até evadir. -->

## Objetivo

<!-- 3. Com o Sistema Âncora agora, será possível acompanhar em tempo real possíveis padrões de comportamento que podem levar a evasão escolar, fazendo com que a direção e a assistência social consigam intervir muito mais rápido em tentar recuperar o aluno dessa situação e reverter esse quadro. -->

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
