# Universidade Livre — Finanças, Investimentos e Economia (Brasil)

Um caminho para a educação autodidata em **finanças**, **investimentos**, **economia** e **empreendedorismo** usando materiais on-line (priorizando PT-BR).

> **Aviso importante:** este repositório tem fins educacionais e **não é recomendação** de investimento, compra/venda de ativos ou aconselhamento financeiro/tributário/jurídico.

---

## Conteúdos

- [Sumário](#sumário)
- [Como usar](#como-usar)
- [Princípios do currículo](#princípios-do-currículo)
- [Dependências entre assuntos](#dependências-entre-assuntos)
- [Currículo](#currículo)
- [Especializações](#especializações)
- [Extras](#extras)
- [Como contribuir](CONTRIBUTING.md)
- [Código de conduta](CODE_OF_CONDUCT.md)
- [Ajuda](HELP.md)
- [FAQ](FAQ.md)

---

## Sumário

Este “curso” é pensado para quem quer **fundamentos** (não apenas “dicas de mercado”) e prefere aprender com uma trilha estruturada.

O currículo está organizado em etapas, com:
- um “mínimo essencial” (para avançar sem lacunas),
- leituras/recursos opcionais,
- projetos práticos (planilhas, estudos de caso, análises).

---

## Como usar

1. Siga a ordem das etapas (ou pule, desde que respeite os pré-requisitos).
2. Registre o seu progresso (ex.: um repositório pessoal com anotações e projetos).
3. Ao final de cada etapa, faça **um projeto** (mesmo simples) para consolidar.

Sugestão: crie um diretório `meu-progresso/` no seu fork com:
- resumos em Markdown,
- planilhas (sem dados sensíveis),
- notebooks (Python/R) de estudo.

---

## Princípios do currículo

Os conteúdos incluídos aqui devem, idealmente:
- ser gratuitos ou ter parte significativa aberta (quando pagos, **marcar como pago**);
- ter método pedagógico (curso, apostila estruturada, livro-texto, etc.);
- ter reconhecimento de qualidade (instituições confiáveis e/ou validação da comunidade);
- respeitar direitos autorais (linkar é ok; redistribuir material fechado, não).

---

## Dependências entre assuntos

```mermaid
graph TD
A[Finanças pessoais] --> B[Matemática financeira]
B --> C[Renda fixa]
B --> D[Renda variável]
C --> E[Alocação e carteira]
D --> E
F[Economia (macro)] --> E
G[Contabilidade] --> H[Finanças corporativas]
H --> I[Valuation]
I --> E
E --> J[Especializações]
```

---

## Currículo

### 0ª Etapa — Ferramentas e base

| Etapa | Conteúdo | Pré-requisitos | Prática sugerida |
|------:|----------|----------------|------------------|
| 0 | Excel/Sheets (tabelas, PROCV/XLOOKUP, Tabela Dinâmica) | - | montar uma planilha de orçamento pessoal |
| 0 | Estatística básica (média, variância, correlação) | - | analisar uma série temporal simples (inflação/juros) |

---

### 1ª Etapa — Finanças pessoais e cidadania financeira

| Etapa | Curso/Conteúdo | Pré-requisitos | Prática sugerida |
|------:|----------------|----------------|------------------|
| 1 | Banco Central — cursos de cidadania financeira | 0 | orçamento + reserva de emergência + metas |
| 1 | FGV — cursos gratuitos em educação financeira | 0 | diagnóstico financeiro (receitas, despesas, dívidas) |
| 1 | Portal do Investidor (CVM) — guias/cadernos/livros | 0 | checklist de “proteção do investidor” |

---

### 2ª Etapa — Investimentos (fundamentos)

| Etapa | Curso/Conteúdo | Pré-requisitos | Prática sugerida |
|------:|----------------|----------------|------------------|
| 2 | FGV — Como fazer investimentos 1 | 1 | simular carteira simples (renda fixa x caixa) |
| 2 | FGV — Como fazer investimentos 2 | 2 | estudar perfil de risco e diversificação |
| 2 | B3 Educação — cursos para investidores | 1 | mapear produtos (Tesouro, CDB, ações, FII, etc.) |
| 2 | ANBIMA Edu (cursos/certificações) | 1 | trilha para CPA-10/CPA-20/CEA (opcional) |

---

### 3ª Etapa — Economia (micro e macro)

| Etapa | Curso/Conteúdo | Pré-requisitos | Prática sugerida |
|------:|----------------|----------------|------------------|
| 3 | Introdução à microeconomia (aulas abertas) | 0 | elasticidade: estimar efeitos simples em dados |
| 3 | Introdução à macroeconomia (playlist aberta) | 0 | construir “painel macro” (PIB, inflação, juros, câmbio) |

---

### 4ª Etapa — Empreendedorismo e negócios

| Etapa | Curso/Conteúdo | Pré-requisitos | Prática sugerida |
|------:|----------------|----------------|------------------|
| 4 | Sebrae — cursos online e gratuitos | 0 | canvas + precificação + fluxo de caixa |
| 4 | BNDES — Trein@ BNDES (linhas de financiamento) | 0 | plano de financiamento (cenários) |
| 4 | FGV — Empreendedorismo para o Mercado Financeiro | 0 | simular “go-to-market” de um serviço financeiro |
| 4 | Link School of Business (programas presenciais) | - | (opcional/pago) usar como referência de grade |

---

## Especializações

As especializações vivem em [`specializations/`](specializations/):

- [Investimentos](specializations/investimentos/README.md)
- [Economia](specializations/economia/README.md)
- [Empreendedorismo](specializations/empreendedorismo/README.md)
- [Carreira no mercado financeiro (BR)](specializations/carreira-mercado-financeiro/README.md)

---

## Extras

Conteúdos bons que não “cabem” na grade principal ficam em [`extras/`](extras/README.md).

---

## Como contribuir

Veja [CONTRIBUTING.md](CONTRIBUTING.md).
