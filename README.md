# AWS-stepfunctions-overview
Breve overview do serviço AWS Step Functions da Amazon.
---
O AWS Step Functions é uma solução de orquestração serverless para aplicações modernas, que ajuda desenvolvedores a gerenciar fluxos de trabalho complexos e tarefas distribuídas. Principais características:

1. Simplifica o desenvolvimento ao eliminar a necessidade de código personalizado para agendamento, dependências e tratamento de erros.
2. Gerencia centralmente fluxos de trabalho, dividindo-os em etapas, adicionando lógica de fluxo e rastreando entradas e saídas entre as etapas.
3. Oferece fluxos de trabalho visuais para melhor visibilidade e verificação rápida da operação correta das aplicações.
4. Permite construir e modificar aplicações rapidamente, sem necessidade de personalizar código.
5. Gerencia a lógica da aplicação e implementa primitivas básicas, removendo código de acesso de microsserviços e funções.
6. Melhora a resiliência cuidando de estados, checkpoints, tratamento de erros e reinicializações.
7. Torna as aplicações mais rápidas de escrever e mais fáceis de manter.

Assim, o AWS Step Functions visa acelerar e simplificar o processo de desenvolvimento de aplicações distribuídas, oferecendo uma solução robusta para gerenciamento de fluxos de trabalho complexos.

Orquestração sem servidor (serverless) para aplicações modernas significa:
---
1. Gerenciamento automático de infraestrutura: A Amazon gerencia toda a infraestrutura subjacente, eliminando a necessidade de provisionar, manter ou escalar servidores.
2. Escalabilidade automática: O serviço escala automaticamente para lidar com a carga de trabalho, sem intervenção manual.
3. Pagamento por uso: Os custos são baseados apenas nos recursos realmente utilizados, sem necessidade de pagar por capacidade ociosa.
4. Foco no código: Desenvolvedores podem se concentrar na lógica da aplicação, em vez de se preocupar com a gestão de servidores.
5. Coordenação de componentes: Permite coordenar diferentes partes de uma aplicação distribuída de forma eficiente.
6. Abstração de complexidade: Simplifica o gerenciamento de fluxos de trabalho complexos, ocultando detalhes de implementação de baixo nível.
7. Integração com outros serviços: Facilita a integração com outros serviços AWS e componentes da aplicação.
8. Alta disponibilidade: Oferece alta disponibilidade e tolerância a falhas sem configuração adicional.

Esta abordagem permite que as empresas construam e operem aplicações de forma mais ágil, eficiente e econômica, focando nos resultados de negócios em vez da gestão de infraestrutura.

Benefícios do Step Functions
---
### Integração rápida

[Comece a criar rapidamente usando o Workflow Studio, uma interface simples com o recurso de arrastar e soltar para expressar lógicas de negócios complexas.](https://docs.aws.amazon.com/step-functions/latest/dg/tutorial-workflow-studio-using.html)

### Automação simples

[Automatize fluxos de trabalho em mais de 220 produtos da AWS sem a necessidade de manutenção do código.](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-service-integrations.html)

### Processar dados sob demanda

[Use código para processar dados sob demanda com fluxos de trabalho paralelos de grande escala](https://docs.aws.amazon.com/step-functions/latest/dg/concepts-orchestrate-large-scale-parallel-workloads.html)

### Visualização da arquitetura orientada por eventos

[Visualize e desenvolva fluxos de trabalho flexíveis para arquiteturas orientadas a eventos.](https://aws.amazon.com/blogs/containers/run-event-driven-workflows-with-amazon-eks-and-aws-step-functions/)


Como funciona
---
O Step Functions é um serviço de fluxo de trabalho visual que ajuda os desenvolvedores a usar os produtos da AWS para desenvolver aplicações distribuídas, automatizar processos, orquestrar microsserviços e criar pipelines de dados e machine learning (ML).

![[AWS Step Functions Workflow.png]](https://github.com/leoawen/AWS-stepfunctions-overview/blob/main/GitHub_assets/AWS%20Step%20Functions%20Workflow.png)

👉 [Página Oficial do AWS Step Function](https://aws.amazon.com/pt/step-functions/)





