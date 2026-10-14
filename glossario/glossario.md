# Glossário de tecnologias, produtos e serviços Oracle

Este glossário foi organizado por categorias para servir como material de consulta e estudo, especialmente para quem trabalha com administração de banco de dados, infraestrutura, desenvolvimento de sistemas e computação em nuvem.

O portfólio da Oracle abrange bancos de dados, sistemas operacionais, middleware, ferramentas de desenvolvimento, infraestrutura em nuvem, aplicações empresariais, hardware especializado e serviços profissionais.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.oracle.com\&sz=32)

Oracle Brasil

+1



Como utilizar: cada item apresenta o nome oficial ou a sigla, seguido de uma descrição objetiva e, quando útil, sua finalidade prática no ambiente corporativo.

## 1. Bancos de dados e tecnologias de dados

Categoria fundamental para DBAs, arquitetos de dados e profissionais de sustentação.

| Nome                                         | Descrição                                                                                                                                       |
| -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------- |
| Oracle Database                              | SGBD relacional utilizado para armazenar, consultar, processar e proteger dados de aplicações empresariais.                                     |
| Oracle Database 19c                          | Versão de suporte de longo prazo da família 19c, amplamente utilizada em ambientes corporativos.                                                |
| Oracle AI Database                           | Denominação atual utilizada pela Oracle para sua evolução de banco de dados com recursos de IA; funcionalidades dependem da versão e da oferta. |
| Oracle Autonomous AI Database                | Serviço de banco de dados gerenciado que automatiza tarefas operacionais e incorpora recursos de IA.                                            |
| Oracle Multitenant                           | Arquitetura que permite gerenciar bancos conectáveis (PDBs) dentro de um banco contêiner (CDB).                                                 |
| Oracle Real Application Clusters (RAC)       | Tecnologia que permite múltiplas instâncias acessarem o mesmo banco de dados para alta disponibilidade e escalabilidade.                        |
| Oracle Data Guard                            | Tecnologia de replicação e proteção de banco de dados, utilizada para contingência e recuperação de desastres.                                  |
| Oracle Active Data Guard                     | Extensão licenciada do Data Guard que pode permitir consultas em bancos standby e outras funcionalidades adicionais.                            |
| Oracle Recovery Manager (RMAN)               | Ferramenta para backup, restauração, recuperação e manutenção de backups do Oracle Database.                                                    |
| Oracle Automatic Storage Management (ASM)    | Gerenciador de armazenamento para arquivos de banco de dados Oracle.                                                                            |
| Oracle Automatic Workload Repository (AWR)   | Repositório de estatísticas históricas de desempenho usado para diagnosticar gargalos.                                                          |
| Automatic Database Diagnostic Monitor (ADDM) | Analisa dados de desempenho e identifica possíveis causas de problemas no banco.                                                                |
| SQL                                          | Linguagem para consultar e manipular dados e administrar objetos relacionais.                                                                   |
| PL/SQL                                       | Linguagem procedural da Oracle para desenvolver procedimentos, funções, pacotes, gatilhos e rotinas de banco de dados.                          |
| Data Pump (EXPDP/IMPDP)                      | Ferramenta de exportação e importação lógica de dados e objetos.                                                                                |
| Oracle GoldenGate                            | Tecnologia de captura, replicação e movimentação de alterações de dados entre sistemas.                                                         |
| Oracle Partitioning                          | Recurso para dividir objetos grandes em partições, facilitando gerenciamento e desempenho em cenários adequados.                                |
| Oracle Spatial and Graph                     | Recursos para armazenar, consultar e analisar dados geográficos e relacionamentos em grafos.                                                    |
| Oracle Database In-Memory                    | Tecnologia que utiliza estruturas em memória para acelerar determinadas consultas analíticas.                                                   |
| Oracle Database Vault                        | Recurso de segurança para restringir acessos privilegiados a dados e operações sensíveis.                                                       |
| Oracle Data Safe                             | Serviço de segurança e avaliação de bancos de dados, com recursos como avaliação de configuração, auditoria e mascaramento.                     |
| Oracle SQL Developer                         | Ferramenta gráfica para desenvolver SQL e PL/SQL, navegar em objetos e administrar bancos de dados.                                             |
| Oracle SQLcl                                 | Interface de linha de comando para trabalhar com bancos Oracle por meio de SQL e scripts.                                                       |
| Oracle REST Data Services (ORDS)             | Camada que expõe dados e funcionalidades Oracle por serviços REST e dá suporte a aplicações como APEX.                                          |

