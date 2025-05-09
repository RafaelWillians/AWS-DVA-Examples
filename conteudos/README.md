# AWS Developer Associate - Lista de conteúdos para estudos

Abaixo há os links para o site da documentação da AWS. 

## [Elastic Beanstalk](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/Welcome.html)

#### [Plataformas suportadas](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/concepts.platforms.html)
* Ruby, Python, PHP, Tomcat, Node.js

#### Tipos de Ambientes
* [Web](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/concepts-webserver.html)
* [Worker](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/concepts-worker.html)

#### [Tipos de Ambiente Web](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/using-features-managing-env-types.html)
* Instância única
* Com Load Balancer

#### [Políticas de Deploy](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/using-features.rolling-version-deploy.html)
* All at once
* Rolling
* Rolling with additional batch
* Immutable
* Traffic splitting

[Outras implantações](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/using-features.CNAMESwap.html)
* In-place
* Blue/Green

#### Arquivos de configuração
* [.ebextensions](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/ebextensions.html)
* .config
* [Manifest do ambiente (arquivo env.yml)](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/environment-cfg-manifest.html)

#### [EB CLI - comandos](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/eb-cli3-getting-started.html)
* eb init
* eb create
* eb clone
* eb deploy
* eb logs
* eb events
* eb health
* eb terminate
* eb abort
* eb status

#### [Usar imagem customizada (AMI) no ambiente EB](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/using-features.customenv.html)

#### [Configurar RDS dentro ou fora do ambiente EB](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/AWSHowTo.RDS.html)

## [Elastic Container Service (ECS)](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/Welcome.html)

#### [Fargate](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/AWS_Fargate.html)

#### Função (Role) de execução e Função (Role) de Tarefa
* [Role de execução](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task_execution_IAM_role.html)
* [Role de tarefa](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/task-iam-roles.html)

#### Provedores de capacidade
* [EC2(Grupo de Auto Scaling)](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/asg-capacity-providers.html)
* [Fargate](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/fargate-capacity-providers.html)
* [Fargate Spot](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/fargate-capacity-providers.html)

#### Criação de cluster
* [Tipo de inicialização EC2](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/create-ec2-cluster-console-v2.html)
* [Tipo de inicialização Fargate](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/create-cluster-console-v2.html)

#### [Ciclo de vida de Tarefa](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/task-lifecycle-explanation.html)

* Provisioning
* Pending
* Activating
* Running
* Deactivating
* Stopping
* Deprovisioning
* Stopped
* Excluída

#### [Port Mapping](https://docs.aws.amazon.com/AmazonECS/latest/APIReference/API_PortMapping.html)

#### [Exemplo de Task Definitions em JSON](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/example_task_definitions.html)

#### [ECS Exec](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/ecs-exec.html)

#### [Configuração de Logs](https://docs.aws.amazon.com/AmazonECS/latest/APIReference/API_LogConfiguration.html)

#### [ECS Service Connect](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/service-connect.html)

#### [AMIs otimizadas para ECS](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-optimized_AMI.html)

* [ECS Bottlerocket](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-bottlerocket.html)

#### [ECS Anywhere](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/ecs-anywhere.html)

