# Resumo-do-lab
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO
Foi aprendido como mecher na interface do Azure.

# Desafio de Projeto: Criando e Gerenciando Máquinas Virtuais na Microsoft Azure

Este repositório contém a documentação e os registros práticos do laboratório focado na criação, configuração e acesso a Máquinas Virtuais (VMs) na plataforma Microsoft Azure, como parte dos objetivos de aprendizado do módulo.

---

## 🎯 Objetivos de Aprendizagem
- Aplicar conceitos de computação em nuvem na prática através do Portal do Azure.
- Realizar o provisionamento e configuração de uma Máquina Virtual (Windows/Linux).
- Documentar processos técnicos de forma clara, estruturada e profissional.
- Utilizar o Git e o GitHub para versionamento e compartilhamento de documentação técnica.

---

## 🛠️ Ferramentas e Recursos Utilizados
- **Microsoft Azure Portal:** Plataforma de nuvem para provisionamento de recursos.
- **Git & GitHub:** Controle de versão e hospedagem da documentação.
- **Markdown:** Linguagem de marcação utilizada para a formatação do README.

---

## 📝 Passo a Passo da Execução

### 1. Acesso ao Portal do Azure e Criação do Recurso
- Acesso ao [Portal do Azure](https://portal.azure.com) utilizando credenciais válidas.
- Navegação até a opção **Máquinas Virtuais (Virtual Machines)** e seleção de **Criar > Máquina virtual do Azure**.

### 2. Configurações Básicas da Máquina Virtual
- **Assinatura e Grupo de Recursos:** Definição do grupo de recursos dedicado ao laboratório (ex: `rg-lab-azure`).
- **Detalhes da Instância:**
  - Nome da VM: (Ex: `VM-Lab-Windows` / `VM-Lab-Linux`)
  - Região: (Ex: `East US` ou região recomendada)
  - Opções de Disponibilidade: Sem redundância de infraestrutura necessária para este laboratório.
  - Imagem: Seleção do sistema operacional base (ex: *Windows Server / Ubuntu Server*).
- **Conta de Administrador:**
  - Nome de usuário e senha configurados para acesso seguro.
- **Portas de Entrada Públicas:**
  - Liberação de portas essenciais (ex: RDP - Porta 3389 para Windows / SSH - Porta 22 para Linux).

### 3. Discos, Rede e Avançado
- Revisão das configurações padrão de discos (Standard SSD / Premium SSD).
- Configuração de rede virtual (VNet), sub-rede e IP público associado.

### 4. Validação e Criação
- Execução da validação final (*Validation passed*).
- Clique em **Criar** e acompanhamento do provisionamento dos recursos.

### 5. Conexão e Validação do Ambiente
- Obtenção do endereço IP público da máquina virtual criada.
- Conexão remota utilizando **RDP** (para Windows) ou **SSH** (para Linux) para validar o funcionamento correto do ambiente provisionado.
