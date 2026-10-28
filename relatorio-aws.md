# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 15/10/2026
**Empresa:** Abstergo Industries
**Responsável:** Rian Jr.

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Rian Jr. O objetivo do projeto foi elencar 3 serviços AWS com a finalidade de realizar a diminuição de custos imediatos, seguindo uma sequência lógica: primeiro enxergar o gasto, depois dimensionar corretamente a computação e, por fim, reduzir o custo de armazenamento.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1

- **Nome da ferramenta:** AWS Budgets + AWS Cost Explorer
- **Foco da ferramenta:** Visibilidade e controle de custos
- **Descrição de caso de uso:** O Cost Explorer permite analisar o gasto por serviço, conta e tag, identificando onde está o desperdício. O AWS Budgets define limites mensais por projeto ou departamento e envia alertas (e-mail ou SNS) quando o gasto real ou previsto se aproxima do limite. Assim, a Abstergo Industries evita surpresas na fatura e prioriza as próximas ações de economia com base em dados.

### Etapa 2

- **Nome da ferramenta:** AWS Compute Optimizer (com Savings Plans)
- **Foco da ferramenta:** Dimensionamento correto (rightsizing) da computação
- **Descrição de caso de uso:** O Compute Optimizer analisa o uso real de CPU e memória das instâncias EC2 e recomenda tipos menores ou mais adequados para as cargas superdimensionadas. Após ajustar as instâncias, o consumo estável restante pode ser coberto por Savings Plans, que oferecem desconto em troca de compromisso de uso por 1 ou 3 anos, reduzindo o custo em relação ao preço sob demanda.

### Etapa 3

- **Nome da ferramenta:** Amazon S3 Intelligent-Tiering e Lifecycle Policies
- **Foco da ferramenta:** Otimização de custos de armazenamento
- **Descrição de caso de uso:** O S3 Intelligent-Tiering move automaticamente os objetos entre camadas de acesso frequente e infrequente conforme o padrão de uso, sem perda de desempenho. Já as Lifecycle Policies arquivam dados antigos em classes mais baratas (como S3 Glacier) ou os excluem após o prazo de retenção. É indicado para logs, backups e documentos históricos da empresa, que raramente são acessados.

## Conclusão

A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado **maior visibilidade dos gastos, eliminação de recursos superdimensionados e redução do custo de armazenamento de dados pouco acessados**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Capturas de tela do Cost Explorer e dos alertas configurados no AWS Budgets
- Relatório de recomendações do AWS Compute Optimizer
- Configuração das Lifecycle Policies dos buckets S3
- Planilha de estimativa de economia (antes e depois)

---

**Assinatura do Responsável pelo Projeto:**

[Rian Jr.]
