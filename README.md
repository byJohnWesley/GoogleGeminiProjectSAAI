# 🧠 SAAI – Sistema Avançado de Análise de Investimentos

O **SAAI** é um sistema de análise que simula o trabalho de uma equipe de especialistas em investimentos. A proposta é organizar as etapas de avaliação de ativos por meio de agentes automatizados, que coletam dados, cruzam informações e apontam opções mais seguras, especialmente para quem ainda não tem muita experiência no mercado financeiro.

> ⚠️ Este projeto foi desenvolvido como parte de um exercício prático da Alura com uso da API do Google Gemini. Algumas partes ainda estão em fase de ajuste.

---

## 🔍 Como funciona

O sistema é composto por **6 agentes distintos**, que operam de forma sequencial. Cada um tem uma função específica e colabora para formar uma recomendação fundamentada.

---

### 👥 Estrutura dos agentes

1. **Agente Coletor de Empresas**  
   Localiza empresas com base no setor ou ativo informado inicialmente pelo usuário.

2. **Agente de Análise Macroeconômica**  
   Recolhe notícias econômicas amplas com até 30 dias de antiguidade, focando em fatores que impactam o mercado de forma geral.

3. **Agente de Análise Microeconômica**  
   Faz uma busca semelhante, mas voltada para aspectos específicos do setor em questão.

4. **Agente de Integração Analítica**  
   Une os dados coletados pelos agentes anteriores e identifica padrões e ciclos, evitando conclusões precipitadas ou fora de contexto.

5. **Agente Fundamentalista Avançado**  
   Reavalia os indicadores fundamentais das empresas sob uma ótica mais contextualizada, considerando as análises anteriores.

6. **Agente Avaliador Final**  
   Gera uma lista com as melhores opções, classificadas por:
   - Nota (0 a 10)
   - Probabilidade de acerto
   - Nível de risco (baixo, moderado ou alto)
   - Relação risco/retorno
   - Justificativa com base nos dados analisados

---

## 🛠️ Tecnologias utilizadas

- Python
- Google Gemini API
- Jupyter Notebooks
- Web scraping
- Análise de dados financeiros e notícias econômicas

---

## ✅ Utilidade do projeto

Este projeto serve como uma introdução prática ao uso de inteligência artificial para análise de investimentos. Apesar de simples, o sistema mostra como é possível estruturar decisões com base em dados reais, de forma organizada e compreensível.

---

## 📌 Status

- Estrutura funcional concluída
- Possíveis melhorias futuras:
  - Integração direta com APIs de dados do mercado
  - Criação de uma interface
  - Geração de relatórios
  - Sistema de pontuação mais completo

---

## 🗒️ Observações

Este é meu primeiro projeto nesse formato. A experiência foi útil para entender como organizar um fluxo de análise automatizada. Ainda há pontos a desenvolver, mas a base está funcional e serve como ponto de partida para projetos mais robustos.

Você me encontra por ai como @byjohnwesley
