# Introdução descritiva sobre Banco de Dados

Este guia fornece uma visão geral de alguns dos sistemas de gerenciamento de bancos de dados (SGBDs) mais populares no mercado de trabalho. Ele descreve brevemente os recursos e características principais de cada SGBD.
## Banco de Dados Relacionais (SGBDs RDBMS)

Os bancos de dados relacionais (RDBMS - Relational Database Management Systems) são um tipo de sistema de gerenciamento de banco de dados (SGBD) que se baseiam no modelo de dados relacional. Esse modelo organiza os dados em tabelas com linhas e colunas, formando uma estrutura tabular que é altamente estruturada e organizada. Cada tabela representa uma entidade ou tipo de informação específico, e as relações entre as tabelas são estabelecidas por meio de chaves estrangeiras. 

- **Características Principais Banco de Dados Relacionais**
Aqui estão algumas das características principais dos bancos de dados relacionais: 
  - **Estrutura Tabular:** Os dados são armazenados em tabelas, também conhecidas como relações, onde cada tabela possui um conjunto fixo de colunas com tipos de dados definidos. 
  - **Esquema de Dados:** Os bancos de dados relacionais têm um esquema de dados predefinido que define a estrutura das tabelas, incluindo os tipos de dados das colunas e as restrições de integridade. 
  - **Chaves Primárias e Chaves Estrangeiras:** As chaves primárias são usadas para identificar exclusivamente cada linha em uma tabela, enquanto as chaves estrangeiras estabelecem relações entre tabelas, permitindo a integridade referencial. 
  - **Transações ACID:** Os SGBDs relacionais seguem o conceito ACID (Atomicidade, Consistência, Isolamento e Durabilidade) para garantir a integridade e confiabilidade dos dados em transações. 
  - **Linguagem SQL:** A consulta e manipulação de dados em bancos de dados relacionais são realizadas usando a linguagem SQL (Structured Query Language). 

Dois dos bancos de dados relacionais mais populares são o **Oracle Database** e o **Microsoft SQL Server**. Vamos descrever brevemente cada um deles:

### *Oracle Database*

Desenvolvido pela Oracle Corporation, é um dos SGBDs mais conhecidos e amplamente utilizados no mundo empresarial. Ele é conhecido por sua escalabilidade, confiabilidade e recursos avançados para gerenciamento de dados.

- **Características Principais SGBD Oracle Database:**
  - **Arquitetura Cliente-Servidor -** O Oracle Database opera em um ambiente cliente-servidor, permitindo que vários clientes acessem o banco de dados centralizado. 
  - **Suporte a Transações -** Oferece suporte a transações ACID (Atomicidade, Consistência, Isolamento e Durabilidade), garantindo a integridade dos dados.
  - **Recursos Avançados de Consulta -** Possui uma linguagem de consulta SQL robusta e oferece recursos avançados, como particionamento de tabelas e otimização de consultas. 
  - **Alta Disponibilidade -** Oferece opções para alta disponibilidade, como replicação e failover. 
  - **Segurança Avançada -** Fornecer recursos de segurança robustos, incluindo controle de acesso, auditoria e criptografia. 

### *Microsoft SQL Server*

É um SGBD desenvolvido pela Microsoft. Ele é amplamente utilizado em ambientes corporativos e integra-se bem com outras tecnologias da Microsoft, como o Windows Server e o .NET Framework. 

- **Características Principais de Microsoft SQL Server:**
  - **Integração com Plataforma Microsoft -** O SQL Server é conhecido por sua integração perfeita com o ecossistema Microsoft, tornando-o uma escolha popular para organizações que já utilizam outras tecnologias da Microsoft. 
  - **Recursos de Business Intelligence -** Oferece recursos avançados de business intelligence, como integração de dados, relatórios e análise de dados. 
  - **Serviços em Nuvem -** O SQL Server também está disponível como um serviço em nuvem na plataforma Microsoft Azure, permitindo a escalabilidade e flexibilidade do banco de dados. 
  - **Segurança e Auditoria -** Possui recursos avançados de segurança, incluindo autenticação, autorização, criptografia e auditoria de dados. 
  - **Ferramentas de Desenvolvimento -** A Microsoft oferece um conjunto de ferramentas de desenvolvimento, como o SQL Server Management Studio (SSMS), que facilitam a administração e o desenvolvimento de bancos de dados SQL Server. 
#### Outros Banco de Dados Relacionais (SGBDs RDBMS)


Além dos SGBDs destacados, existem outros SGBD NoSQL amplamente utilizados no mercado, incluindo:
- **MySQL -** Um SGBD de código aberto amplamente utilizado, conhecido por sua velocidade e facilidade de uso.
- **PostgreSQL -** Outro SGBD de código aberto com uma forte ênfase em conformidade com padrões e recursos avançados.
- **SQLite -** Um SGBD leve e incorporado que não requer um servidor separado, adequado para aplicativos móveis e de desktop.

Importante lembrar que no mercado de trabalho, existem vários sistemas de gerenciamento de bancos de dados relacionais (SGBDs RDBMS) amplamente utilizados para armazenar, recuperar e gerenciar dados de forma eficiente.
Lembre-se de que os bancos de dados relacionais são ideais para cenários em que a estrutura dos dados é bem definida e as relações entre os dados são fundamentais. Eles são especialmente úteis para aplicações que requerem consistência e integridade de dados.
## Bancos de Dados Não Relacionais (SGBDs NoSQL)

