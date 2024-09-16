# Resumo do LAB - Tipos Serviços Nuvem
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do LAB na DIO.

## 🚀 Resumo sobre os Tipos de Serviços de Nuvem

A computação em nuvem oferece diferentes tipos de serviços que permitem às empresas e indivíduos armazenar e processar dados de maneira flexível e escalável, sem a necessidade de servidores físicos. Existem três principais modelos de serviço:

- **Software como Serviço (SaaS):** Permite o uso de aplicativos via navegador, sem a necessidade de se preocupar com a infraestrutura. Exemplos incluem Google Docs e Microsoft 365.
  -  Vantagens: facilidade de uso, baixo custo e atualizações automáticas.
   
- **Plataforma como Serviço (PaaS):** Fornece uma plataforma para o desenvolvimento e implantação de aplicativos. Exemplos: Google App Engine e AWS Elastic Beanstalk.
  - Vantagens: acelera o desenvolvimento e permite foco nos aplicativos.
   
- **Infraestrutura como Serviço (IaaS):** Oferece recursos virtualizados, como servidores e armazenamento. Exemplos: Amazon EC2 e Google Compute Engine.
  - Vantagens: maior flexibilidade e controle sobre a infraestrutura.

Além desses, há outros tipos de nuvem, como a **nuvem pública** (compartilhada por vários usuários), **nuvem privada** (exclusiva para uma organização) e **nuvem híbrida** (combina os dois modelos). A escolha do serviço ideal depende do orçamento, do nível de controle desejado e da complexidade do aplicativo.

## 🚀 Resumo sobre o Modelo de Responsabilidade Compartilhada

O **modelo de responsabilidade compartilhada** é um princípio fundamental da computação em nuvem, no qual as responsabilidades pela segurança e gestão dos serviços são divididas entre o provedor de nuvem e o cliente. A divisão de tarefas varia dependendo do tipo de serviço em uso (SaaS, PaaS ou IaaS), mas, em geral, funciona assim:

- **Software como Serviço (SaaS):** 
   - **Provedor de nuvem:** É responsável por gerenciar tudo, incluindo a segurança dos aplicativos, servidores, redes e armazenamento. Ele garante que o software esteja disponível e seguro.
   - **Cliente:** Deve gerenciar o acesso aos dados e garantir a segurança das informações inseridas, como definir quem pode usar o serviço, controlar senhas e autenticação.

- **Plataforma como Serviço (PaaS):**
   - **Provedor de nuvem:** Cuida da infraestrutura subjacente, como servidores, armazenamento e redes, além do ambiente de execução dos aplicativos.
   - **Cliente:** É responsável pelo desenvolvimento, gerenciamento e segurança do código e dos aplicativos que desenvolve na plataforma.

- **Infraestrutura como Serviço (IaaS):**
   - **Provedor de nuvem:** É responsável por fornecer e proteger os componentes básicos de infraestrutura (hardware, servidores, redes, armazenamento físico).
   - **Cliente:** Tem a responsabilidade de gerenciar o sistema operacional, as aplicações, as redes virtuais e garantir a segurança dos dados que estão armazenados ou em trânsito.

### Exemplo de divisão de responsabilidades:
- **Provedor de nuvem:** Segurança física dos data centers, controle de hardware, patches de rede.
- **Cliente:** Configuração segura dos serviços, gestão de identidades e acessos, proteção de dados, backup e recuperação.

[Responsabilidade compartilhada na nuvem - No Docs da Microsoft](https://learn.microsoft.com/pt-br/azure/security/fundamentals/shared-responsibility#division-of-responsibility)
