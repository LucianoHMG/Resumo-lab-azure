# Introdução ao Azure Cloud

Este documento cobre os fundamentos da Azure Cloud, incluindo a criação de máquinas virtuais, conceitos básicos de segurança e data centers.

## O que é a Azure Cloud?

A Azure Cloud é uma plataforma de computação em nuvem oferecida pela Microsoft, que permite o gerenciamento de uma ampla gama de serviços, como armazenamento, computação, banco de dados e redes. Ela é usada para criar, implantar e gerenciar aplicações e serviços por meio de data centers globais.

## 1. Criação de Máquinas Virtuais (VMs)

As máquinas virtuais (VMs) na Azure são fundamentais para executar aplicações e armazenar dados na nuvem. Elas simulam o funcionamento de um computador físico e são altamente escaláveis.

### Passos básicos para criar uma VM:
1. Acesse o **Portal da Azure** (portal.azure.com).
2. No menu principal, selecione **Máquinas Virtuais** e clique em **Adicionar**.
3. Escolha o sistema operacional, como **Windows** ou **Linux**.
4. Configure o tamanho da VM de acordo com a necessidade (número de CPUs, memória RAM, etc.).
5. Defina as credenciais de acesso e crie a VM.

Após esses passos, a VM estará pronta para ser acessada remotamente e utilizada como um servidor ou ambiente de desenvolvimento.

## 2. Segurança na Azure Cloud

A segurança na Azure Cloud é uma prioridade e está implementada em várias camadas para proteger seus dados e aplicações. Aqui estão alguns dos recursos básicos de segurança:

### **Segurança de Rede:**
- **Grupos de Segurança de Rede (NSG)**: Controlam o tráfego de entrada e saída para suas VMs, funcionando como firewalls para proteger os recursos.
- **VPN (Virtual Private Network)**: Crie conexões seguras entre sua rede local e a nuvem da Azure para proteger o tráfego de dados.

### **Autenticação e Autorização:**
- **Controle de Acesso Baseado em Funções (RBAC)**: Define quem pode acessar e gerenciar os recursos da Azure, garantindo que apenas pessoas autorizadas possam fazer alterações importantes.
- **Azure Active Directory**: Um serviço de identidade e gerenciamento de acesso que permite autenticar usuários e proteger o acesso a aplicativos e dados.

### **Backup e Recuperação:**
- **Azure Backup**: Garante que os dados de suas máquinas virtuais e outros recursos sejam salvos automaticamente e possam ser restaurados em caso de falha.
- **Azure Site Recovery**: Fornece um plano de recuperação de desastres, replicando VMs e mantendo a continuidade do serviço.

## 3. Data Centers da Azure

A Azure possui uma vasta rede de data centers em todo o mundo, chamados de **Regiões**. Cada região é composta por um ou mais data centers que fornecem serviços de computação, armazenamento e rede.

### Benefícios dos Data Centers da Azure:
- **Alta Disponibilidade**: A Azure garante redundância, replicando dados e serviços em vários locais geográficos para prevenir falhas.
- **Desempenho Global**: A proximidade de seus dados e serviços em relação aos usuários finais melhora o desempenho, minimizando a latência.
- **Escalabilidade**: Os data centers da Azure são projetados para permitir a escalabilidade rápida, aumentando a capacidade de processamento conforme necessário.

### Regiões Populares da Azure:
- **Brasil Sul**: Ideal para quem deseja baixa latência para serviços no Brasil.
- **EUA Leste e Oeste**: Usadas para ampla cobertura e serviços críticos.
- **Europa Ocidental**: Alta demanda em regiões europeias para conformidade com regulamentações como o GDPR.

---

## Resumo

A Azure Cloud oferece ferramentas simples e poderosas para criar máquinas virtuais, garantir a segurança dos seus recursos e utilizar data centers distribuídos globalmente. Com esses conceitos básicos, você pode começar a explorar e utilizar a nuvem da Azure para suas necessidades de computação.

**Referências:**
- [Documentação oficial da Azure](https://docs.microsoft.com/pt-br/azure/)# Resumo-lab-azure
