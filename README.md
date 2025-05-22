# ☁️ Criando VMs na Azure - Laboratório Hands-On  

## 📌 Objetivo  
Este laboratório tem como objetivo ensinar **como criar e configurar máquinas virtuais (VMs) na plataforma Microsoft Azure**, explorando opções de **escalabilidade, segurança e gerenciamento** de instâncias na nuvem.  

---

## 📝 O que você vai aprender?  
✅ Criar uma máquina virtual no **Portal Azure**  
✅ Escolher o **tipo de VM adequado** para seu ambiente  
✅ Configurar **rede, armazenamento e sistema operacional**  
✅ Gerenciar **acesso remoto (SSH/RDP)** e segurança  
✅ Monitorar e **escalar recursos** conforme a demanda  

---

## 🔗 **Links Úteis**  
- 🔹 **Portal do Azure**: [Microsoft Azure](https://portal.azure.com/)  
- 🔹 **Documentação Oficial**: [Azure VMs](https://learn.microsoft.com/pt-br/azure/virtual-machines/)  
- 🔹 **Certificações Microsoft**: [Microsoft Learn](https://learn.microsoft.com/pt-br/certifications/)  

---

🚀 Passo a Passo: Criando uma VM na Azure
1️⃣ Acesse o portal do Azure e faça login com sua conta. 2️⃣ Navegue até "Máquinas Virtuais" no menu lateral. 3️⃣ Clique em "Criar" e selecione "Máquina Virtual". 4️⃣ Escolha as configurações:

Sistema operacional (Linux/Windows)

Tamanho da VM (CPU, memória)

Rede e armazenamento

Região do Datacenter 5️⃣ Configure acesso remoto:

🔐 Para Linux: habilite SSH

🖥️ Para Windows: habilite RDP 6️⃣ Finalize e implemente a VM! 🎉

💻 Criando uma VM via CLI (Azure CLI)
Se preferir, você pode criar uma VM pelo terminal, usando Azure CLI:

bash
az login
az vm create \
  --resource-group MeuGrupoAzure \
  --name MinhaVM \
  --image UbuntuLTS \
  --admin-username azureuser \
  --generate-ssh-keys
📈 Monitoramento e Gerenciamento da VM
Após criar a VM, gerencie seus recursos pelo Azure Monitor e Azure Security Center para garantir segurança, desempenho e escalabilidade.

🔹 Monitoramento: az vm list --show-details 🔹 Parar VM: az vm stop --name MinhaVM --resource-group MeuGrupoAzure 🔹 Excluir VM: az vm delete --name MinhaVM --resource-group MeuGrupoAzure --yes

🤝 Contribuições
Se quiser aprimorar este laboratório, adicionar automações ou compartilhar melhorias, sinta-se à vontade para abrir um Pull Request! 💙

📌 Este repositório ajudará você a dominar a criação de VMs na Microsoft Azure! 🚀🔥
