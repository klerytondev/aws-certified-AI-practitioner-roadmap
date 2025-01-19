# Resumo Rápido: AWS Certified AI Practitioner (AIF-C01)

Este documento fornece um resumo detalhado dos principais conceitos abordados na certificação AWS Certified AI Practitioner (AIF-C01).

---

### Fundamentos de Machine Learning:

- **Aumento da Acurácia do Modelo**: Aumentar o número de épocas (iterações de treinamento) pode melhorar a acurácia do modelo, mas é crucial monitorar o sobreajuste.
- **Acurácia**: Mede a proporção de imagens que o modelo classificou corretamente, sendo uma métrica adequada para avaliar o desempenho de um modelo de classificação de imagens.
- **Mitigação de Sobreajuste**: Aumentar o volume de dados usados no treinamento é uma das maneiras mais eficazes de melhorar a capacidade de generalização de um modelo, reduzindo o sobreajuste.
- **Tipos de Viés**:
  - Viés de amostragem ocorre quando o conjunto de dados de treinamento não é representativo da população, levando a resultados injustos.
  - Dados rotulados possuem entradas associadas a saídas esperadas, sendo usados em aprendizado supervisionado (detecção de spam, classificação de imagens e previsão de preços), enquanto dados não rotulados não possuem essas associações, sendo utilizados em aprendizado não supervisionado (agrupamento).
- **Análise Exploratória de Dados (EDA)**: Envolve a análise de dados para entender sua distribuição.
- **Modelos baseados em BERT (Bidirectional Encoder Representations from Transformers)**: Ideais para prever palavras ausentes em frases, analisando o contexto antes e depois da lacuna.
- **Overfitting**: O modelo aprende demais, incluindo ruídos, e funciona bem no treino, mas mal no teste. 
  - Overfitting = Modelo muito complexo.
- **Underfitting**: O modelo aprende de menos e não capta os padrões, indo mal no treino e no teste. 
  - Underfitting = Modelo muito simples.
- **Espaço Latente**: Representação matemática do conhecimento e da compreensão do modelo. Ao manipular os vetores no espaço latente, é possível influenciar as saídas do modelo de maneira controlada.
- **Subajuste**: Ocorre quando um modelo não identifica as relações nos dados de treinamento, levando a baixa acurácia nos dados de treinamento e de teste.
- **Sobreajuste**: Ocorre quando um modelo aprende com os dados de treinamento e não consegue ter um bom desempenho quando recebe novos dados. Esse fator explica por que o modelo tem alta acurácia nos dados de treinamento e baixa acurácia nos dados de teste.

### Métricas de Avaliação de Modelos:

- **Acurácia**: Percentual de previsões corretas, considerando verdadeiros positivos (VP) e verdadeiros negativos (VN). Útil para classificação.
- **BLEU**: Avalia a qualidade da tradução ao comparar texto gerado com referência humana.
- **Precisão**: Mede a proporção de VP dentre todos os positivos previstos. Útil para classificação.
- **MAPE**: Média dos erros percentuais absolutos entre valores reais e previstos. Útil para previsões numéricas, como vendas.
- **Recall**: Mede a proporção de VP corretamente identificados entre todos os positivos reais. Útil para classificação.
- **MAE**: Média dos erros absolutos entre valores reais e previstos. Útil para previsões numéricas, como vendas.
- **F1-Score**: Combina precisão e recall em uma média harmônica. Útil para classificação equilibrada.
- **Matriz de Confusão**: Usada para avaliar modelos de classificação.
- **ROUGE-N**: Avalia resumos com base na similaridade de n-gramas entre texto gerado e referência.
- **BERTScore**: Mede a similaridade semântica entre texto gerado e referência, útil para avaliar chatbots e modelos de linguagem.

### Serviços da AWS para IA:

- **Compreensão de Sentimentos**: Amazon Comprehend é um serviço de PNL que inclui recursos para análise de sentimentos, detecção de idioma, reconhecimento de entidade e muito mais.
- **SageMaker Clarify**: Ajuda a identificar e mitigar o viés em conjuntos de dados e modelos, fornecendo ferramentas para avaliar o viés nas etapas de preparação e treinamento de dados.
- **Bedrock**: Fornece acesso a modelos de fundação, incluindo grandes modelos de linguagem que suportam IA generativa e tarefas complexas de linguagem, incluindo análise de sentimentos.

### IA Generativa:

- **Engenharia de Prompt**: Criar prompts eficazes com instruções e contexto detalhados pode orientar o modelo a produzir conteúdo que se alinhe à voz e às mensagens da marca.
- **Geração de Conteúdo**: Modelos generativos de IA pré-treinados podem ser usados para gerar conteúdo de marketing. A engenharia de prompt é crucial para garantir que o conteúdo se alinhe à voz e às mensagens da marca.
- **Moderação de Conteúdo**: Amazon Rekognition pode ser usado para moderação de conteúdo em imagens e vídeos. Trilhos de proteção (guardrails) no Bedrock fornecem mecanismos para impor a adequação do conteúdo.
- **Plágio**: A IA generativa levanta preocupações éticas sobre a originalidade e a propriedade do conteúdo, especialmente em cenários acadêmicos.
- **Alucinações**: Referem-se ao modelo gerando informações que parecem factuais, mas não são baseadas em dados reais.

### Implementação Responsável de IA:

- **Minimização de Viés**: Detectar desequilíbrios ou disparidades nos dados ajuda a identificar qualquer viés inerente no conjunto de dados.
- **Transparência**: Avaliar regularmente o comportamento dos modelos e documentá-lo ajuda a entender seu impacto, incluindo qualquer viés que possa surgir.

### Casos de Uso de Negócios:

- **Chatbots de Atendimento ao Cliente**: O impacto de um chatbot no atendimento ao cliente pode ser avaliado medindo a duração média da chamada. Uma redução na duração da chamada indica que o chatbot está auxiliando efetivamente os funcionários do call center.
- **Geração de Dados Sintéticos**: Redes Adversárias Generativas (GANs) são especificamente projetadas para gerar dados sintéticos aprendendo com os dados existentes.

### Considerações de Custo:

- **Otimização de Custo no Bedrock**: Usar uma base de conhecimento permite que o modelo acesse informações relevantes dos PDFs sem incluir todo o conteúdo no prompt, tornando-o mais econômico.
- **Tipos de Instância para Treinamento**: As instâncias da série TRN, especialmente as instâncias trn1, são otimizadas especificamente para treinar modelos grandes e são alimentadas por chips AWS Trainium. Essas instâncias são projetadas para eficiência energética.

---