[image](https://www.google.com/s2/favicons?domain=https://academy.oracle.com\&sz=32)

Oracle Academy

+1

## 2. Alta disponibilidade, backup e recuperação de desastres

| Nome                           | Descrição                                                                                                               |
| ------------------------------ | ----------------------------------------------------------------------------------------------------------------------- |
| High Availability (HA)         | Estratégias para manter sistemas disponíveis mesmo diante de determinadas falhas.                                       |
| Disaster Recovery (DR)         | Planejamento e procedimentos para recuperar serviços após um incidente grave.                                           |
| Fast-Start Failover            | Mecanismo do Data Guard Broker para realizar failover automático quando as condições configuradas são atendidas.        |
| Data Guard Broker              | Ferramenta de gerenciamento e monitoramento de configurações Data Guard.                                                |
| Flashback Database             | Recurso para retornar o banco a um estado anterior, conforme configuração e disponibilidade dos dados necessários.      |
| Flashback Query                | Permite consultar versões anteriores de dados dentro do período disponível de retenção.                                 |
| Flashback Table                | Permite reverter uma tabela para um estado anterior em condições suportadas.                                            |
| Archive Log Mode               | Modo de operação que arquiva redo logs, viabilizando recuperação até pontos no tempo e estratégias de backup adequadas. |
| Redo Log                       | Registra alterações realizadas no banco de dados para recuperação e consistência transacional.                          |
| Control File                   | Arquivo crítico que registra informações estruturais e de controle do banco.                                            |
| SPFILE / PFILE                 | Arquivos utilizados para armazenar parâmetros de inicialização da instância Oracle.                                     |
| Recovery Catalog               | Repositório opcional do RMAN para centralizar informações de backup e recuperação.                                      |
| RPO (Recovery Point Objective) | Perda máxima de dados, medida em tempo, tolerada pela organização.                                                      |
| RTO (Recovery Time Objective)  | Tempo máximo desejado para restaurar um serviço após uma interrupção.                                                   |

## 3. Infraestrutura em nuvem — Oracle Cloud Infrastructure (OCI)

[Oracle Cloud Infrastructure Security Architecture](https://images.openai.com/static-rsc-4/NoqVXsvP7vhGj8vHDwLh0v2VxS2YOYRosrX53PR7vKnXhDJs8zc0mKlXeTIhy70fyg241loN6PkCiTGuyxKwyjLMRxvIA7w4ZCJPcmA4GUfOq-VNHFZETYVKbcM8FVCHwR7F2cvEuPLTuheb1Bz56flQlxKTcMOFPQXVms4SPM0?purpose=inline)

[管理界面](https://images.openai.com/static-rsc-4/esdWa90WjIfDEpxYHs0aaCWWhG-QAc61U1UrY9zWComme2g6MT5dx9r9_aaw_uzuVQ1D6PuXkjdMvJYqZoeXq7mi9YNimyaXtABQQv_Z6_pgB21W_8pYuEJmu-Zsb1QxQuxj_Fe9QUzgQvTGUizlxSA-xf4aREzgyLOy5Z8rWnA?purpose=inline)

[Oracle Cloud Infrastructure 技術概要 - Speaker Deck](https://images.openai.com/static-rsc-4/KKsmfOxNS1qJPgpM-l1uPBov0BNaSvAeYO2nqEw0Z6xUOPcUySc7zYONG_dCTXvu5NWpPSNantqvw6SQWEh_gyfIU4opcM4Hg9g-OJ-uyz9juKcRw5Z4ccboD41sgSnlfVu6sgJO52JTwuzCaVrkuwznwXsCqgi12C-ax7YH3Co?purpose=inline)

8

A Oracle Cloud Infrastructure (OCI) é a plataforma de nuvem da Oracle para executar aplicações, bancos de dados, redes, armazenamento e cargas de trabalho de IA.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.oracle.com\&sz=32)

Oracle Brasil

+1



| Nome                                      | Descrição                                                                                                                   |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| OCI                                       | Plataforma de serviços de infraestrutura e plataforma em nuvem da Oracle.                                                   |
| Compute                                   | Serviço para provisionar máquinas virtuais e instâncias bare metal.                                                         |
| Virtual Cloud Network (VCN)               | Rede virtual isolada para organizar recursos e conectividade na OCI.                                                        |
| Subnet                                    | Segmento de rede dentro de uma VCN, associado a regras e recursos de conectividade.                                         |
| Security Lists                            | Regras de segurança aplicadas no nível da subnet.                                                                           |
| Network Security Groups (NSG)             | Conjuntos de regras de tráfego aplicados a grupos de recursos de rede.                                                      |
| Internet Gateway                          | Permite conectividade entre uma VCN e a internet pública, conforme rotas e regras.                                          |
| NAT Gateway                               | Permite que recursos privados iniciem conexões externas sem precisar de endereço público para receber conexões da internet. |
| Service Gateway                           | Permite acesso privado a serviços Oracle suportados sem encaminhar o tráfego pela internet pública.                         |
| FastConnect                               | Conectividade privada dedicada entre uma rede externa e a OCI.                                                              |
| Site-to-Site VPN                          | Conexão criptografada entre a rede corporativa e a OCI por VPN.                                                             |
| Object Storage                            | Armazenamento de objetos para arquivos, backups, logs e grandes volumes de dados.                                           |
| Block Volume                              | Volumes de armazenamento em bloco anexados a instâncias.                                                                    |
| File Storage                              | Sistema de arquivos compartilhado gerenciado.                                                                               |
| Archive Storage                           | Armazenamento de baixo custo destinado a dados acessados raramente.                                                         |
| Load Balancer                             | Distribui requisições entre servidores ou aplicações.                                                                       |
| OCI IAM                                   | Gerenciamento de identidade, usuários, grupos, políticas e permissões.                                                      |
| Compartments                              | Estruturas lógicas para organizar e controlar o acesso a recursos na OCI.                                                   |
| Regions                                   | Áreas geográficas que contêm recursos de nuvem da Oracle.                                                                   |
| Availability Domains                      | Domínios de disponibilidade isolados dentro de determinadas regiões da OCI.                                                 |
| Fault Domains                             | Agrupamentos de infraestrutura que ajudam a reduzir o impacto de falhas correlacionadas.                                    |
| OCI Monitoring                            | Coleta métricas e permite configurar alarmes sobre recursos monitorados.                                                    |
| OCI Logging                               | Centraliza logs de recursos e aplicações compatíveis.                                                                       |
| OCI Cloud Guard                           | Detecta configurações inseguras e atividades suspeitas em ambientes OCI.                                                    |
| OCI Vault                                 | Serviço para gerenciar chaves criptográficas e segredos.                                                                    |
| OCI Container Engine for Kubernetes (OKE) | Serviço gerenciado para executar clusters Kubernetes.                                                                       |
| OCI Functions                             | Plataforma serverless para executar código em resposta a eventos ou chamadas.                                               |
| OCI API Gateway                           | Gerencia e protege pontos de entrada de APIs.                                                                               |
| OCI DevOps                                | Serviços para apoiar pipelines de integração e entrega contínuas e implantação de aplicações.                               |
| Oracle Cloud Free Tier                    | Oferta com recursos gratuitos, sujeitos aos limites e condições vigentes.                                                   |

## 4. Sistemas operacionais, virtualização e infraestrutura local

| Nome                                | Descrição                                                                                                                    |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Oracle Linux                        | Distribuição Linux empresarial utilizada em servidores, bancos de dados e aplicações corporativas.                           |
| Oracle Linux 8                      | Versão da distribuição Linux que pode hospedar o Oracle Database 19c, conforme os requisitos de certificação e configuração. |
| Oracle Linux KVM                    | Tecnologia de virtualização baseada em Kernel-based Virtual Machine, utilizada para executar máquinas virtuais.              |
| Oracle Linux Virtualization Manager | Plataforma de gerenciamento de ambientes de virtualização baseados em KVM.                                                   |
| Oracle VirtualBox                   | Software de virtualização para executar sistemas operacionais convidados em máquinas virtuais.                               |
| Oracle Solaris                      | Sistema operacional Unix da Oracle, utilizado em determinados ambientes empresariais e legados.                              |
| Oracle Solaris Cluster              | Solução de clustering para aumentar a disponibilidade de aplicações e serviços em ambientes Solaris suportados.              |
| Oracle Linux Automation Manager     | Ferramenta de automação de operações e configurações de infraestrutura Linux.                                                |
| Oracle OS Management Hub            | Serviço para gerenciamento de atualizações e sistemas operacionais em ambientes suportados.                                  |
| Oracle Private Cloud Appliance      | Plataforma integrada de infraestrutura para executar cargas de trabalho em ambiente de nuvem privada.                        |
| Oracle Cloud\@Customer              | Família de ofertas que disponibiliza determinados serviços Oracle em infraestrutura instalada no ambiente do cliente.        |

[image](https://www.google.com/s2/favicons?domain=https://apexapps.oracle.com\&sz=32)

Oracle

+2

## 5. Hardware e sistemas projetados

[Exadata Platform](https://images.openai.com/static-rsc-4/ZD8CctkAcGTUjuF406p5NOJTp4XMjy6aTuyYuH1jZfPrjhDrer9-6b_fHQkhuHtES0yb2SmzDgGuYmW-p7Be_HxozD-WonAXCB78OFg-J3wOTg7QYyRtQtHkGbOwItUvnIdBG-T_-mKyaqdcQm6w8nDthOYiH9fa88Ownn5r0wc?purpose=inline)

Oracle Exadata

Plataforma integrada de servidores, armazenamento, rede e software, otimizada para cargas de trabalho Oracle Database. Pode ser implantada localmente ou consumida em modalidades de nuvem.

[Oda-X9-2ha Small Database Machine Server - Rack Server and Computer Parts price](https://images.openai.com/static-rsc-4/2PP0MQyvOlWk4rM7zayiwU-eWoJtv44Bm52t8xEjWVCnD4-8C2p3dLxibkPeAlDoIad9kzQgxP5nw0hWmRwqw1zFjzWi7x7Nc4iCanMOqosP3TQi2mKVMd7vHr4dMJ4tGxP1zh337kJ5fGgg3Z6MuJ8u_3WSl7lFPkE8Axj7uuQ?purpose=inline)

Oracle Database Appliance (ODA)

Sistema integrado que simplifica a implantação e a operação de determinados ambientes Oracle Database.

[1.2 Components](https://images.openai.com/static-rsc-4/8SzYSURAtejQ8JHOhQ4_TceJa_zxov4_I3aTDSW5Ig7ZPuww6BWalZta8eob3yFIsLVHB_bSdRUwUOsjG5-093bEaOSi3JKWw2vv_83Qcbpj3VwueQJJEPS4wX66E0CC_LXyGaEakzAR2CZUJynpTSTOI49qCQJBNIUg5ZOYPzk?purpose=inline)

Oracle Private Cloud Appliance

Infraestrutura integrada voltada à execução de aplicações empresariais em nuvem privada.

| Nome                            | Descrição                                                                                                                                |
| ------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Oracle Exadata Database Service | Serviço de banco de dados baseado na plataforma Exadata, disponível em modalidades específicas de implantação.                           |
| Oracle Exadata Cloud\@Customer  | Oferta que permite executar a plataforma Exadata no ambiente do cliente com gerenciamento e modelo de consumo de nuvem.                  |
| Oracle SuperCluster             | Sistema integrado que combina recursos de computação, armazenamento e software Oracle para determinadas cargas de trabalho empresariais. |
| Oracle ZFS Storage Appliance    | Sistema de armazenamento empresarial para cargas de trabalho e necessidades de proteção de dados compatíveis.                            |

[image](https://www.google.com/s2/favicons?domain=https://www.oracle.com\&sz=32)

Oracle Brasil

+1

## 6. Middleware, servidores de aplicação e integração

Middleware é a camada de software que conecta aplicações, serviços, sistemas e fontes de dados. A família Oracle Fusion Middleware inclui tecnologias de desenvolvimento, integração, segurança e execução de aplicações.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://docs.oracle.com\&sz=32)

Fusion Middleware

+1



| Nome                                         | Descrição                                                                                                             |
| -------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| Oracle WebLogic Server                       | Servidor de aplicações Java empresarial para hospedar aplicações e serviços.                                          |
| Oracle Fusion Middleware                     | Família de produtos para desenvolvimento, integração, segurança e gerenciamento de aplicações empresariais.           |
| Oracle SOA Suite                             | Plataforma para integração de aplicações e implementação de arquiteturas orientadas a serviços (SOA).                 |
| Oracle Integration                           | Plataforma de integração para conectar aplicações, APIs e sistemas locais ou em nuvem.                                |
| Oracle GoldenGate                            | Tecnologia de replicação de dados que também pode apoiar integrações entre sistemas.                                  |
| Oracle Data Integrator (ODI)                 | Plataforma de integração e transformação de dados, utilizada em processos ETL e ELT.                                  |
| Oracle Service Bus (OSB)                     | Camada de mediação e integração de serviços, usada para roteamento, transformação e políticas de comunicação.         |
| Oracle Business Process Management (BPM)     | Tecnologias para modelar, executar e monitorar processos de negócio, conforme a edição e versão.                      |
| Oracle API Gateway                           | Componente para intermediar, proteger e controlar chamadas a APIs.                                                    |
| Oracle Managed File Transfer (MFT)           | Solução de transferência gerenciada de arquivos entre sistemas e organizações.                                        |
| Oracle Forms                                 | Tecnologia para desenvolver aplicações empresariais baseadas em formulários e banco de dados.                         |
| Oracle Reports                               | Ferramenta tradicional de geração e apresentação de relatórios empresariais.                                          |
| Oracle Enterprise Manager                    | Plataforma para monitorar e administrar ambientes Oracle, incluindo bancos de dados e outros componentes compatíveis. |
| Oracle WebCenter                             | Família de soluções para portais, conteúdo empresarial e colaboração.                                                 |
| Oracle Transaction Manager for Microservices | Tecnologia para coordenar transações distribuídas em arquiteturas de microsserviços compatíveis.                      |

## 7. Desenvolvimento de software, linguagens e ferramentas

| Nome                                           | Descrição                                                                                                                                 |
| ---------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- |
| Java                                           | Linguagem e plataforma de programação amplamente utilizadas no desenvolvimento de aplicações corporativas.                                |
| Java SE                                        | Plataforma Java Standard Edition, com APIs e recursos fundamentais para aplicações Java.                                                  |
| Java Development Kit (JDK)                     | Kit de desenvolvimento que inclui ferramentas para compilar, depurar e executar programas Java.                                           |
| Java Virtual Machine (JVM)                     | Ambiente de execução responsável por executar bytecode Java.                                                                              |
| Oracle GraalVM                                 | Distribuição de runtime e tecnologias para executar e otimizar aplicações, com suporte a recursos de compilação nativa conforme a edição. |
| Oracle JDeveloper                              | Ambiente de desenvolvimento integrado para tecnologias Java e Oracle.                                                                     |
| Oracle Application Development Framework (ADF) | Framework empresarial para desenvolvimento de aplicações Java com componentes e serviços integrados.                                      |
| Oracle Application Express (APEX)              | Plataforma low-code para criar aplicações web apoiadas em Oracle Database.                                                                |
| Oracle JET                                     | Oracle JavaScript Extension Toolkit, conjunto de ferramentas para construir interfaces web com JavaScript e tecnologias web.              |
| Oracle Visual Builder                          | Plataforma visual para desenvolver aplicações web e mobile e integrar serviços, conforme a oferta disponível.                             |
| Oracle SQL Developer                           | Ambiente gráfico para trabalhar com SQL, PL/SQL e objetos de bancos Oracle.                                                               |
| Oracle SQLcl                                   | Ferramenta de linha de comando para executar SQL, PL/SQL e scripts administrativos.                                                       |
| Oracle REST Data Services (ORDS)               | Serviço que disponibiliza APIs REST e conecta aplicações a dados e recursos Oracle.                                                       |
| Oracle Developer Tools for Visual Studio       | Ferramentas de desenvolvimento e integração para trabalhar com tecnologias Oracle no Visual Studio, conforme a versão.                    |
| Oracle Cloud Infrastructure DevOps             | Serviços para automatizar processos de build, entrega e implantação na OCI.                                                               |

[image](https://www.google.com/s2/favicons?domain=https://docs.oracle.com\&sz=32)

Fusion Middleware

+2

## 8. Aplicações empresariais e sistemas de gestão

As aplicações empresariais Oracle atendem a áreas como finanças, recursos humanos, compras, vendas, manufatura e logística. A suíte Fusion Cloud reúne soluções integradas, enquanto outros produtos atendem empresas que mantêm sistemas tradicionais instalados localmente.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://docs.oracle.com\&sz=32)

Fusion Cloud Applications

+1



| Nome                                           | Descrição                                                                                                            |
| ---------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| Oracle Fusion Cloud Applications               | Conjunto de aplicações empresariais em nuvem para diferentes áreas da organização.                                   |
| Oracle Fusion Cloud ERP                        | Sistema de planejamento de recursos empresariais, com módulos financeiros, compras, projetos e gestão de riscos.     |
| Oracle Fusion Cloud HCM                        | Solução de gestão de capital humano, abrangendo RH, talentos, recrutamento e gestão de pessoas.                      |
| Oracle Fusion Cloud SCM                        | Solução de gestão da cadeia de suprimentos, planejamento, manufatura e logística.                                    |
| Oracle Fusion Cloud CX                         | Conjunto de soluções de experiência do cliente, vendas, marketing e atendimento.                                     |
| Oracle Enterprise Performance Management (EPM) | Soluções para planejamento financeiro, orçamento, previsões, consolidação e relatórios gerenciais.                   |
| Oracle NetSuite                                | Plataforma empresarial em nuvem que integra funções como finanças, operações, estoque e relacionamento com clientes. |
| Oracle E-Business Suite (EBS)                  | Suíte empresarial tradicional com módulos financeiros, logísticos, de RH e outros processos corporativos.            |
| Oracle PeopleSoft                              | Família de aplicações empresariais utilizada em áreas como RH, finanças e administração.                             |
| Oracle JD Edwards EnterpriseOne                | Sistema ERP utilizado em processos financeiros, distribuição, manufatura e operações.                                |
| Oracle Siebel CRM                              | Plataforma de gerenciamento de relacionamento com clientes, utilizada em determinados ambientes corporativos.        |
| Oracle Hyperion / Essbase                      | Família de tecnologias associadas a planejamento, análise multidimensional e consolidação financeira.                |
| Oracle Retail                                  | Soluções empresariais para operações do varejo, incluindo merchandising, estoque e planejamento.                     |
| Oracle Health                                  | Portfólio de soluções tecnológicas para organizações de saúde.                                                       |
| Oracle Hospitality                             | Soluções de tecnologia para hotelaria, hospedagem, alimentação e operações relacionadas.                             |

## 9. Inteligência de negócios, análise de dados e inteligência artificial

| Nome                               | Descrição                                                                                                                      |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| Oracle Analytics Cloud             | Serviço de análise de dados em nuvem para exploração, visualização e geração de relatórios.                                    |
| Oracle Analytics Server            | Plataforma de análise que pode ser implantada em infraestrutura administrada pela organização.                                 |
| Oracle Business Intelligence (OBI) | Família de tecnologias de business intelligence e relatórios empresariais.                                                     |
| Oracle Analytics Publisher         | Tecnologia para produzir e distribuir relatórios formatados e documentos empresariais.                                         |
| Oracle Machine Learning (OML)      | Recursos para desenvolver e executar modelos de aprendizado de máquina com dados Oracle.                                       |
| Oracle Data Science                | Serviços de nuvem para desenvolvimento, treinamento e implantação de modelos de ciência de dados.                              |
| Oracle AI Data Platform            | Plataforma voltada à integração e utilização de dados em soluções analíticas e de inteligência artificial, conforme a oferta.  |
| Oracle AI Services                 | Categoria de serviços de IA da OCI, incluindo recursos disponíveis para visão computacional, linguagem e outras tarefas.       |
| Oracle AI Vector Search            | Recursos de busca vetorial no banco de dados para aplicações de IA generativa e recuperação semântica.                         |
| Oracle Select AI                   | Funcionalidade que permite interagir com dados por linguagem natural e gerar consultas SQL, conforme a configuração suportada. |
| Oracle AI Agents                   | Agentes de IA incorporados a produtos e fluxos de trabalho compatíveis para executar tarefas e apoiar processos.               |
| Oracle Digital Assistant           | Plataforma para construir assistentes conversacionais e experiências baseadas em linguagem natural.                            |
| Oracle Essbase                     | Plataforma analítica multidimensional usada em planejamento, modelagem e análise empresarial.                                  |

[image](https://www.google.com/s2/favicons?domain=https://academy.oracle.com\&sz=32)

Oracle Academy

+2

## 10. Segurança, identidade e controle de acesso

| Nome                                        | Descrição                                                                                                              |
| ------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Oracle Identity and Access Management (IAM) | Conjunto de tecnologias para gerenciar identidades e controlar o acesso a recursos.                                    |
| OCI IAM                                     | Serviço de identidade e autorização para administrar acessos aos recursos da OCI.                                      |
| Oracle Identity Governance                  | Tecnologias de governança de identidades, concessão de acessos e controles de conformidade.                            |
| Oracle Access Management                    | Soluções para autenticação, controle de acesso e gerenciamento de sessões em aplicações compatíveis.                   |
| Oracle Privileged Access Management         | Solução destinada ao gerenciamento e controle de acessos privilegiados.                                                |
| Oracle Key Vault                            | Produto para gerenciamento centralizado de chaves, credenciais e outros materiais criptográficos suportados.           |
| Oracle Audit Vault and Database Firewall    | Solução de segurança para centralizar auditoria de bancos e detectar ou bloquear determinadas atividades suspeitas.    |
| Oracle Data Masking and Subsetting          | Recursos para mascarar dados sensíveis e criar subconjuntos de dados em cenários suportados.                           |
| Oracle Database Vault                       | Controles adicionais para limitar operações privilegiadas no banco de dados.                                           |
| Oracle Data Safe                            | Serviço de avaliação, auditoria e proteção de dados para bancos compatíveis.                                           |
| Oracle Cloud Guard                          | Serviço de detecção de riscos e configurações inseguras na OCI.                                                        |
| OCI Web Application Firewall (WAF)          | Proteção de aplicações web contra determinadas categorias de ataques e tráfego malicioso.                              |
| OCI Security Zones                          | Controles preventivos que aplicam políticas de segurança a recursos em determinados compartimentos.                    |
| Oracle Linux Security                       | Recursos e mecanismos de segurança do sistema operacional Oracle Linux, incluindo atualizações e controles suportados. |

## 11. Monitoramento, desempenho e administração

| Nome                                         | Descrição                                                                                                        |
| -------------------------------------------- | ---------------------------------------------------------------------------------------------------------------- |
| Oracle Enterprise Manager (OEM)              | Ferramenta para monitoramento, administração e diagnóstico de ambientes Oracle.                                  |
| Oracle Cloud Observability and Management    | Categoria de recursos para monitoramento, logs, diagnóstico e gerenciamento de operações na OCI.                 |
| Oracle Cloud Infrastructure Monitoring       | Coleta métricas e permite criar alarmes para monitorar recursos de nuvem.                                        |
| OCI Logging Analytics                        | Serviço para analisar logs e identificar padrões, eventos e problemas operacionais.                              |
| OCI Application Performance Monitoring (APM) | Recursos para observar o desempenho e diagnosticar problemas em aplicações compatíveis.                          |
| Oracle Database Management                   | Recursos para administrar e monitorar bancos de dados, conforme o serviço e o ambiente.                          |
| Oracle Operations Insights                   | Ferramentas para analisar utilização, desempenho e capacidade de recursos de infraestrutura e bancos suportados. |
| Oracle Automatic Workload Repository (AWR)   | Armazena estatísticas que permitem comparar o comportamento do banco em diferentes períodos.                     |
| SQL Tuning Advisor                           | Analisa determinadas instruções SQL e recomenda possíveis melhorias de desempenho.                               |
| SQL Access Advisor                           | Analisa padrões de acesso e pode recomendar estruturas como índices e materialized views, conforme o cenário.    |
| Oracle Trace File Analyzer (TFA)             | Ferramenta para coletar e organizar diagnósticos de ambientes Oracle compatíveis.                                |
| Oracle ORAchk / EXAchk                       | Ferramentas de verificação de configuração e boas práticas para ambientes Oracle compatíveis.                    |

## 12. Serviços profissionais, suporte e capacitação Oracle

Além de software e infraestrutura, a Oracle oferece serviços de consultoria, suporte técnico, treinamento e orientação para adoção das soluções.&#x20;

[image](https://www.google.com/s2/favicons?domain=https://www.oracle.com\&sz=32)

Oracle Brasil

+1



| Nome                                     | Descrição                                                                                                                                    |
| ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| Oracle Consulting                        | Serviços de consultoria para implantação, transformação tecnológica, integração e otimização de soluções.                                    |
| Oracle Premier Support                   | Oferta de suporte técnico e manutenção de produtos cobertos pelo contrato aplicável.                                                         |
| Oracle Customer Success Services         | Serviços voltados à adoção, operação, otimização e obtenção de valor das soluções Oracle.                                                    |
| Oracle University                        | Organização de treinamento e capacitação em tecnologias, produtos e aplicações Oracle.                                                       |
| Oracle MyLearn                           | Plataforma de aprendizagem que disponibiliza conteúdos de treinamento e preparação para certificações.                                       |
| Oracle Certification                     | Programa de certificações que avalia conhecimentos sobre tecnologias e produtos Oracle.                                                      |
| Oracle Cloud Free Tier                   | Oferta de recursos gratuitos da OCI, sujeita a limites, elegibilidade e condições vigentes.                                                  |
| Oracle Support / My Oracle Support (MOS) | Portal e recursos de suporte técnico para clientes elegíveis, incluindo documentação, patches e solicitações de serviço conforme o contrato. |
| Oracle Cloud Marketplace                 | Catálogo de aplicações, imagens, serviços e soluções de parceiros que podem ser utilizadas em ambientes Oracle Cloud compatíveis.            |
| Oracle Financing                         | Soluções de financiamento para aquisições elegíveis, sujeitas à disponibilidade e aprovação.                                                 |

## 13. Conceitos comerciais e modelos de contratação

Estes termos são importantes para compreender como as soluções Oracle são adquiridas, implantadas e mantidas.

| Nome                               | Descrição                                                                                                                     |
| ---------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| On-premises                        | Software executado na infraestrutura administrada pelo próprio cliente.                                                       |
| Cloud Computing                    | Modelo de utilização de recursos computacionais fornecidos como serviços pela nuvem.                                          |
| SaaS — Software as a Service       | Software consumido como serviço, normalmente por assinatura, com a infraestrutura e a aplicação gerenciadas pelo fornecedor.  |
| PaaS — Platform as a Service       | Plataforma gerenciada para desenvolver, executar ou integrar aplicações sem administrar toda a infraestrutura subjacente.     |
| IaaS — Infrastructure as a Service | Recursos de computação, rede e armazenamento disponibilizados como serviços.                                                  |
| BYOL — Bring Your Own License      | Modelo no qual o cliente utiliza licenças próprias em ambientes elegíveis, respeitando as regras de licenciamento aplicáveis. |
| License Metric                     | Unidade de medição utilizada para determinar o licenciamento de um produto, conforme o contrato.                              |
| Named User Plus (NUP)              | Métrica de licenciamento baseada em usuários nomeados e, conforme as regras aplicáveis, dispositivos que acessam o software.  |
| Processor License                  | Métrica de licenciamento baseada em processadores, calculada segundo as regras contratuais da Oracle.                         |
| Support Renewal                    | Renovação do suporte e da manutenção conforme o contrato e a política aplicáveis.                                             |
| Subscription                       | Contrato de acesso a um produto ou serviço durante um período determinado.                                                    |
| Universal Credits                  | Modelo de créditos utilizado em determinadas ofertas de serviços OCI elegíveis.                                               |
| SLA — Service Level Agreement      | Compromisso contratual sobre níveis de serviço, disponibilidade ou outros parâmetros definidos.                               |

Atenção: o licenciamento Oracle depende do produto, da versão, da edição, da infraestrutura e dos termos contratuais. Não é seguro concluir que uma instalação está licenciada apenas porque funciona tecnicamente.

## 14. Mapa de estudo recomendado para DBA Oracle

Considerando o objetivo de desenvolver conhecimento em administração Oracle e preparar-se para as certificações 1Z0-082 e 1Z0-083, esta é uma sequência prática para organizar os conceitos do glossário.

Etapa 1 — Fundamentos do Oracle Database

SQL, PL/SQL, instância, SGA, processos, arquivos de controle, redo logs, tablespaces e usuários.

Etapa 2 — Administração e segurança

Inicialização, parâmetros, privilégios, roles, auditoria, gerenciamento de espaço e manutenção.

Etapa 3 — Backup e recuperação

RMAN, archivelogs, recuperação completa e incompleta, Flashback e estratégias de contingência.

Etapa 4 — Desempenho e diagnóstico

AWR, ADDM, planos de execução, estatísticas, índices, SQL Tuning e análise de gargalos.

Etapa 5 — Alta disponibilidade

Data Guard, RAC, ASM, arquitetura de contingência, failover e recuperação de desastres.

Etapa 6 — Oracle na nuvem

OCI, redes, Compute, armazenamento, IAM, Autonomous Database e serviços de banco em nuvem.

A ordem acima é uma sugestão didática, não uma reprodução literal do programa oficial dos exames. Para conferir os objetivos e os conteúdos vigentes, consulte a documentação e o portal de aprendizagem da Oracle.

## Referências oficiais para consulta

- [Catálogo de produtos Oracle A–Z](https://www.oracle.com/br/products/oracle-a-z.html) — visão geral de produtos e serviços.
- [Documentação Oracle Database](https://docs.oracle.com/en/database/) — documentação técnica dos bancos de dados.
- [Documentação Oracle Fusion Middleware](https://docs.oracle.com/en/middleware/) — servidores de aplicação e integração.
- [Oracle Architecture Center](https://docs.oracle.com/solutions/) — arquiteturas de referência, soluções e exemplos técnicos.
- [Documentação Oracle Cloud Infrastructure](https://docs.oracle.com/en-us/iaas/Content/home.htm) — infraestrutura, redes, segurança e serviços de nuvem.
- [Oracle University](https://education.oracle.com/) — treinamento e certificações.

Este glossário cobre as principais famílias tecnológicas e comerciais da Oracle, mas não todos os produtos, módulos, versões e serviços do catálogo. A nomenclatura e a disponibilidade podem variar ao longo do tempo.