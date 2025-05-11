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

#### [Outras implantações](https://docs.aws.amazon.com/pt_br/elasticbeanstalk/latest/dg/using-features.CNAMESwap.html)
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

## [Fargate](https://aws.amazon.com/pt/fargate/)
* [Tarefas do Fargate](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/getting-started-fargate.html)
* [Tamanhos de Tarefas](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/capacity-tasksize.html)
* [Comparativo Fargate x Lambda](https://docs.aws.amazon.com/pt_br/decision-guides/latest/fargate-or-lambda/fargate-or-lambda.html)

## [Elastic Container Service (ECS)](https://docs.aws.amazon.com/pt_br/AmazonECS/latest/developerguide/Welcome.html)

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
* [Registros DNS - vídeo explicativo](https://youtu.be/HnUDtycXSNE)
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
* [AWS Private Certificate Authority](https://docs.aws.amazon.com/pt_br/privateca/latest/userguide/PcaWelcome.html)

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
* [Fila de Mensagens Mortas (Dead-Letter Queue)](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-dead-letter-queues.html)
* [Aplicação como Assinante](https://docs.aws.amazon.com/pt_br/sns/latest/dg/sns-mobile-application-as-subscriber.html)

## [SQS](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/welcome.html)
* [Envio de mensagens grandes](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-managing-large-messages.html)
* [Fila Padrão](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/standard-queues.html)
* [Fila FIFO](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-fifo-queues.html)
* [ABAC](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-abac.html)
* [Política de Acesso](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-overview-of-managing-access.html)
* [Metadados de mensagens](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-message-metadata.html)
* [Tempo limite de visibilidade](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-visibility-timeout.html)
* [Filas em atraso](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-delay-queues.html)
* [Timers de mensagens](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-message-timers.html)
* [Filas temporárias](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-temporary-queues.html)
* [Sondagem curta e sondagem longa](https://docs.aws.amazon.com/pt_br/AWSSimpleQueueService/latest/SQSDeveloperGuide/sqs-short-and-long-polling.html)

## [Kinesis](https://docs.aws.amazon.com/pt_br/streams/latest/dev/introduction.html)
* [Kinesis Data Streams](https://docs.aws.amazon.com/pt_br/streams/latest/dev/introduction.html)
* [EFO (Enhanced Fanout)](https://docs.aws.amazon.com/pt_br/glue/latest/dg/aws-glue-programming-etl-connect-kinesis-efo.html)
* [KPL - Kinesis Producer Library](https://docs.aws.amazon.com/pt_br/streams/latest/dev/kinesis-kpl-concepts.html)
* [KCL - Kinesis Client Library](https://docs.aws.amazon.com/pt_br/streams/latest/dev/kcl.html)
* [Kinesis Data Firehose](https://docs.aws.amazon.com/pt_br/firehose/latest/dev/what-is-this-service.html)
* [Kinesis Video Streams](https://docs.aws.amazon.com/pt_br/kinesisvideostreams/latest/dg/what-is-kinesis-video.html)
* [Kinesis Data Analytics (atualmente como Amazon Managed Service for Apache Flink)](https://docs.aws.amazon.com/pt_br/kinesisanalytics/latest/dev/what-is.html)

## [Systems Manager - Parameter Store](https://docs.aws.amazon.com/pt_br/systems-manager/latest/userguide/systems-manager-parameter-store.html)
* [Casos de Uso](https://docs.aws.amazon.com/pt_br/systems-manager/latest/userguide/systems-manager-best-practices.html)
* [Políticas de parâmeros](https://docs.aws.amazon.com/pt_br/systems-manager/latest/userguide/parameter-store-policies.html)
* [Hierarquia de parâmetros](https://docs.aws.amazon.com/pt_br/systems-manager/latest/userguide/sysman-paramstore-hierarchies.html)

## [Secrets Manager](https://docs.aws.amazon.com/pt_br/secretsmanager/latest/userguide/intro.html)
* [Casos de Uso](https://aws.amazon.com/secrets-manager/)
* [Rotação automática](https://docs.aws.amazon.com/pt_br/secretsmanager/latest/userguide/rotating-secrets.html)
* [CLI](https://docs.aws.amazon.com/pt_br/cli/v1/userguide/cli_secrets-manager_code_examples.html)

## [DynamoDB](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/Introduction.html)
* [Tabelas](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/WorkingWithTables.html)
* [Consistência de leituras](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/HowItWorks.ReadConsistency.html)
* [Partições](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/HowItWorks.Partitions.html)
* [Chaves primárias](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/HowItWorks.CoreComponents.html)

  * Simples
  * Composta
* [Query](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/Query.html)
* [Scan](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/APIReference/API_Scan.html)
* [Capacidade Provisionada](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/provisioned-capacity-mode.html)
* [Capacidade Sob-demanda](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/on-demand-capacity-mode.html)
* [Calcular leituras e escritas (RCU e WCU)](https://klouddb.io/dynamodb-for-dbas-calculating-rcus-and-wcus/)
* [Tabelas Globais](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/GlobalTables.html)
* [Transações](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/transaction-apis.html)
* [Time-to-Live (TTL)](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/TTL.html)
* [DynamoDB Streams](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/Streams.html)
* [Erros comuns](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/Programming.Errors.html)
* [Índices](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/SecondaryIndexes.html)

  * [Local Secondary Indexes (LSI)](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/LSI.html)
  * [Global Secondary Indexes (GSI)](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/GSI.html)
* [DynamoDB Accelerator (DAX)](https://docs.aws.amazon.com/pt_br/amazondynamodb/latest/developerguide/DAX.concepts.html)

## [EC2](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html)
* [Cloud Init](https://docs.aws.amazon.com/linux/al2/ug/amazon-linux-cloud-init.html)
* [Dados de usuário (UserData)](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/user-data.html)
* [Metadados](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-metadata.html)
* [Tipos de instâncias](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/instance-types.html)
* [Famílias de instâncias](https://docs.aws.amazon.com/pt_br/ec2/latest/instancetypes/instance-types.html)
* [Processadores](https://docs.aws.amazon.com/whitepapers/latest/aws-graviton-performance-testing/what-is-aws-graviton.html)
* [Instâncias burstable](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/burstable-performance-instances.html)
* [Verificações de origem e destino](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/using-eni.html)
* [Logs do sistema](https://docs.aws.amazon.com/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)
* [Grupos de posicionamento](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/placement-groups.html)

  * [Cluster](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/placement-groups.html#placement-groups-cluster)
  * [Partição](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/placement-groups.html#placement-groups-partition)
  * [Distribuição (Spread)](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/placement-groups.html#placement-groups-spread)
* [EC2 Connect](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ec2-instance-connect-methods.html)
* [Amazon Linux](https://docs.aws.amazon.com/linux/al2/ug/what-is-amazon-linux.html)
* [Tamanhos de instâncias](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/instance-types.html)
* [Perfis de instâncias](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles_use_switch-role-ec2_instance-profiles.html)
* [Ciclo de vida de instâncias](https://docs.aws.amazon.com/pt_br/autoscaling/ec2/userguide/ec2-auto-scaling-lifecycle.html)
* [Screenshot do console da instância](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instance-console-screenshot.html)
* [Hostnames](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/set-hostname.html)
* [Nome de usuário padrão](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html#AccessingInstancesLinux_connecting)

## [IAM](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/introduction.html)

* Componentes principais

  * [Usuários](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_users.html)
  * [Grupos](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_groups.html)
  * [Políticas](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/access_policies.html)
  * [Funções (ou Perfis ou Roles)](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles.html)
* [Tipos de políticas](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/access_policies.html#access_policy-types)
* [Estrutura de políticas](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/access_policies.html#access_policy-structure)
* [Políticas de senhas](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_passwords_account-policy.html)
* [Chaves de acesso](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_access-keys.html)
* [MFA (Autenticação Multifator)](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_mfa.html)
* [Credenciais de segurança temporárias](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_temp.html)
* [Funções entre-contas (Cross-account roles)](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles_create_for-user.html#roles-create-crossaccountuser)
* [IAM Security Token Service (STS)](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_temp.html)
* [Federação de Identidade](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_roles_providers.html)
* [AssumeRoleWithWebIdentity](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp_request.html)

## [CloudTrail](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/cloudtrail-user-guide.html)

* [Histórico de eventos](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/view-cloudtrail-events.html)
* [Trilhas](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/cloudtrail-create-and-update-a-trail.html)
* [CloudTrail para CloudWatch](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/send-cloudtrail-events-to-cloudwatch-logs.html)
* [Gerenciamento e Eventos de dados](https://docs.aws.amazon.com/pt_br/awscloudtrail/latest/userguide/logging-data-events-with-cloudtrail.html)

## [CloudWatch](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)

* [Conceitos de Observabilidade](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/WhatIsCloudWatch.html)
* [Logs](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/WhatIsCloudWatchLogs.html)
* [Grupos de Logs](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/Working-with-log-groups-and-streams.html)
* [Log Streams](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/Working-with-log-groups-and-streams.html)
* [Eventos de Logs](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/Working-with-log-events.html)
* [Log Insights](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/AnalyzingLogData.html)
* [Campos descobertos](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/CWL_AnalyzeLogData-discover-fields.html)
* [Métricas](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/working_with_metrics.html)
* [Disponibilidade dos dados](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/cloudwatch_concepts.html#Metric)
* [Métricas no nível de host](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/host-level-metrics.html)
* [CloudWatch Agent](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/monitoring/Install-CloudWatch-Agent.html)
* [Coleta de Logs](https://docs.aws.amazon.com/pt_br/AmazonCloudWatch/latest/logs/AgentReference.html)

## [EventBridge](https://docs.aws.amazon.com/pt_br/eventbridge/latest/userguide/eb-what-is.html)

* [Componentes principais](https://docs.aws.amazon.com/pt_br/eventbridge/latest/userguide/eb-what-is-how-it-works-concepts.html)
* [Eventos](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-events.html)
* [Expressões de agendamento](https://docs.aws.amazon.com/pt_br/scheduler/latest/UserGuide/schedule-types.html)
* [Regras](https://docs.aws.amazon.com/pt_br/eventbridge/latest/userguide/eb-rules.html)
* [Configurar Entrada](https://docs.aws.amazon.com/es_es/eventbridge/latest/userguide/eb-transform-input-rule.html)
* [Registro de Schema](https://docs.aws.amazon.com/eventbridge/latest/userguide/eb-schema-registry.html)
* [Padrões de Eventos](https://docs.aws.amazon.com/pt_br/eventbridge/latest/userguide/eb-event-patterns.html)
* [Origens de Eventos de Parceiros](https://docs.aws.amazon.com/pt_br/eventbridge/latest/userguide/eb-saas.html)

## [CloudFormation](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/Welcome.html)

* [Componentes de um Template](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/template-anatomy.html)
* [Formatos de Templates](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/template-formats.html)
* [Quick Starts](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cfn-console-create-stacks-quick-create-links.html)
* [Estados das Pilhas](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/stacks.html)
* [Atualizações de Pilhas](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/updating.stacks.walkthrough.html)
* [Políticas de Pilhas](https://docs.aws.amazon.com/pt_br/prescriptive-guidance/latest/least-privilege-cloudformation/cloudformation-stack-policies.html)
* [Pilhas Aninhadas](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html)
* [Rollbacks](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-direct.html)
* [Detecção de Desvios](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/using-cfn-stack-drift.html)
* [ChangeSets](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-changesets.html)
* [CDK](https://docs.aws.amazon.com/cdk/v2/guide/home.html)
* [Pseudo-parâmetros](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/pseudo-parameter-reference.html)
* [Atributos de Recursos](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/aws-properties-name.html)
* [Funções Intrínsecas](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/intrinsic-function-reference.html)
* [Condições de Espera](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/using-cfn-waitcondition.html)
* [IaC Generator](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/using-cfn-cli.html)
* [Helper Scripts](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/cfn-helper-scripts-reference.html)
* [Init](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/aws-resource-init.html)
* [CFN-Hup](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/cfn-hup.html)
* [Recursos customizados](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/template-custom-resources.html)
* [CloudFormation Registry](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/registry.html)
* [Prevent Stack Updates](https://docs.aws.amazon.com/pt_br/AWSCloudFormation/latest/UserGuide/protect-stack-resources.html)

## [SAM](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html)

* [Comparativo SAM x CloudFormation](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-vs-cloudformation.html)
* [Comandos CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-commands.html)

## [Conceitos de CI/CD](https://www.youtube.com/watch?v=j0DNdPXTBi0)

* Continuous Integration (CI)
* Continuous Delivery (CD)
* Continuous Deployment (CD)

## [CodeCommit](https://docs.aws.amazon.com/codecommit/latest/userguide/welcome.html)

* [Características](https://docs.aws.amazon.com/codecommit/latest/userguide/welcome.html)

## [Docker](https://docs.docker.com/get-started/overview/)

* [Dockerfile](https://docs.docker.com/engine/reference/builder/)
* [Comandos Docker](https://docs.docker.com/engine/reference/commandline/docker/)

## [CodeBuild](https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html)

* [Fluxo de trabalho](https://docs.aws.amazon.com/codebuild/latest/userguide/how-codebuild-works.html)
* [Ambientes de build](https://docs.aws.amazon.com/codebuild/latest/userguide/build-env-ref.html)
* [Buildspec.yml](https://docs.aws.amazon.com/codebuild/latest/userguide/build-spec-ref.html)
* [Casos de uso](https://docs.aws.amazon.com/codebuild/latest/userguide/use-cases.html)

## [CodeDeploy](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html)

* [Componentes principais](https://docs.aws.amazon.com/codedeploy/latest/userguide/welcome.html)
* [Tipos de implantações](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-steps.html)

  * [In-Place](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-steps.html#deployment-steps-in-place)
  * [Blue/Green](https://docs.aws.amazon.com/codedeploy/latest/userguide/deployment-steps.html#deployment-steps-blue-green)
* [Appspec.yml](https://docs.aws.amazon.com/codedeploy/latest/userguide/app-spec-ref.html)
* [Lifecycle hooks](https://docs.aws.amazon.com/codedeploy/latest/userguide/reference-appspec-file-structure-hooks.html)
* [Agent e Service Roles](https://docs.aws.amazon.com/codedeploy/latest/userguide/codedeploy-agent.html)

## [CodePipeline](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)

* [Componentes principais](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)
* [Actions](https://docs.aws.amazon.com/codepipeline/latest/userguide/reference-pipeline-structure.html#actions)
* [Exemplos](https://docs.aws.amazon.com/codepipeline/latest/userguide/getting-started.html)
* [Casos de Uso](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)


## [Amazon RDS](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Welcome.html)

* [Criptografia](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Overview.Encryption.html)
* [Backup](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_WorkingWithAutomatedBackups.html)
* [Restaurar backup](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_RestoreFromSnapshot.html)
* [Grupos de subredes](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html)
* [Multi-AZ](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html)
* [Réplicas de leitura](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_ReadRepl.html)
* [Multi-AZ x Réplicas de Leitura](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Concepts.MultiAZ.html)
* [Instância do RDS](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Overview.DBInstance.html)
* [RDS Performance Insights](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_PerfInsights.html)
* [RDS Custom](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/rds-custom.html)
* [RDS Proxy](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/rds-proxy.html)
* [Leituras e escritas otimizadas](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/rds-optimized-reads.html)
* [Autenticação por IAM](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/UsingWithRDS.IAMDBAuth.html)
* [Autenticação Kerberos](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/postgresql-kerberos.html)
* [Integração do RDS com Secrets Manager](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/rds-secrets-manager.html)
* [Master User Account](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Oracle.Concepts.Privileges.html)
* [Grupos de parâmetros](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_WorkingWithParamGroups.html)
* [Acessibilidade Pública](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html)
* [Estabelecer conexões públicas](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html)
* [Estabelecer conexões privadas](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_VPC.WorkingWithRDSInstanceinaVPC.html)
* [Grupos de segurança do RDS](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/Overview.RDSSecurityGroups.html)
* [Implantação Blue/Green](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/blue-green-deployments.html)
* [Suporte estendido](https://docs.aws.amazon.com/pt_br/AmazonRDS/latest/UserGuide/USER_Maintenance.html)


## [Amazon S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Welcome.html)

* [Regras de nomes de buckets](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/directory-bucket-naming-rules.html)
* [Restrições e limitações de buckets](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/directory-bucket-naming-rules.html)
* [Tipos de buckets](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/directory-bucket-naming-rules.html)
* [Diretórios nos buckets](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/directory-bucket-naming-rules.html)
* [Objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingObjects.html)
* [Etags de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingObjects.html)
* [Checksums de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingObjects.html)
* [Prefixos de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingObjects.html)
* Metadados de objetos
  * [Definidos pelo sistema](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingMetadata.html)
  * [Definidos pelo usuário](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingMetadata.html)
* [WORM](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-lock.html)
* [Object Lock](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-lock.html)
  * [Travas de retenções (Retention Holds)](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-lock.html)
  * [Travas legais (Legal Holds)](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-lock.html)
* [URI do bucket](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingBucket.html)
* [CLI](https://docs.aws.amazon.com/pt_br/cli/latest/reference/s3/index.html)
* [Estilos de requisições](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/VirtualHosting.html)
* [Endpoints dualstack](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/VirtualHosting.html)
* [Classes de armazenamento](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Standard](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Standard-IA](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Express One-Zone](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [One Zone-IA](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Glacier Instant Retrieval](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Glacier Flexible Retrieval](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Glacier Deep Archive](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
  * [Intelligent Tiering](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-class-intro.html)
* Segurança
  * [Block Public Access](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/access-control-block-public-access.html)
  * [ACL](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/acl-overview.html)
  * [Políticas de Bucket](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/bucket-policies.html)
  * [IAM Access Analyzer for S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/access-analyzer.html)
  * [Políticas de Bucket x Políticas IAM](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/using-iam-policies.html)
  * [Concessões de acesso](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/acl-overview.html)
  * [Privacidade de tráfego interredes](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/privatelink-interface-endpoints.html)
  * [CORS](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/cors.html)
* Criptografia
  * [Em trânsito](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingEncryption.html)
  * [Em repouso](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingEncryption.html)
  * [SSE-S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingEncryption.html)
  * [SSE-KMS](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingKMSEncryption.html)
  * [SSE-C](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/ServerSideEncryptionCustomerKeys.html)
  * [DSSE-KMS](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingDSSEncryption.html)
  * [Chave de bucket](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/bucket-key.html)
  * [Criptografia do lado do cliente](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingClientSideEncryption.html)
* [Consistência de dados](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Introduction.html)
* Replicação de objetos
  * [Entre regiões (Cross-region)](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/replication.html)
  * [Mesma região (Same-region)](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/replication.html)
  * [Bi-direcional](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/replication.html)
  * [Em lote (Batch replication)](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/replication.html)
  * [Regras de configuração de replicação](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/replication-add-config.html)
* Versionamento
  * [Adicionar versões de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Versioning.html)
  * [Listar versões de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Versioning.html)
  * [Consultar versões de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Versioning.html)
  * [Excluir versões de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/DeletingObjectVersions.html)
  * [Restaurar versões de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Versioning.html)
  * [MFA Delete](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/MultiFactorAuthenticationDelete.html)
* S3 Lifecycle (Ciclo de Vida do S3)
  * [Transição de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/lifecycle-transition-general-considerations.html)
  * [Expiração de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/lifecycle-expire-general-considerations.html)
  * [Configurações de transição](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/lifecycle-transition-general-considerations.html)
  * [Política de ciclo de vida](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/lifecycle-configuration-examples.html)
* [S3 Transfer Acceleration](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/transfer-acceleration.html)
* [URLs Pré-Assinadas](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/ShareObjectPreSignedURL.html)
* Access Points
  * [Access Points Multirregião](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/multi-region-access-points.html)
  * [Object Lambda Access Points](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/transforming-objects.html)
* [Mountpoint for Amazon S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/mountpoint.html)
* [Objetos arquivados](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/archived-objects.html)
* [Objetos arquivados restaurados](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/restoring-archived-objects.html)
* Requesters Pay
  * [Header](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/RequesterPaysBuckets.html)
  * [Troubleshooting](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/RequesterPaysBuckets.html)
* [AWS Marketplace for S3](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/marketplace.html)
* [S3 Batch Operations](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/batch-ops.html)
* [S3 Inventory](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage-inventory.html)
* [S3 Select](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/using-select.html)

  * [Comparativo S3 Select x Athena](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/selecting-content-from-objects.html)
* [Tags de objetos](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/object-tagging.html)
* [Logs do servidor](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/enable-server-access-logging.html)
* [S3 Event Notifications](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/EventNotifications.html)
* [Storage Lens](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/storage_lens_basics_metrics_recommendations.html)
* [Hospedagem de site estático](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/WebsiteHosting.html)

  * [Configurar hospedagem](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html)
  * [Redirecionar requisições](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/Redirects.html)
  * [Acesso público](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/WebsiteAccessPermissionsReqd.html)
  * [Política de bucket](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/WebsiteAccessPermissionsReqd.html)
  * [Single Page Apps (SPA)](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/HostingWebsiteOnS3Setup.html)
* [Multipart Upload](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/mpu-upload-object.html)
* [Pesquisa por Byte Range](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/RangeGET.html)
* [Interoperabilidade](https://docs.aws.amazon.com/pt_br/AmazonS3/latest/userguide/UsingObjects.html)

## [Amazon ElastiCache](https://docs.aws.amazon.com/pt_br/AmazonElastiCache/latest/dg/WhatIs.html)

* [Redis](https://docs.aws.amazon.com/pt_br/AmazonElastiCache/latest/dg/WhatIs.html)
* [Tipos de Dados](https://docs.aws.amazon.com/pt_br/AmazonElastiCache/latest/dg/json-document-overview.html)
* [Memcached](https://docs.aws.amazon.com/pt_br/AmazonElastiCache/latest/dg/WhatIs.html)

## [Amazon API Gateway](https://docs.aws.amazon.com/pt_br/apigateway/latest/developerguide/welcome.html)

* [OpenAPI](https://docs.aws.amazon.com/pt_br/apigateway/latest/developerguide/api-gateway-import-api.html)
* [OpenAPI com o API Gateway](https://docs.aws.amazon.com/pt_br/apigateway/latest/developerguide/api-gateway-import-api.html)
* API REST
  * [Componentes API REST](https://docs.aws.amazon.com/pt_br/apigateway/latest/developerguide/apigateway-rest-api.html)
* API HTTP
  * [Componentes API HTTP](https://docs.aws.amazon.com/pt_br/apigateway/latest/developerguide/http-api.html)

## [Amazon MemoryDB](https://docs.aws.amazon.com/pt_br/memorydb/latest/devguide/what-is-memorydb.html)

## [AWS Step Functions](https://docs.aws.amazon.com/pt_br/step-functions/latest/dg/welcome.html)

* [Casos de Uso](https://docs.aws.amazon.com/pt_br/step-functions/latest/dg/use-cases.html)
* [Estados](https://docs.aws.amazon.com/pt_br/step-functions/latest/dg/concepts-statemachines.html)
* [Entradas e Saídas](https://docs.aws.amazon.com/pt_br/step-functions/latest/dg/concepts-input-output-filtering.html)

## [API da AWS – Visão Geral](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-welcome.html)

* [AWS CLI](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-welcome.html)
  * [Comandos](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage.html)
  * [Códigos de retorno](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-return-codes.html)
  * [Wizards](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-wizard.html)
  * [Formatos de saída](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-output.html)
  * [Paginação](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-pagination.html)
  * [Flags de comandos](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-options.html)
  * [Comandos de espera (Wait)](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-wait.html)
  * [Aliases no CLI](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-aliases.html)
  * [Filtragem](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-filter.html)
  * [Consultas (querying)](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-output.html#cli-usage-output-filter)
  * [Uso de aspas com strings](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-parameters-quoting.html)
  * [Esqueletos do CLI](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-skeleton.html)
  * [Input Flag](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-input.html)
  * [Sintaxe simplificada](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-syntax.html)
  * [PowerShell AWS para AWS CLI](https://docs.aws.amazon.com/pt_br/powershell/latest/userguide/pstools.html)
  * [Variáveis de ambiente](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-envvars.html)
  * [Encadeamento com variáveis de ambiente](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-envvars.html)
  * [Encadeamento com XArgs](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-output.html#cli-usage-output-filter)
  * [Arquivos de configurações](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-files.html)
  * [Perfis nomeados](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-profiles.html)
  * [Comandos Configure](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-quickstart.html)
  * [CLI com SSO](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-sso.html)
  * [Retentativas no CLI](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-retries.html)
  * [CLI com metadados de EC2](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-ec2-metadata.html)
  * [CLI por Proxy](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-proxy.html)
  * [CLI com Roles do IAM](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-role.html)
  * [CLI com Credenciais externas](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-external.html)
  * [Imagem Docker do CLI](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-docker.html)
  * [Instalação / Atualização](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/install-cliv2.html)
  * [Histórico de Versões](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-chap-release-notes.html)
  * [MFA](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-mfa.html)
  * [Opções de preenchimento automático](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-configure-completion.html)
  * [CLI Autoprompt](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-autoprompt.html)

* [Chaves de Acesso](https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_access-keys.html)
* [Retentativas e Backoff Exponencial](https://docs.aws.amazon.com/pt_br/general/latest/gr/api-retries.html)
* [Smithy](https://smithy.io/)
* [AWS Security Token Service (STS)](https://docs.aws.amazon.com/pt_br/STS/latest/APIReference/Welcome.html)
* [Assinar Requisições de API AWS](https://docs.aws.amazon.com/pt_br/general/latest/gr/signing_aws_api_requests.html)
* [AWS Signature Version 4](https://docs.aws.amazon.com/pt_br/general/latest/gr/signature-version-4.html)
* [Endpoints de Serviços](https://docs.aws.amazon.com/pt_br/general/latest/gr/aws-service-information.html)

  * [Endpoints Regionais](https://docs.aws.amazon.com/pt_br/general/latest/gr/rande.html)
  * [Endpoints Globais](https://docs.aws.amazon.com/pt_br/general/latest/gr/rande.html#global-endpoints)
  * [Endpoints FIPS](https://docs.aws.amazon.com/pt_br/general/latest/gr/fips-endpoints.html)
  * [Troubleshooting](https://docs.aws.amazon.com/pt_br/general/latest/gr/troubleshooting.html)
  * [Endpoints Dualstack](https://docs.aws.amazon.com/pt_br/general/latest/gr/dualstack-endpoints.html)

* [Ações de API](https://docs.aws.amazon.com/pt_br/general/latest/gr/api-actions.html)
* [JSON](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-output.html#cli-usage-output-json)
* [YAML](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-output.html#cli-usage-output-yaml)
* [JQ Library](https://stedolan.github.io/jq/)
* [JP Library](https://jmespath.org/)
* [YQ Library](https://github.com/mikefarah/yq)
* [Parâmetros de Arquivos](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-parameters.html)
* [Encoding Base64](https://docs.aws.amazon.com/pt_br/cli/latest/userguide/cli-usage-parameters.html#cli-usage-parameters-base64)


## [Amazon VPC](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/what-is-amazon-vpc.html)

* [Componentes](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/what-is-amazon-vpc.html#vpc-components)
* [Recursos principais](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/what-is-amazon-vpc.html#vpc-resources)
* [VPC padrão](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/default-vpc.html)
* [Excluir VPCs](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/delete-vpc.html)
* [Rota padrão](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_Route_Tables.html)
* [VPCs compartilhadas](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-sharing.html)
* [NACL](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-network-acls.html)
* [Grupos de segurança](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-security-groups.html)
* [Stateful](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-security-groups.html)
* [Stateless](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-network-acls.html)
* [Tabela de rotas](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_Route_Tables.html)
* Gateways
  * [Internet Gateway](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_Internet_Gateway.html)
  * [Egress Only Internet Gateway](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/egress-only-internet-gateway.html)
* [IP Elástico](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/elastic-ip-addresses-eip.html)
* [Lista de Prefixos Gerenciados](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/working-with-aws-managed-prefix-lists.html)
* [Suporte a IPv6](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-migrate-ipv6-add.html)
* [Network Address Usage](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-ip-addressing.html)
* [Direct Connect](https://docs.aws.amazon.com/pt_br/directconnect/latest/UserGuide/Welcome.html)
* Endpoints de VPC
  * [Endpoint de Interface](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpce-interface.html)
  * [Endpoint de Gateway](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpce-gateway.html)
  * [Endpoint de Gateway Load Balancer](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpce-gateway-load-balancer.html)
* [PrivateLink](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-endpoints.html)
* [VPC Flow Logs](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/flow-logs.html)
* [AWS Virtual Private Network (AWS VPN)](https://docs.aws.amazon.com/pt_br/vpn/latest/s2svpn/VPC_VPN.html)
* [Site-to-Site VPN](https://docs.aws.amazon.com/pt_br/vpn/latest/s2svpn/VPC_VPN.html)
* [Virtual Private Gateway (VGW)](https://docs.aws.amazon.com/pt_br/vpn/latest/s2svpn/VPC_VPN.html)
* [Customer Gateway (Gateway de Cliente - CGW)](https://docs.aws.amazon.com/pt_br/vpn/latest/s2svpn/VPC_VPN.html)
* [Transit Gateway para VPN](https://docs.aws.amazon.com/pt_br/vpc/latest/tgw/what-is-transit-gateway.html)
* [AWS Client VPN](https://docs.aws.amazon.com/pt_br/vpn/latest/clientvpn-admin/what-is.html)
* Network Address Translation - NAT
  * [Gateway NAT](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/vpc-nat-gateway.html)
  * [Instância NAT](https://docs.aws.amazon.com/pt_br/vpc/latest/userguide/VPC_NAT_Instance.html)
* [Jumpbox](https://docs.aws.amazon.com/pt_br/whitepapers/latest/aws-vpc-connectivity-options/aws-vpc-connectivity-options.html)
* [VPC Lattice](https://docs.aws.amazon.com/pt_br/vpc/latest/lattice/what-is-vpc-lattice.html)
* [Transit Gateway](https://docs.aws.amazon.com/pt_br/vpc/latest/tgw/what-is-transit-gateway.html)
* [Espelhamento de Tráfego](https://docs.aws.amazon.com/pt_br/vpc/latest/mirroring/what-is-traffic-mirroring.html)
* [Route53 Resolver DNS Firewall](https://docs.aws.amazon.com/pt_br/route53/latest/dns-firewall/what-is-dns-firewall.html)
* [AWS Network Firewall](https://docs.aws.amazon.com/pt_br/network-firewall/latest/developerguide/what-is-aws-network-firewall.html)
* [Emparelhamento de VPC (VPC Peering)](https://docs.aws.amazon.com/pt_br/vpc/latest/peering/what-is-vpc-peering.html)


## [AWS Lambda](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/welcome.html)

* [Versões de Funções](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-versions.html)
* [Aliases](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-aliases.html)
* [Layers](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/chapter-layers.html)
* [Sets de Instruções](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/foundation-progmodel.html)
* [Tempos de execuções (Runtimes)](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-runtimes.html)
* [Runtimes apenas para sistema operacional](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/runtimes-provided.html)
* [Pacotes de implantações](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/java-package.html)
* [Modelo de programação](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/foundation-progmodel.html)
* [Assinatura de Código](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-codesigning.html)
* [Blueprints de Funções](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-samples.html)
* [Aplicações](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-samples.html)
* [Lambda Private Networking](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-vpc.html)
* [Cold Starts](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-runtime-environment.html)
* [Ambientes de Execução](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-runtime-environment.html)
* Concorrência

  * [Reservada](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-concurrency.html)
  * [Provisionada](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/provisioned-concurrency.html)
* [Variáveis de Ambiente](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-envvars.html)
* [Armazenamento Temporário](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-functions.html)
* [Montagem de Elastic File System (EFS)](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/configuration-filesystem.html)
* [URLs de Funções](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/urls.html)
* [Power Tuning](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/power-tuning.html)
* [Roles de Execução](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/lambda-intro-execution-role.html)
* [Logs de Funções](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/monitoring-functions-logs.html)
* [Extensões](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/using-extensions.html)
* [SnapStart](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/snapstart.html)
* [Invocação Síncrona (Sync)](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/invocation-sync.html)
* [Invocação Assíncrona (Async)](https://docs.aws.amazon.com/pt_br/lambda/latest/dg/invocation-async.html)


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

## EMR

## Glue

## Simple Email Service (Amazon SES)

## FSx

## EC2 Auto Scaling

## CloudShell

## CodeArtifact

## Config

## Organizations

## Systems Manager

## Trusted Advisor

## Global Accelerator

## CloudHSM

## IAM Identity Center (AWS Single Sign-On)

## Macie

## Resource Access Manager (RAM)

## WAF
