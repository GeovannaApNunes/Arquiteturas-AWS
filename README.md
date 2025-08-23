# 🏗️ Arquiteturas AWS

[![Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)](https://github.com/GeovannaApNunes/Arquiteturas-AWS)
[![Licença](https://img.shields.io/badge/licença-MIT-green)](LICENSE)

Bem-vindo ao repositório Arquiteturas AWS! Aqui você encontrará exemplos de arquiteturas na nuvem criadas para estudo e aprendizado prático de computação em nuvem.

```
📂 Estrutura do Repositório
text
├─ arquiteturas/                                   # Diagramas e representações visuais das arquiteturas
│  ├─ 001-VPC numa Região.png                       # Arquitetura 1: VPC numa Região
│  ├─ 002-SubRedes em Zonas de Disponibilidade.png  # Arquitetura 2: Sub-redes em Zonas de Disponibilidade
│  ├─ 003-EC2 numa SubRede Publica.png             # Arquitetura 3: EC2 numa Sub-rede Pública
│  ├─ 004-S3 MultiRegiao.png                        # Arquitetura 4: S3 Multi-Região
│  ├─ 005-Conexão EC2 no EBS.png                   # Arquitetura 5: Conexão EC2 no EBS
│  ├─ 006 - Site Estático no S3.png                # Arquitetura 6: Site Estático no S3
│  ├─ 007 - AWS Journey 🚀.jpeg                     # Arquitetura 7: AWS Journey
│  ├─ 008 - AWS Flow 🌐.jpeg                        # Arquitetura 8: AWS Flow
│  ├─ 009 - Serverless Scholar 🧠✨.jpeg           # Arquitetura 9: Serverless Scholar
│  └─ 010 - Protocolos da Internet endereços IP públicos e privados.png  # Arquitetura 10: Protocolos da Internet e Endereços IP
├─ 011 - IAM.png                                   # Arquivo IAM
├─ 012 - Selecionando dados de um banco de dados.png  # Exemplo de banco de dados
├─ 013 - Instalar e configurar a CLI da AWS.png   # Exemplo de configuração CLI
└─ README.md                                      # Este arquivo

O objetivo deste repositório é fornecer exemplos práticos de arquiteturas na nuvem, auxiliando no entendimento e aplicação de conceitos de computação em nuvem.
```
📌 Como Usar
Clone este repositório em sua máquina local:
```
bash
git clone https://github.com/GeovannaApNunes/Arquiteturas-AWS.git
Acesse a pasta do projeto:

bash
cd Arquiteturas-AWS
Navegue até a arquitetura de interesse:

bash
cd arquiteturas/nome-da-arquitetura
Abra os diagramas na ferramenta de sua preferência para visualização e estudo.
```

# 🏛️ Arquiteturas Disponíveis

## 1. VPC numa Região
- **Objetivo:** Criar uma Virtual Private Cloud (VPC) em uma única região da AWS.  
- **Componentes:** VPC, Internet Gateway, Tabelas de Roteamento.  
- **Fluxo:** Rede privada isolada para hospedar recursos AWS de forma segura.

## 2. Sub-redes em Zonas de Disponibilidade
- **Objetivo:** Distribuir sub-redes em múltiplas Availability Zones (AZs) para alta disponibilidade.  
- **Componentes:** VPC, Sub-redes públicas e privadas, AZs.  
- **Fluxo:** Garantia de resiliência e tolerância a falhas.

## 3. EC2 numa Sub-rede Pública
- **Objetivo:** Utilizar uma instância EC2 acessível via Internet em uma sub-rede pública.  
- **Componentes:** EC2, Elastic IP, Internet Gateway.  
- **Fluxo:** Acesso direto à instância para rodar aplicações.

## 4. S3 Multi-Região
- **Objetivo:** Configurar buckets S3 para armazenamento e replicação entre regiões.  
- **Componentes:** Buckets S3, Replicação entre regiões.  
- **Fluxo:** Garantia de alta disponibilidade e resiliência dos dados.

## 5. Conexão EC2 no EBS
- **Objetivo:** Demonstrar uso de volumes EBS para armazenamento persistente em uma EC2.  
- **Componentes:** EC2, Volumes EBS.  
- **Fluxo:** Dados mantidos mesmo após reinicializações da instância.

## 6. Site Estático no S3
- **Objetivo:** Hospedar um site estático diretamente no Amazon S3.  
- **Componentes:** Bucket S3, Configuração de hospedagem, CloudFront (opcional).  
- **Fluxo:** Entrega direta via S3 ou distribuição global com CloudFront.

## 7. AWS Journey
- **Objetivo:** Ilustrar a jornada de adoção da AWS, de iniciantes a arquiteturas mais complexas.  
- **Componentes:** Serviços variados.  
- **Fluxo:** Caminho progressivo de aprendizado e implementação.

## 8. AWS Flow
- **Objetivo:** Representar o fluxo de dados e interações entre serviços AWS.  
- **Componentes:** Serviços de rede, armazenamento e computação.  
- **Fluxo:** Comunicação entre serviços para aplicações completas.

## 9. Serverless Scholar
- **Objetivo:** Destacar o uso de arquitetura serverless para reduzir custos e gerenciamento de infraestrutura.  
- **Componentes:** Lambda, API Gateway, DynamoDB/S3.  
- **Fluxo:** Funções executadas sob demanda sem servidores dedicados.

## 10. Protocolos da Internet e Endereços IP
- **Objetivo:** Explicar protocolos e diferenças entre IPs públicos e privados na AWS.  
- **Componentes:** VPC, Sub-redes, Endereços IP.  
- **Fluxo:** Comunicação de recursos dentro e fora da rede AWS.

---

## 💬 Contribuições
Este repositório é pessoal e possui fins educativos, mas contribuições são bem-vindas!  
Sinta-se à vontade para sugerir melhorias ou compartilhar suas próprias arquiteturas via Pull Request.
