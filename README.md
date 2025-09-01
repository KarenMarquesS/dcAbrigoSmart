# 🚀 Projeto DimDim – Modernização com Docker Compose

## 📌 Contexto
A **DimDim** está passando por um processo de modernização tecnológica.  
Atualmente, os sistemas funcionam em uma arquitetura tradicional e enfrentam desafios como:  

- Aplicações monolíticas em servidores dedicados  
- Deploy manual e demorado  
- Dificuldade de escalabilidade  
- Inconsistências entre ambientes  
- Alta dependência de infraestrutura física  

## 🎯 Objetivo
Migrar para uma arquitetura moderna e eficiente, utilizando **Docker Compose**, garantindo:  

- Orquestração automatizada de serviços  
- Escalabilidade horizontal  
- Ambientes padronizados e reproduzíveis  
- Deploy contínuo e confiável  
- Melhor utilização de recursos  

## 🏗️ Arquitetura
**🔹 Atual:** Monolítica, servidores dedicados  
**🔹 Futura:** Contêineres orquestrados com Docker Compose  

## ⚙️ Tecnologias Utilizadas
- Docker & Docker Compose  
- Java Spring Boot  
- MySQL (banco relacional)  
- Imagens oficiais do Docker Hub  

## 📂 Estrutura do Projeto
```plaintext
.
├── app/                  # Código da aplicação
│   ├── Dockerfile        # Build do container da aplicação
│   └── src/              # Código-fonte do projeto
├── docker-compose.yml    # Orquestração dos containers
├── README.md             # Documentação do projeto
└── .env                  # Variáveis de ambiente

## ▶️ Como Rodar o Projeto

### 🔹 Pré-requisitos
- Docker instalado  
- Docker Compose instalado  

### 🔹 Passos
1. Clone o repositório:

git clone https://github.com/seu-usuario/dimdim-docker.git
cd dimdim-docker

docker-compose up -d --build

docker ps

Acesse a aplicação no navegador:
👉 http://localhost:8080


