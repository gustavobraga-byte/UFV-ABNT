# Skill: ufv-abnt

Skill para formatação e normalização de trabalhos acadêmicos conforme as normas da **Universidade Federal de Viçosa (UFV)** e da **ABNT**, baseada no manual publicado pela Biblioteca Central da UFV em 2025.

**Normas cobertas:** NBR 14724/2024 · NBR 6023/2018 · NBR 10520/2023  
**Fonte oficial:** https://www.bbt.ufv.br/wp-content/uploads/2025/02/Normalizacao-de-trabalhos-academicos-2025-UFV.pdf

---

## O que esta skill faz

Orienta Claude a responder perguntas e auxiliar tarefas relacionadas à normalização de trabalhos acadêmicos: estrutura do documento, formatação, elaboração de referências bibliográficas e citações. Cobre tanto as regras gerais da ABNT quanto as especificidades da UFV para programas de pós-graduação (UFV-PPG).

---

## Quando usar

A skill é ativada quando o usuário menciona, por exemplo:

- "Como formatar meu TCC/dissertação/tese?"
- "Qual é a estrutura de uma monografia?"
- "Como fazer referência de livro/artigo/site pela ABNT?"
- "Como citar um autor no texto?"
- "Quais são as normas da UFV?"
- "Como fazer o resumo / abstract / folha de rosto / sumário?"
- "Qual a margem / fonte / espaçamento correto?"

---

## Tipos de trabalho cobertos

| Tipo | Grau |
|------|------|
| TCC / Trabalho de Graduação Interdisciplinar | Bacharel / Licenciado |
| Monografia de Especialização | Especialista |
| Dissertação | Magister Scientiae (Mestrado UFV) |
| Tese | Doctor Scientiae (Doutorado UFV) |

---

## Conteúdo da skill

```
ufv-abnt/
├── SKILL.md                        # Guia principal
└── references/
    ├── referencias-abnt.md         # Modelos detalhados de referências
    └── citacoes-abnt.md            # Regras e exemplos de citações
```

### SKILL.md — o que cobre

- Definições dos tipos de trabalho acadêmico
- Estrutura completa (elementos pré-textuais, textuais e pós-textuais) com tabela de obrigatoriedade
- Regras de formatação: papel, fonte, margens, espaçamento, paginação
- Detalhamento de cada elemento pré-textual (capa, folha de rosto, ficha catalográfica, errata, folha de aprovação, dedicatória, agradecimentos, epígrafe, resumo, abstract, listas, sumário)
- Notas descritivas prontas para cada tipo de trabalho
- Regras para seções, ilustrações, tabelas, siglas e equações
- Resumo das regras de referências e citações (com ponteiro para os arquivos de referência)
- Checklist de revisão rápida

### references/referencias-abnt.md

Modelos prontos de referências para: livros, trabalhos acadêmicos, artigos de periódico, capítulos de livro, sites, eventos, documentos jurídicos, redes sociais, e-books, podcasts, e mais. Inclui regras para autoria (pessoa física, jurídica, eventos, autoria desconhecida), local, editora e data.

### references/citacoes-abnt.md

Regras e exemplos de citações diretas (curtas e longas), indiretas (paráfrase), citação de citação (`apud`), sistema autor-data, sistema numérico, notas de rodapé explicativas e de referência, e casos especiais (informação verbal, obra no prelo, documentos jurídicos).

---

## Limitações

- A skill cobre as normas vigentes em 2025 conforme o manual da UFV. Normas podem ser atualizadas; conferir a versão mais recente no site da Biblioteca Central: https://www.bbt.ufv.br/manual-de-normalizacao-de-trabalhos-academicos/
- A ficha catalográfica deve ser solicitada à Biblioteca Central da UFV: https://www.bbt.ufv.br/ficha-catalografica-online/
- Para dúvidas muito específicas sobre programas de pós-graduação individuais, consultar o próprio PPG.

---

## Referência do manual base

PIRES, Alice Regina Pinto; SILVA, Bruna (org.). **Normalização de trabalhos acadêmicos:** atualizada conforme ABNTs NBR 14724/2024, NBR 6023/2018 e NBR 10520/2023. Viçosa, MG: UFV, Biblioteca Central, 2025. 144 p. Disponível em: https://www.bbt.ufv.br/manual-de-normalizacao-de-trabalhos-academicos/. Acesso em: 23 maio 2025.
