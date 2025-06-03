# MicrosoftAzure-VM-


🚀 Como Criar uma Máquina Virtual no Microsoft Azure

🧰 Pré-requisitos
Conta no Microsoft Azure

Acesso ao portal do Azure

Permissão para criar recursos (assinatura ativa)

📝 Passo a Passo
1. Acesse o Portal do Azure
Vá para: https://portal.azure.com

Faça login com sua conta Microsoft.

2. Crie um Novo Recurso
No menu lateral, clique em "Criar um recurso".

Selecione "Máquina Virtual" na seção de "Computação".

3. Configurar Informações Básicas
Preencha os campos obrigatórios:

Assinatura: escolha sua assinatura ativa.

Grupo de Recursos: crie um novo ou use um existente.

Nome da VM: defina um nome identificável.

Região: selecione a localização do datacenter.

Imagem: escolha o sistema operacional (ex: Ubuntu, Windows Server).

Tamanho: clique em "Alterar tamanho" para escolher o tipo de VM (ex: B1s para uso leve).

Usuário e senha/SSH: configure as credenciais de acesso.

4. Configurar Disco
Escolha o tipo de disco: SSD padrão, SSD premium, ou HDD.

Mantenha o padrão se não tiver necessidade específica.

5. Configurar Rede
Uma rede virtual e um grupo de segurança (firewall) serão criados automaticamente, mas você pode personalizar.

Certifique-se de que a porta 22 (SSH) ou 3389 (RDP) esteja aberta conforme o sistema operacional.

6. Revisar e Criar
Clique em "Revisar + criar".

Verifique se todas as configurações estão corretas.

Clique em "Criar".

7. Acessar a VM
Após a criação:

Vá em "Recursos" e selecione sua VM.

Copie o endereço IP público.

Use SSH ou RDP para se conectar:

Linux: ssh usuario@ip-da-vm

Windows: Conexão de Área de Trabalho Remota (RDP)


🛠️ Recursos Úteis
Documentação oficial do Azure

Azure CLI – para criar VMs via terminal

Calculadora de preços Azure
