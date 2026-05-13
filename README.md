# Gerenciando Instâncias EC2 na AWS

## 📌 Descrição

Este repositório foi criado como parte do desafio prático da DIO sobre gerenciamento de instâncias EC2 na AWS.

O objetivo deste laboratório foi aplicar conceitos fundamentais da AWS em um ambiente prático, além de documentar os conhecimentos adquiridos durante a experiência.

---

# ☁️ O que é Amazon EC2

O Amazon EC2 (Elastic Compute Cloud) é um serviço da AWS que permite criar e gerenciar máquinas virtuais na nuvem.

Com ele, é possível executar aplicações, hospedar sites, criar ambientes de testes e utilizar diferentes sistemas operacionais sob demanda.

---

# 🎯 Objetivos do Laboratório

* Entender o funcionamento de instâncias EC2
* Aprender a criar e configurar máquinas virtuais na AWS
* Configurar regras básicas de segurança
* Compreender o uso de volumes EBS
* Documentar os processos realizados

---

# 🧠 Conceitos Aprendidos

## Regiões e Availability Zones

A AWS possui regiões distribuídas globalmente. Cada região contém múltiplas Availability Zones para garantir alta disponibilidade.

## IAM

O IAM é utilizado para gerenciamento de usuários, grupos e permissões dentro da AWS.

## EC2

O EC2 permite criar máquinas virtuais escaláveis na nuvem.

## EBS

O Elastic Block Store (EBS) fornece armazenamento persistente para instâncias EC2.

## Security Groups

Funcionam como firewalls virtuais responsáveis por controlar o tráfego de entrada e saída das instâncias.

## S3

O Amazon S3 é um serviço de armazenamento de objetos amplamente utilizado na AWS.

---

# ⚙️ Etapas Realizadas

## 1. Criação da Instância EC2

Durante o laboratório foi realizada:

* Seleção da AMI
* Escolha do tipo de instância
* Configuração da key pair
* Configuração da rede
* Inicialização da instância

---

## 2. Configuração do Security Group

Foram liberadas portas necessárias para acesso:

| Porta | Função |
| ----- | ------ |
| 22    | SSH    |
| 80    | HTTP   |
| 443   | HTTPS  |

---

## 3. Conexão na Instância

Exemplo de conexão via SSH:

```bash
ssh -i minha-chave.pem ec2-user@IP-DA-INSTANCIA
```

---

## 4. Gerenciamento de Volumes EBS

Foi possível entender:

* Como anexar volumes EBS
* Persistência dos dados
* Expansão de armazenamento
* Organização de dados em partições

---

# 💰 Modelo de Cobrança da AWS

A AWS utiliza o modelo pay-as-you-go, onde o usuário paga apenas pelos recursos utilizados.

Também foi estudado o funcionamento do AWS Free Tier e dos alertas de orçamento.

---

# 🔐 Boas Práticas Aprendidas

* Não utilizar a conta root no dia a dia
* Utilizar MFA
* Criar usuários IAM com permissões específicas
* Restringir acessos via Security Groups
* Monitorar custos constantemente

---

# 📷 Capturas de Tela

As imagens do laboratório podem ser adicionadas na pasta:

```txt
/images
```

Exemplos:

* Dashboard EC2
* Criação da instância
* Security Groups
* Volumes EBS
* Instância em execução

---

# 🚀 Tecnologias Utilizadas

* AWS EC2
* AWS IAM
* AWS EBS
* AWS S3
* GitHub
* Markdown

---

# 📚 Aprendizados Finais

Este laboratório permitiu consolidar conhecimentos importantes sobre computação em nuvem utilizando a AWS.

Além da criação de instâncias EC2, também foi possível compreender conceitos de segurança, armazenamento, gerenciamento de custos e boas práticas dentro do ambiente cloud.

---

# 🔗 Autor

Felipe Espinosa
