---
name: relatorio-executivo
description: Gera o PDF executivo do projeto com estrutura fixa. Use ao montar ou atualizar o relatório final para quem decide.
---

# Skill: relatorio-executivo

<!-- Preencha os colchetes com a estrutura e as regras do relatório do projeto. -->

Estrutura não negociável: sempre o mesmo número de páginas, na mesma ordem.

## Estrutura do PDF

- Pág 1 — [Diagnóstico: número principal em destaque e recomendação principal]
- Pág 2 — [Drivers ou achados, em blocos visuais]
- Pág 3 — [Plano de ação com prazos e responsáveis, e rodapé com ressalvas]

## Regras

- Biblioteca: [por exemplo reportlab]. Paleta: [cores #HEX]
- Números em formato brasileiro (R$ 1.234,56 e DD/MM/AAAA)
- Todo número vem dos dados, nunca digitado à mão
- Afirmar associação como associação, nunca como causa sem evidência
- Salvar em reports/ com nome descritivo, em .pdf
