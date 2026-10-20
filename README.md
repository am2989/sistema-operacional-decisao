# Sistema Operacional de Decisão, Governança por Dados e Crescimento

Desafio de Projeto Final da formação **Creator Data Marketing System** (DIO).

Este repositório reúne o documento final de entrega e os modelos de trabalho do sistema de decisão que construí: um método para deixar de criar conteúdo por intuição e passar a decidir com base em dados reais de receita.

> **Nota de transparência:** o projeto, os valores, as taxas e o histórico são **dados fictícios**, assumidos como simulação para fins do desafio.

## Documento de entrega

📄 **[Abrir o documento final (link público)](https://docs.google.com/document/d/1jbArMzoO3woslncqrdcm7qFNhxcOgJPh3TowZYfedO4/edit?usp=sharing)**

Uma cópia em PDF está em [`docs/documento-final.pdf`](docs/documento-final.pdf).

## Resumo do projeto

| Item | Definição |
|---|---|
| Autora | Alda Marlene Anjo Benta |
| Projeto (simulado) | Contas Claras com a Alda |
| Caminho escolhido | B – Validação e Revisão do Sistema Existente |
| Produto | Programa online "Contabilidade Descomplicada para Independentes" |
| Ticket médio | €149 |
| Canal de atração | LinkedIn (principal) e Instagram (secundário) |
| Canais de conversão | Link no perfil → página de vendas → checkout, com apoio de WhatsApp |
| Objetivo de 90 dias | 30 vendas (€4.470) entre 01/11/2026 e 31/01/2027, com reembolsos até 5% |
| Métrica Mãe | Vendas pagas por semana |
| Indicador antecedente | Taxa de início de checkout (Intenção) |

## Como o sistema funciona

### 1. Métricas essenciais e réguas de saúde

| Etapa | Métrica | Referência saudável | Piso (alerta) |
|---|---|---|---|
| Atenção | CTR do link (cliques ÷ impressões) | 1,0% | 0,5% |
| Intenção | Início de checkout (checkouts ÷ visitas à página) | 6,0% | 3,0% |
| Ação | Pagamento concluído (vendas ÷ checkouts) | 45% | 30% |

Os valores iniciais são benchmarks genéricos de marketing digital e dados fictícios. A primeira recalibração está marcada para **30/11/2026**.

### 2. Mapa preditivo

| Cenário | Sinal na Intenção | Postura |
|---|---|---|
| Pré-Queda | Abaixo de 3,0% em 2 semanas seguidas, ou queda de 30% face à média de 4 semanas | Ativar a matriz de investigação |
| Estabilidade | Entre 4,5% e 7,4% | Manter o ciclo |
| Oportunidade de Escala | 7,5% ou mais em 2 semanas seguidas | Aumentar o volume em 1 publicação por semana |

As vendas pagas confirmam-se 3 a 7 dias depois da leitura da Intenção (desfasamento temporal).

### 3. Protocolo de ação

Cada taxa abaixo do piso tem um comando de investigação definido (conteúdo e CTA, oferta e página, ou checkout), e cada ciclo tem **uma única decisão**, para que a relação causa-efeito seja legível. O documento inclui regras para semanas atípicas (feriados, amostra com menos de 100 visitas, publicação viral, checkout fora do ar).

### 4. Ritual semanal de 10 minutos

| Passo | Tempo | O que se faz |
|---|---|---|
| Alimentação de dados | 2 min | Inserir 6 números brutos da semana |
| Leitura hierárquica | 5 min | Métrica Mãe → taxas de transição → cores de alerta → mapa preditivo |
| IA de apoio | 3 min | Só com alerta vermelho: consulta estruturada que devolve 1 hipótese e 1 ação |

## Estrutura do repositório

```
├── README.md
├── docs/
│   └── documento-final.pdf        # cópia do documento de entrega
└── templates/
    ├── registo-semanal.csv        # folha do ritual semanal
    └── prompt-ia-apoio.md         # consulta-modelo para a IA de apoio
```

## Como usar os modelos

1. Abrir `templates/registo-semanal.csv` numa folha de cálculo (Excel ou Google Sheets).
2. Todas as segundas-feiras, acrescentar uma linha com os 6 números brutos da semana anterior.
3. Calcular as taxas com as fórmulas: `CTR = cliques ÷ impressões`, `Intenção = checkouts ÷ visitas`, `Ação = vendas ÷ checkouts`.
4. Comparar com os pisos e classificar a semana (verde, amarelo ou vermelho).
5. Com alerta vermelho, preencher `templates/prompt-ia-apoio.md` e pedir a análise à IA.

## Ferramentas

- Documento: Claude (Claude Docs)
- Registo e dashboard: folha de cálculo (Excel / Google Sheets)
- IA de apoio: assistente de IA, com a consulta-modelo deste repositório

## Autora

**Alda Marlene Anjo Benta**
[LinkedIn](linkedin.com/in/alda-benta) · [GitHub](https://github.com/am2989)

Desafio de Projeto Final · DIO · 2026
