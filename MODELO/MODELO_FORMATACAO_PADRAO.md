# MODELO DE FORMATAÇÃO PADRÃO — PLANO REAL 1994

**Arquivo:** MODELO_FORMATACAO_PADRAO.md
**Data de criação:** 27/09/2026
**Projeto:** PLANO REAL 1994
**Contexto:** Modelo institucional de formatação reutilizado de projetos anteriores.
**Finalidade:** Padronizar todos os documentos, pesquisas, análises e materiais produzidos neste projeto.
**Caminho:** MODELO/MODELO_FORMATACAO_PADRAO.md
**Repositório:** carlos-andrade/PLANO-REAL-1994

---

## 1. Estrutura obrigatória

Todo documento deve iniciar com:

# TÍTULO DO DOCUMENTO

**Arquivo:** NOME_DO_ARQUIVO.md  
**Data de criação:** DD/MM/AAAA  
**Projeto:** PLANO REAL 1994  
**Contexto:** Descrição objetiva do contexto do documento.  
**Finalidade:** Finalidade específica do material.  
**Caminho:** caminho/relativo/no/repositorio  
**Repositório:** carlos-andrade/PLANO-REAL-1994  

---

## 2. Hierarquia de conteúdo

Utilizar Markdown de forma consistente:

- **H1 (`#`)** para o título principal.
- **H2 (`##`)** para seções principais.
- **H3 (`###`)** para subseções.
- Listas para informações estruturadas.
- **Negrito** para conceitos, campos e informações de destaque.
- Citações em bloco (`>`) quando necessário.
- Tabelas quando facilitarem comparação ou auditoria.
- Separadores (`---`) para dividir blocos documentais.

---

## 3. Organização por temas

**Regra permanente:** sempre que surgir um tema novo no projeto, deve ser criada uma **nova pasta específica para esse tema**, antes de armazenar seus arquivos.

A pasta temática deve:

- ter nome claro, objetivo e consistente;
- conter os arquivos relacionados exclusivamente àquele tema;
- preservar a separação entre temas diferentes;
- evitar concentração de assuntos distintos na mesma pasta;
- facilitar localização, leitura, auditoria e continuidade da pesquisa.

Quanto maior o projeto, maior deve ser a preocupação com organização hierárquica e separação temática.

Exemplo:

```text
PLANO-REAL-1994/
├── MODELO/
├── PROMPTS/
├── TEMA_NOVO_01/
│   ├── documento.md
│   └── fontes.md
├── TEMA_NOVO_02/
│   └── documento.md
└── README.md
```

---

## 4. Organização analítica

Quando aplicável, os documentos devem separar claramente:

1. **Fatos documentados**
2. **Dados e cálculos**
3. **Interpretações**
4. **Controvérsias**
5. **Limitações**
6. **Fontes**
7. **Status**
8. **Versionamento**

Não apresentar interpretação como fato.

---

## 5. Controle documental

Quando houver evolução do material, registrar:

- **Versão**
- **Data**
- **Status**
- **Alterações realizadas**
- **Fontes utilizadas**
- **Caminho do arquivo**
- **Commit**, quando houver atualização no GitHub

---

## 6. Encerramento

Documentos analíticos devem, quando pertinente, terminar com:

## Status

**Status:** Em desenvolvimento / Em revisão / Validado / Concluído

## Fontes

Relacionar as fontes utilizadas, priorizando fontes primárias e institucionais.

---

## 7. Regra permanente do projeto

Este arquivo constitui o **modelo de formatação padrão do projeto PLANO REAL 1994**.

Todo novo material produzido para o projeto deve seguir este padrão.

**Regra estrutural adicional:** todo tema novo deve possuir sua própria pasta. Arquivos de temas diferentes não devem ser misturados na mesma pasta quando a separação temática for aplicável.

A organização do repositório deve priorizar clareza, rastreabilidade, entendimento e manutenção futura.
