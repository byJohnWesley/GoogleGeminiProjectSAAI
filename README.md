# 🧠 SAAI – Sistema Avançado de Análise de Investimentos

O **SAAI** é um sistema inteligente composto por múltiplos agentes que analisam o mercado financeiro de forma ampla e integrada. Seu objetivo é apresentar **opções de investimento mais seguras**, mesmo para investidores iniciantes.

> ⚠️ Este repositório é um esboço funcional criado para entrega de um exercício da Alura com o Google Gemini. Algumas melhorias e atualizações ainda são necessárias.

---

## 🔍 Como funciona

O sistema é dividido em **6 agentes especializados**, que trabalham em conjunto para filtrar, analisar e recomendar ativos de forma fundamentada.

### 👥 Estrutura dos agentes

1. **Agente Coletor de Empresas**  
   Coleta dados de empresas relacionadas ao setor ou ativo escolhido pelo usuário.

2. **Agente de Análise Macroeconômica**  
   Busca notícias relevantes da macroeconomia com até 30 dias de antiguidade que impactam o setor pesquisado.

3. **Agente de Análise Microeconômica**  
   Realiza o mesmo processo do agente 2, mas focando no ambiente microeconômico.

4. **Agente de Integração Analítica**  
   Integra dados fundamentais, notícias macro e microeconômicas, identificando padrões com base em ciclos anteriores, sempre considerando cenários de baixa probabilidade.

5. **Agente Fundamentalista Avançado**  
   Reavalia os indicadores fundamentais, agora sob a ótica das análises do agente anterior.

6. **Agente Avaliador Final**  
   Retorna uma lista **ranqueada e justificada** com as melhores opções de investimento para o setor analisado, considerando todos os cenários.

---

## 🛠️ Tecnologias

- Python
- Google Gemini API
- Jupyter Notebooks
- Web scraping / coleta de dados
- Análise de dados econômicos

---

## 🤖 Observação

Levo em conta muitos indicadores. Infelizmente, o tempo é curto 😅  
Espero que aproveitem a ferramenta! 😉

---

## 📌 Status

🚧 Projeto em desenvolvimento. Atualizações futuras devem incluir:
- Melhor integração com APIs de dados financeiros
- Interface interativa
- Sistema de pontuação por risco/retorno

