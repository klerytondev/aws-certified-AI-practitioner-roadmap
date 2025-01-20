## Respostas para o Exame de Certificação AWS Certified AI Practitioner (AIF-C01)

Este documento contém as respostas para as questões do exame de certificação AWS Certified AI Practitioner (AIF-C01).

### Índice

1. [Questão 1](#questão-1)
2. [Questão 2](#questão-2)
3. [Questão 3](#questão-3)
4. [Questão 4](#questão-4)
5. [Questão 5](#questão-5)
6. [Questão 6](#questão-6)
7. [Questão 7](#questão-7)
8. [Questão 8](#questão-8)
9. [Questão 9](#questão-9)
10. [Questão 10](#questão-10)
11. [Questão 11](#questão-11)
12. [Questão 12](#questão-12)
13. [Questão 13](#questão-13)
14. [Questão 14](#questão-14)
15. [Questão 15](#questão-15)
16. [Questão 16](#questão-16)
17. [Questão 17](#questão-17)
18. [Questão 18](#questão-18)
19. [Questão 19](#questão-19)
20. [Questão 20](#questão-20)
21. [Questão 21](#questão-21)
22. [Questão 22](#questão-22)
23. [Questão 23](#questão-23)
24. [Questão 24](#questão-24)
25. [Questão 25](#questão-25)
26. [Questão 26](#questão-26)
27. [Questão 27](#questão-27)
28. [Questão 28](#questão-28)
29. [Questão 29](#questão-29)
30. [Questão 30](#questão-30)
31. [Questão 31](#questão-31)
32. [Questão 32](#questão-32)
33. [Questão 33](#questão-33)
34. [Questão 34](#questão-34)
35. [Questão 35](#questão-35)
36. [Questão 36](#questão-36)
37. [Questão 37](#questão-37)
38. [Questão 38](#questão-38)
39. [Questão 39](#questão-39)
40. [Questão 40](#questão-40)
41. [Questão 41](#questão-41)
42. [Questão 42](#questão-42)
43. [Questão 43](#questão-43)
44. [Questão 44](#questão-44)
45. [Questão 45](#questão-45)
46. [Questão 46](#questão-46)
47. [Questão 47](#questão-47)
48. [Questão 48](#questão-48)
49. [Questão 49](#questão-49)
50. [Questão 50](#questão-50)
51. [Questão 51](#questão-51)
52. [Questão 52](#questão-52)
53. [Questão 53](#questão-53)
54. [Questão 54](#questão-54)
55. [Questão 55](#questão-55)
56. [Questão 56](#questão-56)
57. [Questão 57](#questão-57)
58. [Questão 58](#questão-58)
59. [Questão 59](#questão-59)
60. [Questão 60](#questão-60)
61. [Questão 61](#questão-61)
62. [Questão 62](#questão-62)
63. [Questão 63](#questão-63)
64. [Questão 64](#questão-64)
65. [Questão 65](#questão-65)

---

### Questão 1

**Resposta:** B) Aumentar as épocas

**Resumo:** Aumentar as épocas, ou seja, o número de vezes que o modelo percorre todo o conjunto de dados de treinamento, permite que o modelo aprenda mais com os dados, potencialmente aumentando a precisão. No entanto, um número excessivo de épocas pode levar ao overfitting, onde o modelo se torna muito especializado nos dados de treinamento e tem dificuldades em generalizar para novos dados. Monitorar o overfitting é crucial.

**[Pergunta](readme_perguntas.md#questão-1)**

---

### Questão 2

**Resposta:** B) Duração média da chamada

**Resumo:** A duração média da chamada é a métrica mais relevante, pois uma redução nesse tempo indica que o chatbot está respondendo às perguntas dos clientes de forma eficaz, diminuindo a necessidade de intervenção dos funcionários do call center.

**[Pergunta](readme_perguntas.md#questão-2)**

---

### Questão 3

**Resposta:** D) SageMaker Clarify

**Resumo:** O SageMaker Clarify concentra-se na detecção e mitigação de vieses em conjuntos de dados e modelos de machine learning. Ele fornece ferramentas para avaliar vieses e explicar as previsões do modelo.

**[Pergunta](readme_perguntas.md#questão-3)**

---

### Questão 4

**Resposta:** C) Aumentar o volume de dados de treinamento

**Resumo:** Aumentar o volume de dados de treinamento é a solução mais eficaz para combater o overfitting. Mais dados permitem que o modelo aprenda padrões mais generalizáveis, reduzindo a especialização excessiva nos dados de treinamento.

**[Pergunta](readme_perguntas.md#questão-4)**

---

### Questão 5

**Resposta:** B e E) Amazon Comprehend e Amazon Bedrock

**Resumo:** Tanto o Amazon Comprehend quanto o Amazon Bedrock são adequados para análise de sentimento. O Comprehend é um serviço de PNL com recursos específicos para essa tarefa, enquanto o Bedrock, com seus modelos de linguagem de grande escala, também pode ser usado para análise de sentimento. O Comprehend pode ser uma solução mais direta e econômica para essa necessidade específica.

**[Pergunta](readme_perguntas.md#questão-5)**

---

### Questão 6

**Resposta:** D) Utilização de uma base de conhecimento

**Resumo:** A utilização de uma base de conhecimento é a solução mais eficiente e econômica, pois permite que o modelo acesse as informações relevantes sem a necessidade de enviar grandes quantidades de texto a cada solicitação. Adicionar todos os PDFs como contexto seria caro e ineficiente, enquanto o ajuste fino em todos os documentos seria demorado e caro.

**[Pergunta](readme_perguntas.md#questão-6)**

---

### Questão 7

**Resposta:** C) Engenharia de prompts

**Resumo:** A engenharia de prompts, ou seja, a criação de prompts (instruções) eficazes, é a chave para orientar o modelo a gerar conteúdo alinhado à voz da marca. Instruções detalhadas e contexto relevante no prompt permitem um controle preciso sobre o estilo e o conteúdo gerado.

**[Pergunta](readme_perguntas.md#questão-7)**

---

### Questão 8

**Resposta:** A) Detectar desequilíbrios nos dados

**Resumo:** Detectar desequilíbrios nos dados é crucial para identificar e corrigir vieses potenciais. Avaliar e documentar o comportamento do modelo permite monitorar e mitigar vieses que possam surgir ao longo do tempo. Executar o modelo com frequência, usar ROUGE ou garantir o tempo de inferência não abordam diretamente a questão do viés.

**[Pergunta](readme_perguntas.md#questão-8)**

---

### Questão 9

**Resposta:** B) Bedrock não suporta a implantação direta de modelos personalizados

**Resumo:** O Bedrock não suporta a implantação direta de modelos personalizados. A solução é implantar o modelo em um endpoint do SageMaker e, em seguida, usar esse endpoint em conjunto com os fluxos de trabalho do Bedrock.

**[Pergunta](readme_perguntas.md#questão-9)**

---

### Questão 10

**Resposta:** C) Copiar conteúdo gerado por IA sem atribuição adequada

**Resumo:** Copiar conteúdo gerado por IA sem atribuição adequada constitui plágio, violando os princípios de autoria e originalidade.

**[Pergunta](readme_perguntas.md#questão-10)**

---

### Questão 11

**Resposta:** D) Série TRN com chips AWS Trainium

**Resumo:** A série TRN, com seus chips AWS Trainium, foi projetada especificamente para treinamento de LLMs com alta eficiência energética, minimizando o impacto ambiental.

**[Pergunta](readme_perguntas.md#questão-11)**

---

### Questão 12

**Resposta:** C) Guardrails do Bedrock

**Resumo:** Os guardrails do Bedrock permitem definir restrições sobre a saída do modelo, garantindo a geração de conteúdo apropriado para crianças ao filtrar linguagem e tópicos inadequados.

**[Pergunta](readme_perguntas.md#questão-12)**

---

### Questão 13

**Resposta:** D) SageMaker Canvas

**Resumo:** O SageMaker Canvas é uma solução sem código que permite que analistas de negócios criem modelos de machine learning sem escrever código. É ideal para prever a demanda em um ambiente amigável.

**[Pergunta](readme_perguntas.md#questão-13)**

---

### Questão 14

**Resposta:** B) Viés de amostragem

**Resumo:** Viés de amostragem ocorre quando os dados de treinamento não representam a população de forma justa, levando a resultados tendenciosos. Se o conjunto de dados usado para treinar o modelo contivesse uma representação excessiva de um determinado grupo étnico em relação a incidentes de roubo, isso resultaria na sinalização desproporcional observada.

**[Pergunta](readme_perguntas.md#questão-14)**

---

### Questão 15

**Resposta:** B) Aprendizagem por reforço

**Resumo:** A aprendizagem por reforço é ideal para chatbots que precisam se autoaprimorar. Nessa abordagem, o chatbot aprende por meio de tentativa e erro, recebendo recompensas por respostas positivas e penalidades por respostas negativas.

**[Pergunta](readme_perguntas.md#questão-15)**

---

### Questão 16

**Resposta:** A) Matriz de confusão

**Resumo:** A matriz de confusão é a métrica mais adequada para avaliar a precisão de modelos de classificação, pois detalha os tipos de erros cometidos pelo modelo (verdadeiros positivos, verdadeiros negativos, falsos positivos e falsos negativos).

**[Pergunta](readme_perguntas.md#questão-16)**

---

### Questão 17

**Resposta:** A) APIs de moderação

**Resumo:** APIs de moderação, como o Amazon Rekognition Content Moderation, são a solução mais eficaz. Essas APIs analisam as imagens em tempo real e sinalizam conteúdo inadequado, garantindo uma experiência segura para o usuário.

**[Pergunta](readme_perguntas.md#questão-17)**

---

### Questão 18

**Resposta:** B) Recurso de registro de dados de invocação do Bedrock

**Resumo:** O Bedrock possui um recurso específico para registrar dados de invocação, capturando as entradas e saídas do modelo para cada solicitação.

**[Pergunta](readme_perguntas.md#questão-18)**

---

### Questão 19

**Resposta:** A) SageMaker Batch Transform

**Resumo:** O SageMaker Batch Transform foi projetado para executar inferências em grandes conjuntos de dados em modo batch, processando os dados em massa e armazenando os resultados no S3. É ideal para cenários onde as previsões não precisam ser acessadas imediatamente.

**[Pergunta](readme_perguntas.md#questão-19)**

---

### Questão 20

**Resposta:** A) Embeddings

**Resumo:** Embeddings são representações numéricas densas de palavras, frases ou objetos em um espaço vetorial. Eles capturam o significado, os relacionamentos e o contexto de entidades do mundo real, ajudando os modelos de IA a entender e processar informações textuais.

**[Pergunta](readme_perguntas.md#questão-20)**

---

### Questão 21

**Resposta:** B) Adaptação de domínio por meio de ajuste fino

**Resumo:** A adaptação de domínio por meio de ajuste fino é a solução ideal. Envolve treinar o modelo com dados específicos do domínio em questão (neste caso, artigos científicos), permitindo que ele compreenda e responda com precisão a termos científicos complexos.

**[Pergunta](readme_perguntas.md#questão-21)**

---

### Questão 22

**Resposta:** A) Diminuir o valor da temperatura

**Resumo:** Diminuir o valor da temperatura reduz a aleatoriedade nas respostas do modelo, tornando as saídas mais determinísticas e consistentes para o mesmo prompt de entrada.

**[Pergunta](readme_perguntas.md#questão-22)**

---

### Questão 23

**Resposta:** A) Criação de uma função de serviço separada por equipe

**Resumo:** A criação de uma função de serviço separada por equipe, com permissões restritas aos dados de seus clientes, garante o controle de acesso adequado e alinha-se ao princípio do privilégio mínimo.

**[Pergunta](readme_perguntas.md#questão-23)**

---

### Questão 24

**Resposta:** C) Guardrails do Bedrock e alarmes do CloudWatch

**Resumo:** Os guardrails do Bedrock podem filtrar informações confidenciais das respostas do modelo, enquanto os alarmes do CloudWatch podem notificar os administradores sobre quaisquer violações de política.

**[Pergunta](readme_perguntas.md#questão-24)**

---

### Questão 25

**Resposta:** A) Amazon Textract

**Resumo:** O Amazon Textract é um serviço que extrai texto, incluindo texto manuscrito, de documentos digitalizados, como PDFs. É a escolha ideal para converter currículos em texto sem formatação.

**[Pergunta](readme_perguntas.md#questão-25)**

---

### Questão 26

**Resposta:** B) Adicionar uma descrição de função no prompt

**Resumo:** Adicionar uma descrição de função no prompt é a maneira mais simples e eficaz de orientar o modelo a adaptar seu estilo de resposta à idade do usuário.

**[Pergunta](readme_perguntas.md#questão-26)**

---

### Questão 27

**Resposta:** B) Testar o modelo em um conjunto de dados de referência rotulado

**Resumo:** Testar o modelo em um conjunto de dados de referência rotulado é a abordagem padrão para avaliar a precisão de modelos de classificação de imagens.

**[Pergunta](readme_perguntas.md#questão-27)**

---

### Questão 28

**Resposta:** A) Avaliar a justiça do modelo e garantir dados de treinamento representativos

**Resumo:** Avaliar a justiça do modelo e garantir dados de treinamento representativos e equilibrados são cruciais para uma implementação responsável, minimizando vieses e danos potenciais.

**[Pergunta](readme_perguntas.md#questão-28)**

---

### Questão 29

**Resposta:** C) Análise exploratória de dados (EDA)

**Resumo:** A análise exploratória de dados (EDA) envolve a análise de dados para entender sua distribuição, correlações e padrões. As ações descritas na pergunta se encaixam perfeitamente nessa fase.

**[Pergunta](readme_perguntas.md#questão-29)**

---

### Questão 30

**Resposta:** B) Modelos baseados em BERT

**Resumo:** Modelos baseados em BERT (Bidirectional Encoder Representations from Transformers) são ideais para prever palavras ausentes em frases, analisando o contexto antes e depois da lacuna.

**[Pergunta](readme_perguntas.md#questão-30)**

---

### Questão 31

**Resposta:** C) Amazon QuickSight com QuickSight Q

**Resumo:** O Amazon QuickSight com QuickSight Q é a solução ideal. O QuickSight é um serviço de business intelligence que permite criar visualizações, e o QuickSight Q, com sua capacidade de consulta em linguagem natural, automatiza a geração de gráficos com base em dados.

**[Pergunta](readme_perguntas.md#questão-31)**

---

### Questão 32

**Resposta:** C) Associar as mensagens do usuário às suas intenções correspondentes

**Resumo:** Para a detecção de intenções, é fundamental associar as mensagens do usuário às suas intenções correspondentes, fornecendo ao modelo os dados necessários para aprender os padrões de linguagem que indicam a intenção do usuário.

**[Pergunta](readme_perguntas.md#questão-32)**

---

### Questão 33

**Resposta:** B) Reduzir o número de tokens no prompt

**Resumo:** Reduzir o número de tokens no prompt, ou seja, usar menos exemplos ou simplificar a entrada, diminui a quantidade de dados processados a cada invocação, levando a custos mensais mais baixos.

**[Pergunta](readme_perguntas.md#questão-33)**

---

### Questão 34

**Resposta:** B) Alucinação em IA

**Resumo:** Alucinação em IA refere-se à geração de informações que parecem plausíveis, mas não têm base nos dados de treinamento, resultando em conteúdo fabricado ou incorreto.

**[Pergunta](readme_perguntas.md#questão-34)**

---

### Questão 35

**Resposta:** A) Reconstruir o modelo sem dados confidenciais

**Resumo:** A única maneira de garantir que o modelo não use dados confidenciais durante a inferência é reconstruí-lo sem esses dados no conjunto de dados de treinamento. As outras opções protegem os dados, mas não impedem que o modelo os utilize se estiverem presentes nos dados de treinamento.

**[Pergunta](readme_perguntas.md#questão-35)**

---

### Questão 36

**Resposta:** A) Métrica BLEU

**Resumo:** A métrica BLEU é amplamente utilizada para avaliar a qualidade de traduções automáticas, comparando a tradução gerada com uma ou mais traduções de referência.

**[Pergunta](readme_perguntas.md#questão-36)**

---

### Questão 37

**Resposta:** B) Agentes do Bedrock

**Resumo:** A principal vantagem dos agentes do Bedrock é a capacidade de automatizar tarefas repetitivas e orquestrar fluxos de trabalho, levando a tempos de resposta mais rápidos e eficientes no suporte ao cliente.

**[Pergunta](readme_perguntas.md#questão-37)**

---

### Questão 38

**Resposta:** B) Pré-treinamento contínuo

**Resumo:** O pré-treinamento contínuo permite que o modelo continue aprendendo com novos dados, o que pode levar a uma maior precisão e capacidade de adaptação a diferentes tarefas.

**[Pergunta](readme_perguntas.md#questão-38)**

---

### Questão 39

**Resposta:** A) Tokens

**Resumo:** Tokens são as unidades básicas de texto que os modelos de IA generativa processam, podendo ser palavras, subpalavras ou caracteres.

**[Pergunta](readme_perguntas.md#questão-39)**

---

### Questão 40

**Resposta:** A) Número de tokens processados durante a inferência

**Resumo:** O número de tokens processados durante a inferência é o principal fator de custo, pois os modelos de linguagem geralmente cobram com base na quantidade de texto processado.

**[Pergunta](readme_perguntas.md#questão-40)**

---

### Questão 41

**Resposta:** C) Criar um endpoint VPC para o S3

**Resumo:** Criar um endpoint VPC para o S3 garante um fluxo de dados seguro e eficiente entre os notebooks do SageMaker Studio e o S3, mantendo o tráfego de dados dentro da rede da AWS.

**[Pergunta](readme_perguntas.md#questão-41)**

---

### Questão 42

**Resposta:** A) Amazon S3

**Resumo:** O Amazon S3 é a solução mais adequada para armazenar e gerenciar conjuntos de dados, incluindo aqueles usados para validação de modelos.

**[Pergunta](readme_perguntas.md#questão-42)**

---

### Questão 43

**Resposta:** A) Amazon Transcribe

**Resumo:** O Amazon Transcribe é um serviço da AWS que pode ser usado para transcrever áudio em texto.

**[Pergunta](readme_perguntas.md#questão-43)**

---

### Questão 44

**Resposta:** A) Avaliar e mitigar vieses nos dados de treinamento

**Resumo:** Avaliar e mitigar vieses nos dados de treinamento é essencial para garantir que um modelo de IA não esteja enviesado.

**[Pergunta](readme_perguntas.md#questão-44)**

---

### Questão 45

**Resposta:** B) Usar técnicas de data augmentation

**Resumo:** Usar técnicas de data augmentation pode aumentar a quantidade de dados de treinamento disponíveis, melhorando a robustez do modelo.

**[Pergunta](readme_perguntas.md#questão-45)**

---

### Questão 46

**Resposta:** A) Amazon Translate

**Resumo:** O Amazon Translate é um serviço da AWS que pode ser usado para traduzir texto entre diferentes idiomas.

**[Pergunta](readme_perguntas.md#questão-46)**

---

### Questão 47

**Resposta:** A) Testar o modelo com dados de teste variados e representativos

**Resumo:** Testar o modelo com dados de teste variados e representativos garante que ele seja robusto a diferentes tipos de entradas.

**[Pergunta](readme_perguntas.md#questão-47)**

---

### Questão 48

**Resposta:** A) Usar validação cruzada durante o treinamento

**Resumo:** Usar validação cruzada durante o treinamento pode melhorar a generalização de um modelo de IA.

**[Pergunta](readme_perguntas.md#questão-48)**

---

### Questão 49

**Resposta:** A) Amazon Comprehend

**Resumo:** O Amazon Comprehend é um serviço da AWS que pode ser usado para analisar sentimentos em textos.

**[Pergunta](readme_perguntas.md#questão-49)**

---

### Questão 50

**Resposta:** A) Otimizar o modelo para inferência

**Resumo:** Otimizar o modelo para inferência garante que ele seja eficiente em termos de tempo de inferência.

**[Pergunta](readme_perguntas.md#questão-50)**

---

### Questão 51

**Resposta:** A) Usar técnicas de oversampling ou undersampling

**Resumo:** Usar técnicas de oversampling ou undersampling pode ajudar a lidar com dados desbalanceados em um problema de classificação.

**[Pergunta](readme_perguntas.md#questão-51)**

---

### Questão 52

**Resposta:** A) Amazon Lex

**Resumo:** O Amazon Lex é um serviço da AWS que pode ser usado para criar chatbots.

**[Pergunta](readme_perguntas.md#questão-52)**

---

### Questão 53

**Resposta:** A) Usar serviços de nuvem como o Amazon SageMaker

**Resumo:** Usar serviços de nuvem como o Amazon SageMaker garante que um modelo de IA seja escalável.

**[Pergunta](readme_perguntas.md#questão-53)**

---

### Questão 54

**Resposta:** A) Ajustar os hiperparâmetros do modelo

**Resumo:** Ajustar os hiperparâmetros do modelo pode melhorar a precisão de um modelo de classificação.

**[Pergunta](readme_perguntas.md#questão-54)**

---

### Questão 55

**Resposta:** A) Amazon Polly

**Resumo:** O Amazon Polly é um serviço da AWS que pode ser usado para sintetizar voz a partir de texto.

**[Pergunta](readme_perguntas.md#questão-55)**

---

### Questão 56

**Resposta:** A) Implementar medidas de segurança como criptografia e controle de acesso

**Resumo:** Implementar medidas de segurança como criptografia e controle de acesso garante que um modelo de IA seja seguro.

**[Pergunta](readme_perguntas.md#questão-56)**

---

### Questão 57

**Resposta:** A) Usar técnicas de explicabilidade como LIME ou SHAP

**Resumo:** Usar técnicas de explicabilidade como LIME ou SHAP pode melhorar a interpretabilidade de um modelo de IA.

**[Pergunta](readme_perguntas.md#questão-57)**

---

### Questão 58

**Resposta:** A) Amazon SageMaker Canvas

**Resumo:** O Amazon SageMaker Canvas é um serviço da AWS que permite criar modelos de machine learning sem precisar escrever código.

**[Pergunta](readme_perguntas.md#questão-58)**

---

### Questão 59

**Resposta:** A) Otimizar o modelo para eficiência de recursos

**Resumo:** Otimizar o modelo para eficiência de recursos garante que ele seja eficiente em termos de uso de recursos.

**[Pergunta](readme_perguntas.md#questão-59)**

---

### Questão 60

**Resposta:** A) Testar o modelo com dados de teste variados e representativos

**Resumo:** Testar o modelo com dados de teste variados e representativos pode melhorar a robustez de um modelo de IA.

**[Pergunta](readme_perguntas.md#questão-60)**

---

### Questão 61

**Resposta:** A) Amazon Lookout for Metrics

**Resumo:** O Amazon Lookout for Metrics é um serviço da AWS que pode ser usado para detectar anomalias em dados.

**[Pergunta](readme_perguntas.md#questão-61)**

---

### Questão 62

**Resposta:** A) Implementar um pipeline de atualização contínua de dados

**Resumo:** Implementar um pipeline de atualização contínua de dados garante que um modelo de IA seja atualizado com novos dados.

**[Pergunta](readme_perguntas.md#questão-62)**

---

### Questão 63

**Resposta:** A) Ajustar os hiperparâmetros do modelo

**Resumo:** Ajustar os hiperparâmetros do modelo pode melhorar a precisão de um modelo de regressão.

**[Pergunta](readme_perguntas.md#questão-63)**

---

### Questão 64

**Resposta:** A) Amazon Personalize

**Resumo:** O Amazon Personalize é um serviço da AWS que pode ser usado para criar modelos de recomendação.

**[Pergunta](readme_perguntas.md#questão-64)**

---

### Questão 65

**Resposta:** A) Otimizar o modelo para eficiência de custo

**Resumo:** Otimizar o modelo para eficiência de custo garante que ele seja eficiente em termos de custo.

**[Pergunta](readme_perguntas.md#questão-65)**

## Links Úteis

- [Página Oficial da Certificação AWS Certified AI Practitioner](https://aws.amazon.com/pt/certification/certified-ai-practitioner/)
- [AWS Skill Builder](https://explore.skillbuilder.aws/learn)
- [Documentação dos Serviços de IA/ML da AWS](https://aws.amazon.com/pt/machine-learning/)

## Licença

Este projeto está licenciado sob a [MIT License](../license.txt). Sinta-se à vontade para usar e distribuir este Guia, desde que mantenha os créditos apropriados..

---

### Autor
---
<a href="https://github.com/klerytondev/">
 <img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/klerytondev" width="100px;" alt=""/>
 <br />
 <h3><b>Kleryton Souza</b></h3> <a>

Made by Kleryton de Souza 👋🏽 Entre em contato!

[![Twitter Badge](https://img.shields.io/badge/-@SouzaKleryton-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/SouzaKleryton)](https://twitter.com/SouzaKleryton) [![Linkedin Badge](https://img.shields.io/badge/-kleryton-souza?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/kleryton-souza-a1733673/)](https://www.linkedin.com/in/kleryton-souza-a1733673/) 
[![Gmail Badge](https://img.shields.io/badge/kleryton.dev@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:kleryton.dev@gmail.com)](mailto:kleryton.dev@gmail.com)