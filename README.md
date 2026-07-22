# Emagreca_Sem_Passar_Fome_Gemini_Notebook
Criação de um caderno no Gemini Notebook utilizando engenharia de prompt para o desafio do Bootcamp Bradesco - GenAI, Dados & Cyber.

# 🏋️‍♂️ Miniguia de Estudos: Rotina de Treinos e Dieta Nordestina com NotebookLM

Este repositório contém a documentação completa do desafio prático proposto pela **DIO (Digital Innovation One)**, focado no uso da ferramenta **NotebookLM** para curadoria, síntese de conhecimento e inteligência artificial aplicada à saúde e bem-estar.

---

## 🎯 Contexto e Objetivos

### Contexto
O projeto surge da necessidade de unir estratégias de emagrecimento rápido e seguro com o fortalecimento de massa magra, aproveitando a riqueza cultural e nutricional da **culinária nordestina** (alimentos como macaxeira, cuscuz, batata-doce, ovos e carnes magras) associada a uma rotina eficiente de treinos (musculação e cardio).

### Objetivos de Estudo
* Explorar a capacidade de síntese do NotebookLM ao cruzar dados de nutrição e educação física.
* Praticar Engenharia de Prompts para extrair respostas precisas baseadas estritamente em fontes fornecidas.
* Estruturar um miniguia prático que sirva como modelo replicável para montagem de planos alimentares e de treino regionais.

---

## 📚 Curadoria de Fontes

Para alimentar o NotebookLM e garantir embasamento técnico e científico, foram selecionadas e carregadas as seguintes fontes de dados abertas:

1. **[Tabela TACO - Tabela Brasileira de Composição de Alimentos](https://www.cfn.org.br/wp-content/uploads/2017/03/taco_4_edicao_ampliada_e_revisada.pdf)**
   * *Uso:* Mapeamento de macronutrientes dos alimentos típicos do Nordeste.
2. **[Guia Alimentar para a População Brasileira (Ministério da Saúde)](https://bvsms.saude.gov.br/bvs/publicacoes/guia_alimentar_populacao_brasileira_2ed.pdf)**
   * *Uso:* Diretrizes sobre comida de verdade, alimentos minimamente processados e cultura regional.
3. **[Diretrizes da Sociedade Brasileira de Medicina do Esporte (SBME)](https://www.scielo.br/j/rbme/)**
   * *Uso:* Prescrição segura de exercícios físicos, frequência semanal e gasto calórico.

---

## 🧪 Engenharia de Prompts e "Cicatrizes" (Troubleshooting)

Nesta seção, documentou-se a evolução das perguntas para instruir o NotebookLM até alcançar o resultado ideal.

### ❌ Iteração 1: Prompt Muito Genérico
* **Prompt:** *"Crie um treino e uma dieta nordestina para emagrecer rápido."*
* **Resultado Obtido:** A IA gerou uma resposta simplista, sugerindo apenas "coma cuscuz e corra 30 minutos", sem tabelas, divisões de treino ou especificações de porções.
* **Problema:** Faltava direcionamento sobre papel do especialista, estrutura das seções e delimitação de variáveis (séries, refeições, etc.).

### ⚠️ Iteração 2: Falta de Especificidade de Fontes
* **Prompt:** *"Atue como nutricionista. Monte uma dieta nordestina de emagrecimento e uma rotina de treinos ABC."*
* **Resultado Obtido:** O plano citou ingredientes como tapioca em excesso (alto índice glicêmico sem fibra) e não justificou a escolha dos treinos com base nos PDFs anexados.
* **Problema:** A IA não utilizou os dados da Tabela TACO de forma rigorosa.

### ✅ Iteração 3: Prompt Final "Nota 10" (Aprovado)
* **Prompt:**
  > *"Atue como um Especialista em Educação Física, Nutricionista Clínico Esportivo e endocrinologista.*
  > 
  > *Objetivo: Com base no material de apoio anexado a este caderno, elabore um plano completo e personalizado contendo:*
  > *1. Uma rotina de treinos semanal.*
  > *2. Um plano alimentar focado em emagrecimento rápido e seguro, priorizando exclusivamente alimentos típicos da culinária nordestina.*
  > 
  > *[Objetivo: Com base no material de apoio anexado a este caderno, elabore um plano completo e personalizado contendo:

Uma rotina de treinos semanal.

Um plano alimentar focado em emagrecimento rápido e seguro, priorizando exclusivamente alimentos típicos da culinária nordestina.

Diretrizes para o Plano Alimentar (Dieta Nordestina):
Enfoque Regional: Utilize ingredientes acessíveis e tradicionais da região Nordeste (ex.: macaxeira, batata-doce, cuscuz, inhame, ovos, queijo coalho/mussarela com moderação, carne de sol magra, frango, peixes, feijão fradinho/caupi, frutas regionais como acerola, caju, goiaba, mamão, etc.).

Perfil Nutricional: Foco em déficit calórico moderado para perda de gordura eficiente, preservando a massa magra (alta ingestão proteica e fibras).

Estrutura das Refeições: Organize a dieta em 4 a 5 refeições diárias (Café da manhã, Almoço, Lanche da tarde, Jantar e Ceia/Opcional), indicando porções ou opções de substituição simples.

Dicas de Preparo: Oriente sobre formas saudáveis de preparo (ex.: cozidos, grelhados, no vapor, cuscuz sem excesso de manteiga).

Diretrizes para a Rotina de Treinos:
Estrutura: Monte uma divisão semanal clara (ex.: ABC, AB ou Treino Full-Body), adaptada para potencializar o gasto calórico.

Tipos de Exercício: Combine musculação/fortalecimento (para preservação de massa muscular) com exercícios cardiovasculares (HIIT ou cardio moderado).

Detalhamento: Para cada dia, especifique:

Grupo muscular trabalhado.

Nome dos exercícios sugestivos.

Séries e faixa de repetições.

Tempo e tipo de aeróbico recomendados.

Formatação da Resposta:
Use tabelas e listas organizadas para facilitar a leitura.

Divida a resposta em seções claras: 1. Visão Geral e Estratégia, 2. Plano Alimentar Nordestino, 3. Rotina de Treinos e 4. Recomendações Gerais (Hidratação e Descanso).

Caso as fontes anexadas contenham dados de um perfil específico (idade, peso, rotina), ajuste as recomendações aos dados das fontes. Se não houver, apresente o plano baseado em diretrizes padronizadas de recomposição corporal.

💡 Dica de Uso no NotebookLM:
Para obter o melhor resultado possível:

Suba fontes de apoio: Anexe no NotebookLM arquivos como PDFs sobre tabelas nutricionais, guias de treino ou um arquivo de texto com suas métricas pessoais (seu peso atual, altura, nível de experiência e rotina).

Cole o prompt acima no chat do NotebookLM e dê o comando!]*"
* **Resultado Obtido:** Resposta rica, organizada em tabelas, respeitando o déficit calórico com alimentos do Nordeste e com divisão de treino coerente.

---

## 📘 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado do Assunto
* **Emagrecimento Seguro e Regional:** Para perder gordura sem perder massa magra, é crucial o déficit calórico com aporte proteico adequado (1.6g a 2g por kg). Alimentos nordestinos como cuscuz, macaxeira e inhame são excelentes fontes de carboidratos de baixo/médio índice glicêmico quando combinados com fibras e proteínas (ovos, queijo coalho moderado, carne de sol magra).
* **Estrutura de Treino:** A combinação de musculação (preservação muscular) com aeróbico (HIIT/LISS para aumento de gasto metabólico) é a chave para o emagrecimento rápido sustentável.

### 2. Glossário de Conceitos Aprendidos
* **Déficit Calórico:** Condição em que o gasto energético diário é maior do que a quantidade de calorias ingeridas.
* **LISS (Low-Intensity Steady State):** Exercício aeróbico de baixa intensidade e longa duração (ex.: caminhada rápida).
* **HIIT (High-Intensity Interval Training):** Treino intervalado de alta intensidade que acelera o metabolismo pós-treino (efeito EPOC).
* **Macronutrientes:** Nutrientes principais necessários em grandes quantidades (Carboidratos, Proteínas e Lipídios).

### 3. Prompts Reutilizáveis para Revisões Futuras

#### 🔄 Prompt para Ajuste de Substituições Alimentares:
```text
Com base no meu plano alimentar gerado, substitua o [Ingrediente A] por outro alimento típico nordestino que possua equivalência nutricional próxima segundo a tabela TACO.
