# Consulta-modelo para a IA de apoio (3 minutos)

Usar só quando há pelo menos uma taxa abaixo do piso ou a semana é classificada como Pré-Queda.

```text
Contexto: vendo um programa online de contabilidade por €149 a independentes, via LinkedIn.
Dados da semana: impressões [X], cliques [X], visitas [X], checkouts iniciados [X], vendas [X].
Taxas: CTR [X]% (piso 0,5%), Intenção [X]% (piso 3,0%), Ação [X]% (piso 30%).
Alerta ativo: [taxa abaixo do piso].
Devolve: 1) a hipótese mais provável, 2) UMA única ação para os próximos 7 dias, 3) a taxa e o valor que confirmam ou refutam a hipótese. Não sugiras mais de 1 alteração.
```

Regra: a resposta da IA é uma proposta. A decisão final é minha e só uma ação entra no ciclo seguinte.
