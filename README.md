# Simulação de Redes

## 📌 Descrição do Projeto

Este projeto consiste em uma **simulação de rede de computadores desenvolvida no Cisco Packet Tracer**, com o objetivo de aplicar, na prática, os principais conceitos de **roteamento, endereçamento IP e conectividade entre redes distintas**.

A atividade simula um cenário realista de interligação entre múltiplas redes locais (LANs) por meio de **roteadores**, incluindo um **roteador de ISP**, permitindo a comunicação entre diferentes localidades e validando a configuração através de testes de conectividade (ping).

---

## 🗺️ Topologia da Rede

A topologia é composta por:

* Múltiplas **LANs** representando diferentes localidades
* **Roteadores intermediários** para interconexão das redes
* Um **roteador ISP**, simulando acesso externo
* Computadores finais para validação da comunicação

A imagem `TOPOLOGIA.png` apresenta a visão geral da estrutura da rede.

---

## ⚙️ Funcionalidades e Configurações

* Configuração manual de **endereços IP**
* Configuração de **interfaces de rede** nos roteadores
* Implementação de **roteamento** entre redes
* Comunicação entre hosts de diferentes LANs
* Testes de conectividade utilizando **PING**

As imagens de configuração demonstram os parâmetros aplicados em cada roteador:

* Router_CP
* Router_CT
* Router_LD
* Router_ISP

---

## 🧰 Tecnologias Utilizadas

* Cisco Packet Tracer
* Redes de Computadores
* Protocolos de Roteamento (conceitos básicos)
* Endereçamento IP

---

## ▶️ Como Abrir o Projeto

### 1️⃣ Pré-requisitos

* Cisco Packet Tracer instalado

### 2️⃣ Abrir o arquivo

Abra o arquivo abaixo no Packet Tracer:

```
atividade.pkt
```

### 3️⃣ Verificação

* Analise a topologia
* Verifique as configurações dos roteadores
* Execute testes de **ping** entre os computadores para validar a comunicação

---

## 📂 Estrutura do Projeto

```
atividade.pkt
TOPOLOGIA.png
CONFIG Router_CP.png
CONFIG Router_CT.png
CONFIG Router_LD.png
CONFIG Router_ISP.png
PING PC1_CP para PC1_LD e PC1_CT.png
```

---

## 📚 Conceitos Aplicados

* Modelo de redes LAN e WAN
* Interconexão de redes
* Roteamento entre sub-redes
* Diagnóstico de conectividade
* Simulação de infraestrutura de rede

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido como **avaliação formativa prática**, voltado ao aprendizado de **Redes de Computadores**, com foco na compreensão de topologias, roteamento e comunicação entre redes.

---

## 👤 Autor

**Filipe Antonio de Lima Nogueira**
Curso: Engenharia da Computação

---

## 📄 Observações

Este projeto tem caráter educacional e foi desenvolvido para simulação e validação de conceitos de redes, não possuindo integração com ambientes de produção.
