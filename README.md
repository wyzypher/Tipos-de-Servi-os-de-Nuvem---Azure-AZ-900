# ☁️ Tipos de Serviços de Nuvem - Azure AZ-900

Este repositório contém um resumo dos principais **modelos de serviços de nuvem** (IaaS, PaaS e SaaS), além do **modelo de responsabilidade compartilhada**.  
Também inclui um **overview das máquinas virtuais no Azure** e dicas práticas para estudos.

---

## 🔎 Visão Geral
Na computação em nuvem, os serviços podem ser entregues em diferentes modelos:

- **IaaS (Infraestrutura como Serviço)**  
- **PaaS (Plataforma como Serviço)**  
- **SaaS (Software como Serviço)**  

Cada modelo atende a diferentes necessidades, desde a infraestrutura básica até softwares prontos para uso.

---

## 🖥️ IaaS - Infraestrutura como Serviço
A infraestrutura como serviço fornece os blocos fundamentais de TI em um modelo **pay-as-you-go**.

**Estrutura incluída:**
- Servidores e armazenamento  
- Firewall / segurança de rede  
- Planta física / edifício do datacenter  

**Descrição:**  
Permite **alugar servidores, máquinas virtuais, armazenamento, redes e sistemas operacionais** de um provedor de nuvem.  
Ideal para empresas que querem **controle total** sobre os recursos sem manter datacenters físicos.

**Exemplos de uso:**
- Hospedar máquinas virtuais personalizadas  
- Backup e recuperação de desastres  
- Ambientes de teste e desenvolvimento  

---

## ⚙️ PaaS - Plataforma como Serviço
A plataforma como serviço oferece um ambiente pronto para **desenvolvimento e implantação de aplicativos**.

**Estrutura incluída:**
- Servidores e armazenamento  
- Firewall / segurança de rede  
- Planta física do datacenter  
- Sistemas operacionais  
- Ferramentas para desenvolvedores, análise de negócios e gerenciamento de banco de dados  

**Descrição:**  
Permite criar, testar e implantar aplicativos sem se preocupar com o gerenciamento da infraestrutura.  
Focado na **produtividade do desenvolvedor**.

**Exemplos de uso:**
- Aplicações web escaláveis  
- APIs e microserviços  
- Automação de pipelines de CI/CD  

---

## 📱 SaaS - Software como Serviço
O software como serviço entrega **aplicações prontas** pela internet.

**Estrutura incluída:**
- Tudo do IaaS e PaaS  
- Aplicativos hospedados  

**Descrição:**  
O usuário apenas **consome o serviço**, sem precisar gerenciar infraestrutura ou plataforma.  
Exemplos: Microsoft Office 365, Outlook, OneDrive, Google Workspace.

**Exemplos de uso:**
- E-mail e calendários online  
- CRM (Customer Relationship Management)  
- Softwares de produtividade  

---

## 🛡️ Modelo de Responsabilidade Compartilhada
Na nuvem, tanto o **provedor** quanto o **cliente** possuem responsabilidades.

- **IaaS:** mais flexível. O cliente gerencia sistemas operacionais e aplicativos.  
- **PaaS:** o provedor gerencia a plataforma, enquanto o cliente foca no desenvolvimento.  
- **SaaS:** o provedor gerencia tudo. O cliente apenas usa o software em modelo de assinatura.  

---

## 💻 Máquinas Virtuais no Azure - Overview
As **Máquinas Virtuais (VMs)** são um dos recursos mais usados no Azure, permitindo executar sistemas operacionais e aplicativos sob demanda.

**Principais opções de configuração:**
1. **Sistema Operacional:** Windows ou Linux.  
2. **Tamanho da VM:** escolha baseado em CPU, memória e carga de trabalho (Ex: B1s para testes, D-Series para produção).  
3. **Armazenamento:** discos HDD ou SSD, com diferentes níveis de performance.  
4. **Rede:** IP público, balanceadores de carga, grupos de segurança.  
5. **Escalabilidade:** conjunto de VMs em *scale sets* para alta demanda.  

👉 Tudo isso pode ser configurado pelo **Portal do Azure**, **CLI** ou **ARM Templates**.

---

## 💡 Dicas para o Exame e para a Prática
- Grave a diferença:  
  - **IaaS = você gerencia quase tudo**.  
  - **PaaS = foco no desenvolvimento**.  
  - **SaaS = apenas usa o software**.  
- Saiba citar **exemplos reais** (Azure VM = IaaS, Azure App Service = PaaS, Office 365 = SaaS).  
- Para **alta disponibilidade**, sempre configure suas VMs em **zonas de disponibilidade**.  
- Para estudar, use a camada **Free Tier** do Azure e crie VMs de teste (ex.: B1s).  

---

## 📘 Conclusão
Os serviços de nuvem são oferecidos em diferentes níveis (IaaS, PaaS e SaaS) para atender às diversas necessidades de negócio.  
Entender o **modelo de responsabilidade compartilhada** e como configurar **máquinas virtuais no Azure** é essencial para dominar os fundamentos da nuvem e se preparar para o **AZ-900**.

---
