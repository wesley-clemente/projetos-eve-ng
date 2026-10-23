# 🌐 Laboratórios e Topologias de Redes — EVE-NG

<p align="center">
  <img src="https://img.shields.io/badge/Platform-EVE--NG-orange?style=for-the-badge&logo=virtualbox" alt="EVE-NG Platform">
  <img src="https://img.shields.io/badge/Network-MikroTik-blue?style=for-the-badge&logo=mikrotik" alt="MikroTik">
  <img src="https://img.shields.io/badge/Monitoring-Zabbix_7.0-red?style=for-the-badge&logo=zabbix" alt="Zabbix">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status">
</p>

> Coleção de laboratórios e cenários práticos de infraestrutura de redes, monitoramento e roteamento dinâmico desenvolvidos e validados no **EVE-NG**.

---

## 🛠️ Tecnologias e Protocolos

- **Plataforma de Simulação:** EVE-NG
- **Sistemas & Ativos:** Zabbix Server Appliance 7.0, MikroTik RouterOS v7, Linux (Debian/Ubuntu)
- **Protocolos & Serviços:** OSPFv2, Inter-VLAN Routing (Bridge Filtering), DHCP Server, NAT/Masquerade, SNMPv2c/SNMPv3

---

## 📂 Projetos em Destaque

Clique no nome do projeto para ver a **documentação completa com topologia visual**:

| Projeto | Descrição Resumida | Tecnologias Principais | Status |
| :--- | :--- | :--- | :---: |
| 📊 [**Zabbix & SNMP**](./Zabbix/) | Coleta de métricas e monitoramento de ativos Linux via agente SNMP. | Zabbix 7.0, SNMP, Linux | 🟢 Concluído |
| 🏢 [**Rede Matriz & Filial**](./Rede%20Matriz/) | Interligação corporativa L2/L3 com segregação por VLANs e roteamento dinâmico. | MikroTik v7, OSPF, VLANs, NAT | 🟢 Concluído |

---

## 🚀 Como Utilizar estes Laboratórios

1. **Clone o repositório ou baixe os arquivos:**
   ```bash
   git clone [https://github.com/wesley-clemente/projetos-eve-ng.git]