Além dos bancos de dados relacionais, existem os bancos de dados não relacionais, também conhecidos como NoSQL (Not Only SQL). Esses sistemas de gerenciamento de dados são projetados para lidar com tipos de dados não estruturados ou semi-estruturados e oferecem flexibilidade em termos de esquema de dados.

- **Características Principais sobre Bancos de Dados Não Relacionais**
Aqui estão algumas das características principais dos bancos de dados NoSQL:
  - **Modelagem Flexível:** Os bancos de dados NoSQL permitem armazenar dados em formatos variados, incluindo documentos, gráficos, pares chave-valor, famílias de colunas e muito mais. Isso oferece flexibilidade na modelagem de dados.
  - **Esquema Dinâmico:** Ao contrário dos bancos de dados relacionais, os bancos de dados NoSQL geralmente não exigem um esquema de dados rígido e predefinido. Isso permite adicionar campos ou estruturas de dados conforme necessário.
  - **Alta Escalabilidade:** Muitos bancos de dados NoSQL são altamente escaláveis horizontalmente, o que significa que podem lidar com grandes volumes de dados distribuídos em vários servidores.
  - **Desempenho:** Os bancos de dados NoSQL são frequentemente otimizados para operações de leitura e gravação em grande escala, tornando-os adequados para aplicativos de alta demanda.
  - **Uso de Linguagem Própria:** Cada categoria de banco de dados NoSQL pode ter sua própria linguagem de consulta e API, adaptada às necessidades específicas do tipo de dado armazenado.

#### Categorias de Bancos de Dados NoSQL
Existem várias categorias de bancos de dados NoSQL, cada uma adequada para diferentes tipos de aplicativos e casos de uso:

1. **Bancos de Dados de Documentos:** Armazenam dados em documentos semiestruturados, geralmente em formatos como JSON ou BSON. Exemplo: MongoDB.

2. **Bancos de Dados de Colunas:** Organizam dados em colunas em vez de linhas, o que é eficiente para consultas analíticas. Exemplo: Cassandra.

3. **Bancos de Dados de Grafos:** Projetados para armazenar dados relacionais, como redes sociais ou sistemas de recomendação. Exemplo: Neo4j.

4. **Bancos de Dados de Pares Chave-Valor:** Armazenam dados como pares de chave-valor simples. Exemplo: Redis.

Dois dos principais bancos de dados não relacionais amplamente utilizados são o **MongoDB** e o **Cassandra**. Aqui está uma breve descrição de cada um deles:

### *MongoDB*

   - **Características Principais do MongoDB**: 
     - Armazena dados em documentos BSON (Binary JSON), que são flexíveis e não requerem um esquema rígido.
     - Adequado para dados não estruturados ou semi-estruturados.
     - Suporta consultas avançadas, índices e agregações.
     - Escalabilidade horizontal fácil de alcançar.
     - Usado em uma variedade de aplicativos, incluindo aplicativos da web, análise de big data e muito mais.

### *Cassandra*
   
   É um banco de dados NoSQL escalável e distribuído, conhecido como um banco de dados de coluna amplamente distribuído.
   
   - **Características Principais do Cassandra**:
     - Projetado para lidar com grandes volumes de dados distribuídos em clusters de servidores.
     - Oferece alta disponibilidade e tolerância a falhas.
     - Escalabilidade linear, o que significa que você pode adicionar facilmente mais nós ao cluster.
     - Adequado para aplicativos que requerem baixa latência e alta disponibilidade, como aplicativos de IoT, sistemas de rastreamento e muito mais.


#### Outros Bancos de Dados Não Relacionais (SGBDs NoSQL)
Além dos SGBDs destacados, existem outros SGBD NoSQL amplamente utilizados no mercado, incluindo:
- **IBM Db2 -** Um SGBD corporativo desenvolvido pela IBM com suporte a mainframes e tecnologias de análise avançada. 
- **Redis -** Um SGBD NoSQL em memória usado para armazenamento em cache e processamento de dados em tempo real. 
- **Amazon Aurora -** Um SGBD oferecido pela Amazon Web Services (AWS) que é compatível com MySQL e PostgreSQL e projetado para alta disponibilidade e escalabilidade na nuvem. 
- **Neo4j -** Um banco de dados de grafos que permite a modelagem e consulta de dados relacionais complexos.

Importante lembrar que no mercado de trabalho, existem vários sistemas de gerenciamento de bancos de dados não relacionais (SGBDs NoSQL) amplamente utilizados para armazenar, recuperar e gerenciar dados de forma eficiente.
Os bancos de dados NoSQL são ideais para cenários em que a estrutura dos dados é variável, os volumes de dados são grandes e a flexibilidade é necessária. Eles são frequentemente usados em aplicativos da web, análise de big data, IoT e muito mais.

#### Como Escolher um SGBD

É importante observar que existem muitos outros SGBDs disponíveis no mercado, cada um com suas próprias características e casos de uso específicos.
A escolha do SGBD dependerá das necessidades específicas do projeto, como o tipo de dados a serem armazenados, a escala de operação, os requisitos de desempenho e os recursos desejados. Cada SGBD tem suas próprias vantagens e casos de uso ideais.

---