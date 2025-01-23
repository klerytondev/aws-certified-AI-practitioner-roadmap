# Resumo Rápido: AWS Certified AI Practitioner (AIF-C01)

Este documento fornece um resumo detalhado dos principais conceitos abordados na certificação AWS Certified AI Practitioner (AIF-C01).

---
## Índice
1. [Conteúdo Completo](#conteúdo-completo)
    1. [Fundamentos de Machine Learning](#fundamentos-de-machine-learning)
    2. [Métricas de Avaliação de Modelos](#métricas-de-avaliação-de-modelos)
    3. [Serviços da AWS para IA](#serviços-da-aws-para-ia)
    4. [IA Generativa](#ia-generativa)
    5. [Implementação Responsável de IA](#implementação-responsável-de-ia)
    6. [Casos de Uso de Negócios](#casos-de-uso-de-negócios)
    7. [Considerações de Custo](#considerações-de-custo)
    8. [Segurança e Governança](#segurança-e-governança)

---

## Conteúdo Completo

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

- **Amazon SageMaker**: Plataforma abrangente para desenvolvimento de modelos de machine learning, que inclui ferramentas para preparação de dados, treinamento, deploy e monitoramento de modelos. Recursos como AutoML, pipelines e endpoints gerenciados tornam o SageMaker essencial para projetos de ML em produção.
- **Amazon Comprehend**: Serviço de processamento de linguagem natural (PNL) que analisa textos para identificar sentimentos, entidades e tópicos. É útil em aplicações como análise de feedbacks de clientes ou automação de tarefas baseadas em textos.
- **Amazon Rekognition**: Serviço de análise de imagens e vídeos que identifica objetos, pessoas, atividades e texto. Recursos incluem detecção de rostos e moderação de conteúdo visual, frequentemente usados em segurança, mídia e entretenimento.
- **Amazon Bedrock**: Permite acesso a modelos de fundação, incluindo grandes modelos de linguagem que suportam IA generativa e tarefas complexas de linguagem, como análise de sentimentos.
- **Amazon Polly**: Serviço de síntese de texto em fala (TTS), capaz de converter texto em áudio realista. Com suporte a múltiplos idiomas e vozes personalizáveis, é ideal para aplicações como assistentes virtuais e narração automatizada.
- **Amazon Translate**: Serviço de tradução automática em tempo real, suportando múltiplos idiomas. Ele é útil para e-commerces globais, legendas multilíngues e comunicações internacionais.
- **Amazon Fraud Detector**: Serviço da AWS que utiliza machine learning para identificar automaticamente atividades potencialmente fraudulentas em transações online, como pagamentos e criação de contas.
- **Amazon Lookout for Vision**: Aplica aprendizado de máquina para identificar defeitos visuais em imagens, ajudando a detectar anomalias em produtos de manufatura e melhorar o controle de qualidade.
- **Amazon SageMaker Ground Truth**: Usa feedback humano para criar conjuntos de dados rotulados. Ao incorporar rótulos verificados por humanos e supervisão humana, o SageMaker Ground Truth ajuda a alinhar mais estreitamente o processo de tomada de decisão da IA aos contextos do mundo real.
- **AWS DeepRacer**: Projetado para ensinar os usuários a treinar modelos de aprendizado por reforço, utilizados para guiar um carro autônomo em pistas virtuais e, eventualmente, em carros físicos.
- **Amazon Lex**: Pode ser usado para criar interfaces de voz integradas a dispositivos IoT e aplicativos móveis, mas sua funcionalidade principal está na construção de chatbots baseados em IA para interações com clientes.

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

### Segurança e Governança

Esses serviços ajudam a proteger dados, monitorar atividades e manter a conformidade com regulamentações.

- **AWS Identity and Access Management (IAM)**: Serviço que permite gerenciar identidades e permissões para acessar recursos da AWS de forma segura. Ele suporta práticas como controle de acesso baseado em funções (RBAC) e políticas detalhadas.
- **AWS Key Management Service (KMS)**: Serviço de gerenciamento de chaves criptográficas para proteger dados confidenciais. Ele pode ser integrado a outros serviços da AWS, como S3 e DynamoDB, para criptografia de dados em repouso.
- **Amazon Macie**: Serviço que usa ML para identificar e proteger dados sensíveis, como informações de identificação pessoal (PII) e documentos confidenciais, em buckets S3. Ele ajuda a mitigar riscos de exposição.
- **AWS PrivateLink**: Permite conectar serviços em diferentes VPCs e à AWS de forma segura, usando a rede interna da AWS, sem expor o tráfego à internet pública.
- **Amazon Inspector**: Serviço automatizado que avalia a segurança de workloads da AWS, como instâncias EC2 e containers. Ele identifica vulnerabilidades e desvios de configuração com base em benchmarks de segurança.
- **AWS Audit Manager**: Ajuda a automatizar o processo de auditoria, coletando evidências para conformidade com regulamentações como GDPR e HIPAA. Ideal para gerenciar auditorias de forma eficiente.
- **AWS Artifact**: Repositório de relatórios de conformidade e contratos da AWS. Ele fornece documentos necessários para demonstrar conformidade com padrões como ISO 27001, SOC 2 e mais.

---

Esses são os principais pontos abordados no resumo da certificação AIF-C01. Para mais detalhes, revise os materiais de estudo e documentação oficial da AWS.

## Links Úteis

- [Página Oficial da Certificação AWS Certified AI Practitioner](https://aws.amazon.com/pt/certification/certified-ai-practitioner/)
- [AWS Skill Builder](https://explore.skillbuilder.aws/learn)
- [Documentação dos Serviços de IA/ML da AWS](https://aws.amazon.com/pt/machine-learning/)

---

## Licença

Este projeto está licenciado sob a [MIT License](../license.txt). Sinta-se à vontade para usar e distribuir este Guia, desde que mantenha os créditos apropriados..

---

### Autor

<a href="https://github.com/klerytondev/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/klerytondev" width="100px;" alt=""/>
 <br />
 <h3><b>Kleryton Souza</b></h3> <a>

Made by Kleryton de Souza 👋🏽 Entre em contato!

[![Twitter Badge](https://img.shields.io/badge/-@SouzaKleryton-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/SouzaKleryton)](https://twitter.com/SouzaKleryton) [![Linkedin Badge](https://img.shields.io/badge/-kleryton-souza?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/kleryton-souza-a1733673/)](https://www.linkedin.com/in/kleryton-souza-a1733673/) 
[![Gmail Badge](https://img.shields.io/badge/kleryton.dev@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:kleryton.dev@gmail.com)](mailto:kleryton.dev@gmail.com)

