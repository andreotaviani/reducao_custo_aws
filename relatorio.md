# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 21/04/2026
Empresa: Abstergo Industries
Responsável: André Otaviani

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por André Otaviani. O objetivo do projeto foi elencar 3 serviços AWS com foco na diminuição de custos imediatos, sem comprometer a disponibilidade e a segurança dos dados.

## Descrição do Projeto

Etapa 1:
Amazon S3 Intelligent-Tiering

Foco: Armazenamento de objetos com otimização automática de custos.

Caso de uso: Implementado para armazenar grandes volumes de dados sem padrão de acesso definido. A classe Intelligent-Tiering ajusta automaticamente os objetos entre camadas de acesso frequente e infrequente, reduzindo custos sem necessidade de configuração manual.

Etapa 2:
Amazon EC2 Spot Instances

Foco: Computação sob demanda com preços reduzidos.

Caso de uso: Utilizado para cargas de trabalho tolerantes a interrupções, como processamento em lote e testes. As instâncias Spot oferecem até 90% de economia em relação às instâncias sob demanda.

Etapa 3:
Amazon Elastic File System (EFS) Infrequent Access

Foco: Sistema de arquivos escalável com custo otimizado.

Caso de uso: Aplicado para dados compartilhados entre múltiplas instâncias EC2, mas que não são acessados constantemente. A classe EFS-IA reduz custos de armazenamento mantendo alta disponibilidade e escalabilidade.

## Conclusão

A implementação das ferramentas na empresa Abstergo Industries tem como esperado:

Redução imediata de custos operacionais

Maior eficiência no uso de recursos de armazenamento e computação

Escalabilidade automática sem necessidade de intervenção manual

Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias AWS que possam otimizar ainda mais os processos da empresa.

## Anexos

Planilhas de custos comparativos antes e depois da implementação

Documentação de configuração dos serviços

Guia de boas práticas AWS para redução de custos

Assinatura do Responsável pelo Projeto:  
André Otaviani
