# Como contribuir

Obrigado por querer melhorar este guia :)

## O que aceitamos

- Cursos e materiais (vídeos, playlists, apostilas, livros) **com qualidade e estrutura**.
- Preferência por conteúdo **gratuito** e em **PT-BR**, mas podemos incluir:
  - conteúdo em EN/ES (quando for referência),
  - conteúdo pago (desde que claramente marcado como **pago** e com justificativa).

## O que NÃO aceitamos

- Pirataria (arquivos de cursos fechados, PDFs não autorizados, etc.).
- Links para “sinais”, “calls”, promessas de rentabilidade, ou marketing agressivo.
- Recomendação de investimento (este repositório é educacional).

## Padrão para adicionar um recurso

Ao adicionar um item, inclua:

- **Título**
- **Instituição / autor**
- **Link**
- **Idioma**
- **Carga horária** (se houver)
- **Custo**: gratuito / pago / freemium
- **Pré-requisitos**
- **Tópicos** (tags)
- **Projeto sugerido** (1 linha)

### Exemplo (Markdown)

```md
| Etapa | Curso/Conteúdo | Pré-requisitos | Prática sugerida |
|------:|----------------|----------------|------------------|
| 2 | [Como fazer investimentos 1](LINK_AQUI) — FGV | 1 | montar uma planilha simples de alocação |
```

## Como abrir PR

1. Faça um fork
2. Crie uma branch: `feat/novo-recurso-b3` (exemplo)
3. Edite o arquivo certo:
   - grade principal: `README.md`
   - trilhas: `specializations/**/README.md`
   - extras: `extras/README.md`
4. Explique o “porquê” do recurso no PR
5. Se possível, adicione uma evidência de qualidade (ex.: programa, ementa, reputação da instituição)

## Como sugerir sem codar

Abra uma issue usando o template “Sugestão de recurso”.
