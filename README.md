# Bootcamp_Ferramentas_implantacao
Este repositório fala um pouco sobre o que aprendi durante o modulo Ferramentas de implantação na Azure do Bootcamp Microsoft Azure Essentials da Dio.

# Azure Cloud Shell, CLI do Azure e Azure PowerShell

##  Azure Cloud Shell

O **Azure Cloud Shell** é um terminal de shell baseado em navegador, acessível diretamente pelo **Azure Portal**, que permite interagir com seus recursos no Azure por meio de uma interface de linha de comando. Ele oferece dois ambientes:
- **Bash** (baseado em Linux) ou
- **PowerShell** (baseado em Windows).

### Principais Características:
- **Ambiente persistente**: Você pode armazenar scripts e arquivos no **Azure Storage** associado ao Cloud Shell.
- **CLI do Azure e Azure PowerShell**: Você pode escolher entre usar a **CLI do Azure** para comandos de linha de comando ou o **Azure PowerShell** para administrar seus recursos.
- **Ferramentas pré-instaladas**: Ferramentas populares como Git, Terraform e Ansible já estão prontas para uso.

---

##  CLI do Azure

A **CLI do Azure** é uma interface de linha de comando que permite gerenciar os recursos do Azure diretamente a partir do seu terminal. Ela é compatível com Windows, macOS e Linux, facilitando o gerenciamento de recursos de forma programática ou interativa.

### Casos de Uso:
- **Gerenciar VMs**.
- **Gerenciar Redes e Armazenamento**.
- **Automação**: Integrar scripts da CLI do Azure em pipelines de CI/CD ou outros processos automatizados.

---

##  Azure PowerShell

O **Azure PowerShell** é uma ferramenta baseada no **Windows PowerShell** que permite gerenciar recursos do Azure diretamente da linha de comando, utilizando **cmdlets** (comandos específicos do PowerShell) para interagir com os serviços da plataforma.

### Casos de Uso:
- **Gerenciamento de Recursos**.
- **Automação**.
- **Integrar com Windows**.

---

# Azure Arc

O **Azure Arc** é uma solução que permite estender o gerenciamento e governança de serviços do Azure para ambientes locais, multi-nuvem e de borda. Com ele, você pode gerenciar servidores, Kubernetes, e serviços de dados SQL do Azure em qualquer lugar, como se estivessem rodando no Azure.

### Finalidade:
- **Gerenciar Recursos Híbridos**.
- **Governança e Conformidade Centralizadas**.
- **Serviços de Dados Consistentes**.

### Casos de Uso:
- **Gerenciamento Multi-Nuvem**.
- **Ambientes Locais**.

---

# Azure Resource Manager (ARM) e Modelos do ARM

##  Azure Resource Manager (ARM)

### O que é?
O **Azure Resource Manager (ARM)** é a plataforma de gerenciamento do Azure que permite provisionar, gerenciar e organizar recursos no Azure. Com o ARM, todos os recursos são agrupados em **grupos de recursos**, facilitando a gestão e a aplicação de políticas.

### Principais Características:
- **Gerenciamento em Grupo**.
- **Governança e Controle**.
- **Automação e Infraestrutura como Código**.

---

##  Modelos do ARM

Os **modelos do ARM** são arquivos JSON que definem a infraestrutura e as configurações de recursos que você deseja implementar no Azure. Eles seguem o conceito de **Infraestrutura como Código (IaC)**, permitindo automação de implantação.

### Principais Benefícios:
- **Automação**.
- **Reprodutibilidade**.
- **Infraestrutura Declarativa**.

### Estrutura de um Modelo do ARM:
Um modelo típico de ARM contém seções como:
- **$schema**: A versão do esquema ARM que está sendo usada.
- **contentVersion**: A versão do modelo.
- **resources**: A lista de recursos a serem implantados.
- **parameters**: Valores que podem ser passados para personalizar a implantação.
- **outputs**: Valores retornados após a implantação.

---