## [ECR](https://docs.aws.amazon.com/AmazonECR/latest/userguide/what-is-ecr.html)
* [Replicação](https://docs.aws.amazon.com/AmazonECR/latest/userguide/replication.html)

## [EKS](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)
* [Add Ons](https://docs.aws.amazon.com/eks/latest/userguide/eks-add-ons.html)
* [EKS Connector](https://docs.aws.amazon.com/pt_br/eks/latest/userguide/eks-connector.html)
* [EKS CTL](https://docs.aws.amazon.com/pt_br/eks/latest/userguide/getting-started-eksctl.html)
* [EKS Distro](https://docs.aws.amazon.com/pt_br/eks/latest/userguide/eks-deployment-options.html)
* [EKS Anywhere](https://anywhere.eks.amazonaws.com)
* [AWS Distro for Open Telemetry (ADOT)](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/Container-Insights-EKS-otel.html)
* [Instrumentação do Open Telemetry](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-services-adot.html)
* [Traces](https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/performance-engineering-aws/tracing.html)
* [Spans](https://docs.aws.amazon.com/pt_br/xray/latest/api/API_Span.html)

## [Amazon Managed Service for Prometheus](https://docs.aws.amazon.com/pt_br/prometheus/latest/userguide/what-is-Amazon-Managed-Service-Prometheus.html)

## [Amazon Managed Service for Grafana](https://docs.aws.amazon.com/pt_br/grafana/latest/userguide/what-is-Amazon-Managed-Service-Grafana.html)

#### [Fargate](https://aws.amazon.com/pt/fargate/)
* [Tarefas do Fargate](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/getting-started-fargate.html)
* [Tamanhos de Tarefas](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/capacity-tasksize.html)
* [Comparativo Fargate x Lambda](https://docs.aws.amazon.com/pt_br/decision-guides/latest/fargate-or-lambda/fargate-or-lambda.html)

## [X-Ray](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/aws-xray.html)

* [Conceitos](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Instrumentação](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-instrumenting-your-app.html)
* [Daemon](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-daemon.html)
* [Gráficos do Serviço](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Segmentos](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Subsegmentos](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Traces](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Amostragem](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Cabeçalho de rastreamento (Trace Header)](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Expressões de filtro](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Grupos](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Anotações e metadados](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Exceções](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-concepts.html)
* [Integração com serviços AWS](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/xray-services.html)
* [Linguagens suportadas](https://docs.aws.amazon.com/pt_br/xray/latest/devguide/aws-xray-interface-sdk.html)

## [AWS Certificate Manager (ACM)](https://docs.aws.amazon.com/pt_br/acm/latest/userguide/acm-overview.html)
* [SSL Termination](https://aws.amazon.com/blogs/aws/elastic-load-balancer-support-for-ssl-termination/)

## [Route 53](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/Welcome.html)
* [Casos de uso](https://community.aws/content/2iXNEg3a1vS6fIGhgDtqVPYzruA/what-is-aws-route-53-and-how-does-it-work)
* [Zonas Hospedadas](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/hosted-zones-working-with.html)
* [Record Sets](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/rrsets-working-with.html)
* [Fluxo de tráfego](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/traffic-flow.html)
* [Políticas de roteamento](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy.html)
  * [Simples](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-simple.html)
  * [Ponderado](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-weighted.html)
  * [Failover](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-failover.html)
  * [Geolocalização](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-geo.html)
  * [Geoproximidade](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-geoproximity.html)
  * [Multi-valor](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-multivalue.html)
  * [Latência](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/routing-policy-latency.html)
* [Verificação de integridade](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/welcome-health-checks.html)
* [Resolver](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/resolver.html)
* [DNSSEC](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/domain-configure-dnssec.html)
* [Zonal-Shift](https://docs.aws.amazon.com/pt_br/r53recovery/latest/dg/arc-zonal-shift.how-it-works.html)
* [Alias](https://docs.aws.amazon.com/pt_br/Route53/latest/DeveloperGuide/resource-record-sets-choosing-alias-non-alias.html)

## [KMS](https://docs.aws.amazon.com/pt_br/kms/latest/developerguide/overview.html)
* [Comandos CLI](https://docs.aws.amazon.com/pt_br/cli/v1/userguide/cli_kms_code_examples.html)
* [Chaves](https://docs.aws.amazon.com/pt_br/kms/latest/developerguide/concepts.html)
  * [Chaves gerenciadas pela AWS](https://docs.aws.amazon.com/pt_br/kms/latest/developerguide/concepts.html#aws-managed-cmk)
  * [Chaves gerenciadas pelo cliente - CMK (Customer Managed Keys)](https://docs.aws.amazon.com/pt_br/kms/latest/developerguide/concepts.html#customer-cmk)

## [Cognito](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/what-is-amazon-cognito.html)
* [O que é IdP?](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles_providers.html)
* [OAuth 2](https://auth0.com/pt/intro-to-iam/what-is-oauth-2)
* [Autenticação Cliente-Servidor](https://pt.wikipedia.org/wiki/Modelo_cliente–servidor)
* [Roles OAuth2](https://developers.procore.com/documentation/oauth-roles)
* [JWT](https://auth0.com/docs/secure/tokens/json-web-tokens)
* [JWK](https://auth-wiki.logto.io/pt-br/jwk)
* [Grupos de Usuários (User Pools)](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-user-pools.html)
  * [Clientes de Aplicação](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/user-pool-settings-client-apps.html)
  * [Política de senhas](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/aws-properties-cognito-userpool-passwordpolicy.html)
  * [Atributos do usuário](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/user-pool-settings-attributes.html)
  * [Segurança Avançada](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-user-pool-settings-threat-protection.html)
  * [Configurações de Email](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/user-pool-email.html)
  * [UI Hospedada](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-user-pools-managed-login.html)
  * [Triggers com Lambda](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-user-pools-working-with-lambda-triggers.html)
  * [MFA](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/user-pool-settings-mfa.html)
* [Bancos/Grupos de Identidades (Identity Pools)](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-identity.html)
* [Cognito Sync](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-sync.html)
* [Multi-Tenancy](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/multi-tenant-application-best-practices.html)
* [Modelos de autenticação](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/authentication-flows-public-server-side.html)
* [Integração da autenticação do Cognito em apps web e mobile](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/cognito-integrate-apps.html)
* [AWS JWT Verify](https://docs.aws.amazon.com/pt_br/cognito/latest/developerguide/amazon-cognito-user-pools-using-tokens-verifying-a-jwt.html)

## [SNS](https://docs.aws.amazon.com/pt_br/sns/latest/dg/welcome.html)
* [Pub/Sub](https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/modernization-integrating-microservices/pub-sub.html)
* [Origens](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-event-sources-and-destinations.html)
* [Destinos](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-event-sources-and-destinations.html)
* [Tópicos](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-create-topic.html)
* [Mensagens](https://docs.aws.amazon.com/pt_br/sns/latest/dg/message-delivery.html)
* [Assinaturas](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-create-subscribe-endpoint-to-topic.html)
* [Política de filtragem](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-message-filtering.html)
* [Proteção de dados de mensagens](https://docs.aws.amazon.com/pt_br/sns/latest/dg/message-data-protection.html)
* [Entrega de mensagens brutas](https://docs.aws.amazon.com/pt_br/sns/latest/dg/message-delivery.html)
* [Política de entrega](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-message-delivery-retries.html)
* Fila de Mensagens Mortas (Dead-Letter Queue)
* Aplicação como Assinante

## SQS
* Envio de mensagens grandes
* Fila Padrão
* Fila FIFO
* ABAC
* Política de Acesso
* Metadados de mensagens
* Tempo limite de visibilidade
* Filas em atraso
* Timers de mensagens
* Filas temporárias
* Busca curta e busca longa

## Kinesis
* Kinesis Data Streams
* EFO
* KPL
* KCL
* Kinesis Data Firehose
* Kinesis Video Streams
* Kinesis Data Analytics (Amazon Managed Service for Apache Flink)

## Systems Manager - Parameter Store
* Casos de Uso
* Políticas de parâmeros
* Hierarquia de CLI

## Secrets Manager
* Casos de Uso
* Rotação automática
* CLI

## DynamoDB
* Tabelas
* Consistência de leituras
* Partições
* Chaves primárias
  * Simples
  * Composta
* Query
* Scan
* Capacidade Provisionada
* Capacidade Sob-demanda
* Calcular leituras e escritas (RCU e WCU)
* Tabelas Globais
* Transações
* Time-to-Live (TTL)
* DynamoDB Streams
* Erros comuns
* Índices
  * Local Secondary Indexes (LSI)
  * Global Secondary Indexes (GSI)
* DynamoDB Accelerator (DAX)

## EC2
* Cloud Init
* Dados de usuário (UserData)
* Metadados
* Tipos de instâncias
* Famílias de instâncias
* Processadores
* Instâncias burstable
* Verificações de origem e destino
* Logs do sistema
* Grupos de posicionamento
  * Cluster
  * Partição
  * Distribuição (Spread)
* EC2 Connect
* Amazon Linux
* Tamanhos de instâncias
* Perfis de instâncias
* Ciclo de vida de instâncias
* Screenshot do console da instância
* Hostnames
* Nome de usuário padrão

## IAM
* Componentes principais
  * Usuários
  * Grupos
  * Políticas
  * Funções (ou Perfis ou Roles) 
* Tipos de políticas
* Estrutura de políticas
* Políticas de senhas
* Chaves de acesso
* MFA
* Credenciais de segurança temporárias
* Funções entre-contas (Cross-account roles)
* IAM Security Token Service (STS)
* Federação de Identidade
* AssumeRoleWithWebIdentity

## CloudTrail
* Histórico de eventos
* Trilhas
* CloudTrail para CloudWatch
* Gerenciamento e Eventos de dados

## CloudWatch
* Conceitos de Observabilidade
* Logs
* Grupos de Logs
* Log Streams
* Eventos de Logs
* Log Insights
* Campos descobertos
* Métricas
* Disponibilidade dos dados
* Métricas no nível de host
* CloudWatch Agent
* Coleta de Logs

## EventBridge
* Componentes principais
* Eventos
* Expressões de agendamento
* Regras
* Configurar Entrada
* Registro de Schema
* Padrões de Eventos
* Origens de Eventos de Parceiros

## CloudFormation
* Componentes de um Template
* Formatos de Templates
* Quick Starts
* Estados das Pilhas
* Atualizações de Pilhas
* Políticas de Pilhas
* Pilhas *Nested
* Rollbacks
* Detecção de Desvios
* ChangeSets
* CDK
* Pseudo-parâmetros
* Atributos de Recursos
* Funções Intrínsecas
* Condições de Espera
* IaC Generator
* Helper Scripts
* Init
* CFN-Hup
* Recursos customizados
* CloudFormation Registry
* Prevent Stack Updates

## SAM
* Comparativo SAM x CloudFormation
* Comandos CLI

## Conceitos de CI/CD
* Continuous Integration (CI)
* Continuous Delivery (CD)
* Continuous Deployment (CD)

## CodeCommit
* Características

## Docker
* Dockerfile
* Comandos Docker

## CodeBuild
* Fluxo de trabalho
* Ambientes de build
* Buildspec.yml
* Casos de uso

## CodeDeploy
* Componentes principais
* Tipos de implantações
  * In-Place
  * Blue/Green
* Appspec.yml
* Lifecycle hooks
* Agent e Service Roles

## CodePipeline
* Componentes principais
* Actions
* Exemplos
* Casos de Uso

## RDS
* Criptografia
* Backup
* Restaurar backup
* Grupos de subredes
* Multi-AZ
* Réplicas de leitura
* Multi-AZ x Réplicas de Leitura
* Instância do RDS
* RDS Performance Insights
* RDS Custom
* RDS Proxy
* Leituras e escritas otimizadas
* Autenticação por IAM
* Autenticação Kerberos
* Integração do RDS com Secrets Manager
* Master User Account
* Grupos de parâmetros
* Acessibilidade Pública
* Estabelecer conexões públicas
* Estabelecer conexões privadas
* Grupos de segurança do RDS
* Implantação Blue/Green
* Suporte estendido

## S3
* Regras de nomes de buckets
* Restrições e limitações de buckets
* Tipos de buckets
* Diretórios nos buckets
* Objetos
* Etags de objetos
* Checksums de objetos
* Prefixos de objetos
* Metadados de objetos
  * Definidos pelo sistema
  * Definidos pelo usuário
* Worm
* Object Lock
  * Travas de retenções (Retention Holds)
  * Travas legais (Legal Holds)
* URI do bucket
* CLI
* Estilos de requisições
* Endpoints dualstack
* Classes de armazenamento
  * Standard
  * Standard-IA
  * Express One-Zone
  * One Zone-IA
  * Glacier Instant Retrieval
  * Glacier Flexible Retrieval
  * Glacier Deep Archive
  * Intelligent Tiering
* Segurança
    * Block Public Access
    * ACL
    * Políticas de Bucket
    * IAM Access Analyzer for S3
    * Políticas de Bucket x Políticas IAM
    * Concessões de acesso
    * Privacidade de tráfego interredes
    * CORS
* Criptografia
  * Em trânsito
  * Em repouso
  * SS3-S3
  * SSE-KMS
  * SSE-C
  * DSSE-KMS
  * Chave de bucket
  * Criptografia do lado do cliente
* Consistência de dados
* Replicação de objetos
  * Entre regiões (Cross-region)
  * Mesma região (Same-region)
  * Bi-direcional
  * Em lote (Batch replication)
  * Regras de configuração de replicação
* Versionamento
  * Adicionar versões de objetos
  * Listar versões de objetos
  * Consultar versões de objetos
  * Excluir versões de objetos
  * Restaurar versões de objetos
  * MFA Delete
* S3 Lifecycle (Ciclo de Vida do S3)
  * Transição de objetos
  * Expiração de objetos
  * Configurações de transição
  * Política de ciclo de vida
* S3 Transfer Acceleration
* URLs Pré-Assinadas
* Access Points
  * Access Points Multirregião
  * Object Lambda Access Points
* Mountpoint for Amazon S3
* Objetos arquivados
* Objetos arquivados restaurados
* Requesters Pay
  * Header
  * Troubleshooting
* AWS Marketplace for S3
* S3 Batch Operations
* S3 Inventory
* S3 Select
  * Comparativo S3 Select x Athena
* Tags de objetos
* Logs do servidor
* S3 Event Notifications
* Storage Lens
* Hospedagem de site estático
  * Configurar hospedagem
  * Redirecionar requisições
  * Acesso público
  * Política de bucket
  * Single Page Apps (SPA)
* Multipart Upload
* Pesquisa por Byte Range
* Interoperabilidade

## Elasticache
* Redis
* Tipos de Dados
* Memcached

## API Gateway
* OpenAPI
* OpenAPI com o API Gateway
* API REST
  * Componentes API REST
* API HTTP
  * Componentes API REST

## MemoryDB

## Step Functions
* Casos de Uso
* Estados
* Entradas e Saídas

## API da AWS
* CLI
  * Comandos
  * Códigos de retorno
  * Wizards
  * Formatos de saída
  * Paginação
  * Flags de comandos
  * Comandos de espera (Wait)
  * Aliases no CLI
  * Filtragem
  * Consultas (querying)
  * Uso de aspas com strings
  * Esqueletos do CLI
  * Input Flag
  * Sintaxe simplificada
  * PowerShell AWS para AWS CLI
  * Variáveis de ambiente
  * Encadeamento com variáveis de ambiente
  * Encadeamento com XArgs
  * Arquivos de configurações
  * Perfis nomeados
  * Comandos Configure
  * CLI com SSO
  * Retentativas no CLI
  * CLI com metadados de EC2
  * CLI por Proxy
  * CLI com Roles do IAM
  * CLI com Credenciais externas
  * Imagem Docker do CLI
  * Instalação / Atualização
  * Histórico de Versões
  * MFA
  * Opções de preenchimento automático
  * CLI Autoprompt
* Chaves de acesso
* Retentativas e Backoff Exponencial
* Smithy
* Security Token Service (STS)
* Assinar requisições de API AWS
* AWS Signature Version 4
* Endpoints de Serviços
  * Endpoints regionais
  * Endpoints globais
  * Endpoints FIPS
  * Troubleshooting
  * Endpoints Dualstack
* Ações de API
* JSON
* YAML
* JQ Library
* JP Library
* YQ Library
* Parâmetros de arquivos
* Encoding Base64

## VPC
* Componentes
* Recursos principais
* VPC padrão
* Excluir VPCs
* Rota padrão
* VPCs compartilhadas
* NACL
* Grupos de segurança
* Stateful
* Stateless
* Tabela de rotas
* Gateways
  * Internet Gateway
  * Egress Only Internet Gateway
* IP Elástico
* Lista de Prefixos Gerenciados
* Suporte a IPv6
* Network Address Usage
* Direct Connect
* Endpoints de VPC
  * Endpoint de Interface
  * Endpoint de Gateway
  * Endpoint de Gateway Load Balancer
* PrivateLink
* VPC Flow Logs
* AWS Virtual Private Network (AWS VPN)
* Site-to-Site VPN
* Virtual Private Gateway (VGW)
* Customer Gateway (Gateway de Cliente - CGW)
* Transit Gateway para VPN
* AWS Client VPN
* Network Address Translation - NAT
* Gateway NAT
* Instância NAT
* Jumpbox
* VPC Lattice
* Transit Gateway
* Espelhamento de Tráfego
* Route53 Resolver DNS Firewall
* AWS Network Firewall
* Emparelhamento de VPC (VPC Peering)

## Lambda
* Versões de Funções
* Aliases
* Layers
* Sets de Instruções
* Tempos de execuções (Runtimes)
* [Runtimes apenas para sistema operacional](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/runtimes-provided.html)
* Pacotes de implantações
* Modelo de programação
* Assinatura de Código
* Blueprints de Funções
* Aplicações
* Lambda Private Networking
* Cold Starts
* Ambientes de Execução
* Concorrência
  * Reservada
  * Provisionada
* Variáveis de Ambiente
* Armazenamento Temporário
* Montagem de Elastic File System (EFS)
* URLs de Funções
* Power Tuning
* Roles de Execução
* Logs de Funções
* Extensões
* SnapStart
* Invocação Síncrona (Sync)
* Invocação Assíncrona (Async)

## CloudFront
* Lambda@Edge
* CloudFront Functions
* Origem
* Política de Caching
* Política de Requisição de Origem
* Política de Header de Resposta
* Origin Access Identity (OAI)
* Origin Access Control (OAC)
* Origin Shield
* Restrições Geográficas
* Parâmetros de String de Consulta em Cache
* Conteúdo baseado em Cookies
* Tipos de Conteúdos
* Invalidação de Cache
* Cache Busting com Digests
* Objeto Raíz padrão
* Exigência de HTTPS
* URLs Assinadas
* Cookies Assinados
* Páginas de erro customizadas

## Aurora
* Escalabilidade
* Aurora Provisionado
* Instâncias de Leitura
* Instâncias de Escrita
* Aurora Serverless v2
* Aurora Global Database
* API de Dados RDS
* Babelfish para Aurora

## Elastic Load Balancer
* Regras de tráfego
* Application Load Balancer
  * Regras
    * Roteamento de requisições
    * Tipos de Ações
    * Respostas Fixas
    * Ações de Redirecionamento
    * Tipos de condições
  * Header do Host
  * Header HTTP
  * Método de requisição HTTP
  * Padrão de caminhos
  * Strings de consultas
  * IP de origem
* Network Load Balancer
* Classic Load Balancer
* Sticky Sessions
* Cross Zone Load Balancing
* XFF-Header
* Verificações de Integridade
* Registrar/desregistrar alvos

## Athena
* Componentes
* Tipos de Dados
* Tabela
* SerDe

## AWS Copilot

## EFS
* EFS Client

## EBS
* Tipos de Volumes
* HDD
* RAID
* SSD
* Fita Magnética
* Mover volumes
* Volumes EBS x Volumes de armazenamento de instâncias (Instance store)
* Esquemas de particionamento
* Bloqueio de endereço lógico
* EBS Multi-Attach

## AppConfig

## Amazon Q

## CodeWhisperer

## CodeGuru

## Amazon Detective

## Batch

## Firewall Manager

## AppSync
* O que é GraphQL?
* Sobre o AppSync

## Amplify

## OpenSearch Service