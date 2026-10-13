# Modelo de projeto de análise de dados

Base para começar projetos de análise de dados com a mesma arquitetura: pastas com propósito, contexto fixo para o Claude Code, subagents e skills reutilizáveis.

## O que vem pronto

| Item | Para que serve |
|---|---|
| `CLAUDE.md` | Contexto do projeto, em seções para preencher |
| `.claude/agents/` | Subagents: `data-auditor` (cético) e `insight-hunter` (curioso) |
| `.claude/skills/` | Skills: `grafico-profissional` e `relatorio-executivo`, com padrões para preencher |
| `data/` | Dados brutos, somente leitura (não versionados) |
| `notebooks/` | Análises exploratórias |
| `scripts/` | Código reutilizável |
| `reports/` | Entregáveis finais: gráficos e PDFs |

## Como começar um projeto novo

**Pelo GitHub:** abra este repositório e clique em **Use this template → Create a new repository**. Depois clone o novo repositório.

**Pela linha de comando:**

```
gh repo create nome-do-projeto --template Acalaes/modelo-projeto-dados --private --clone
```

Em seguida:

1. Abra a pasta no VS Code e inicie o Claude Code nela.
2. Preencha o `CLAUDE.md` (cada seção tem uma dica entre colchetes).
3. Preencha os colchetes das duas skills com o padrão do projeto.
4. Coloque os dados brutos em `data/`. Essa pasta nunca vai para o GitHub.

## Como evoluir o modelo

Melhore **este** repositório: novos agentes, skills ou seções do `CLAUDE.md`. Os projetos criados **depois** já nascem com a versão nova. Projetos que já existem **não** são atualizados sozinhos: copie à mão o que quiser levar para eles.

## Licença

[MIT](LICENSE)
