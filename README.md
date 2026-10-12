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

Desafio de Projeto: Configurando uma Instância de Banco de Dados no Microsoft Azure ☁️🗄️

Repositório criado para documentar a resolução do desafio de projeto da DIO (Digital Innovation One), focado na criação e configuração de uma instância de Banco de Dados Relacional utilizando o Microsoft Azure SQL Database.

🎯 Objetivo do Desafio

O objetivo principal deste laboratório prático foi aplicar os conceitos de computação em nuvem na plataforma Azure, configurando um banco de dados SQL gerenciado, estruturando os recursos em um grupo dedicado e documentando todo o processo técnico de forma clara utilizando o GitHub.

🛠️ Passo a Passo da Implementação

Abaixo estão detalhadas as etapas realizadas durante a criação da instância de banco de dados no Portal do Azure:

1. Acesso ao Azure SQL

No Portal do Azure, navegue até a seção Azure SQL e selecione SQL databases.

Clique no botão + Criar para iniciar o assistente de configuração de um novo banco de dados SQL.

📷 <img width="1698" height="902" alt="image" src="https://github.com/user-attachments/assets/017722ee-5c98-475d-af75-b85f83bed61c" />


2. Configurações Básicas (Noções Básicas)

Na aba Noções Básicas, foram definidos os parâmetros fundamentais do projeto:

Assinatura: Azure subscription 1

Grupo de Recursos: Criado um novo grupo chamado free-db-teste para organizar os recursos correlacionados.

Nome do Banco de Dados: Free-DB-Teste-1

Servidor Lógico: Criado um novo servidor teste-teste-free-db na região Brazil South.

Oferta: Aplicação da oferta gratuita disponível na assinatura para otimização de custos de estudo.

📷 <img width="943" height="836" alt="image" src="https://github.com/user-attachments/assets/609509e2-aa4b-4dba-a5b8-3a058bf0e5d3" />


3. Revisão e Criação (Examinar + criar)

Antes de finalizar a implantação, a aba de resumo validou todas as configurações escolhidas:

Método de Autenticação: Autenticação somente do Microsoft Entra (zleo.gp@gmail.com).

Computação + Armazenamento: General Purpose - Sem servidor - Série Standard (Gen5), 2 vCores, 32 GB de Armazenamento.

Redundância: Armazenamento de backup com redundância local.

📷 <img width="952" height="1142" alt="image" src="https://github.com/user-attachments/assets/02cffcd2-42fe-4b52-92a0-a096ed8c2aa2" />


4. Conclusão da Implantação

Após a validação, o deploy foi executado com sucesso. O Azure provisionou automaticamente os recursos necessários (o banco de dados, a regra de firewall e o servidor lógico associado).

📷 <img width="1305" height="897" alt="image" src="https://github.com/user-attachments/assets/94beab64-3662-477a-b4a5-d73d4acb2957" />


💡 Dicas e Conclusões Técnicas

Gerenciamento Simplificado (PaaS): O uso do Azure SQL Database demonstra na prática as vantagens do modelo PaaS (Platform as a Service), onde a Microsoft gerencia toda a infraestrutura subjacente, backups e alta disponibilidade, permitindo que o desenvolvedor foque totalmente na modelagem e nos dados.

Organização de Recursos: Utilizar Grupos de Recursos facilita drasticamente o ciclo de vida dos projetos em nuvem, permitindo monitorar custos, aplicar políticas e excluir todos os componentes associados de forma limpa quando necessário.

📁 Estrutura do Repositório

├── images/             # Contém as capturas de tela do processo
└── README.md           # Documentação principal do desafio




