# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por [Seu Nome Aqui]. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimização da infraestrutura em nuvem.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- **Amazon S3 com Intelligent-Tiering**
- **Otimização de custos de armazenamento de objetos**
- **Descrição de caso de uso:** Armazenamento de grandes arquivos de vídeo (60-80GB) onde o padrão de acesso não é conhecido previamente. A ferramenta move automaticamente os dados para camadas de acesso mais baratas quando não são utilizados, gerando economia imediata.

Etapa 2: 
- **DynamoDB Accelerator (DAX)**
- **Performance e redução de carga em banco de dados NoSQL**
- **Descrição de caso de uso:** Adição de uma camada de cache no DynamoDB para otimizar o tempo de consultas repetitivas. Isso permite reduzir a necessidade de provisionar alta capacidade de leitura na tabela principal, diminuindo os custos operacionais.

Etapa 3: 
- **Amazon RDS (Relational Database Service)**
- **Automação de manutenção e alta disponibilidade**
- **Descrição de caso de uso:** Hospedagem de bancos de dados PostgreSQL e MySQL utilizando recursos de patches automatizados, redundância e failover. O serviço gerenciado reduz custos com mão de obra operacional e infraestrutura física de recuperação de desastres.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução drástica de gastos com armazenamento subutilizado e a diminuição da carga operacional sobre as equipes de banco de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.
