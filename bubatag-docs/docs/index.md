# Bubatag 🐃

## Plataforma IoT de Monitoramento para Bubalinos

O Bubatag é uma plataforma inteligente de monitoramento para bubalinocultura de precisão, desenvolvida para auxiliar produtores rurais no acompanhamento fisiológico e geográfico de bubalinos em tempo real utilizando Internet das Coisas (IoT), Computação em Nuvem e Inteligência Artificial.

---

## 📖 Sobre o Projeto

A plataforma foi criada com o objetivo de:

- Monitorar níveis de estresse térmico dos bubalinos
- Realizar rastreamento geográfico em tempo real
- Criar uma cerca virtual inteligente
- Gerar alertas automáticos
- Facilitar o manejo do rebanho
- Melhorar produtividade e bem-estar animal

---

## 🎯 Objetivos

### Objetivo Geral

Desenvolver uma arquitetura IoT integrada à computação em nuvem para monitoramento contínuo do bem-estar animal em fazendas de pequeno e médio porte.

---

### Objetivos Específicos

- Monitoramento de localização com latência máxima de 5 minutos
- Desenvolvimento de coleira inteligente baseada em ESP32
- Captura de frequência cardíaca e temperatura corporal
- Integração com serviços em nuvem
- Implementação de infraestrutura LoRaWAN
- Monitoramento via PRTG
- Processamento de dados utilizando Inteligência Artificial


# Arquitetura do Sistema

## Estrutura Geral

O sistema Bubatag é dividido em:

### 📱 Aplicativo Mobile
Responsável pelo monitoramento rápido e simplificado do rebanho em tempo real.

### 🖥️ Aplicativo Desktop
Painel administrativo completo para gerenciamento da fazenda.

### ☁️ API e Nuvem
Responsável pela centralização, processamento e distribuição dos dados.

### 📡 Infraestrutura IoT
Rede composta por:
- Coleiras inteligentes
- Antenas LoRaWAN
- Gateway central
- Roteadores
- Servidor em nuvem

---

# 📡 Infraestrutura IoT

## Coleira Inteligente

A coleira inteligente é responsável pela captura de dados fisiológicos e geográficos dos animais.

### Componentes utilizados

| Componente | Função |
|---|---|
| ESP32 | Microcontrolador principal |
| XD-58C | Sensor de frequência cardíaca |
| MLX90614 | Sensor infravermelho de temperatura |
| GPS | Localização em tempo real |
| LoRa | Comunicação de longa distância |

---

## Comunicação LoRaWAN

A comunicação entre dispositivos ocorre utilizando tecnologia LoRaWAN, permitindo:

- Baixo consumo energético
- Longo alcance
- Cobertura rural
- Transmissão contínua de dados

---

## Gateway Central

Responsável por:

- Receber dados das antenas
- Encaminhar informações para a nuvem
- Gerenciar comunicação da fazenda

---

# ☁️ API

## Visão Geral

A API atua como intermediária entre:

- Coleiras inteligentes
- Banco de dados
- Inteligência Artificial
- Aplicativos web/mobile
- Sistema PRTG

---

## Fluxo da API

### Etapa A — Recebimento de Dados
Recebimento dos dados enviados pelas coleiras.

### Etapa B — Processamento
Envio das informações para:
- IA
- PRTG
- Banco de dados

### Etapa C — Consolidação
Armazenamento dos dados processados.

### Etapa D — Disponibilização
Distribuição das informações para os usuários finais.

---

# 🧠 Inteligência Artificial

## Objetivo

A IA é responsável por:

- Detectar padrões de estresse
- Gerar relatórios automáticos
- Classificar níveis de risco
- Auxiliar decisões do produtor

---

# 📱 Aplicativo Mobile

## Funcionalidades

### 🗺️ Localização em Tempo Real

- Visualização dos animais no mapa
- Cerca virtual
- Monitoramento de movimentação

---

### ❤️ Monitoramento Fisiológico

Visualização em tempo real de:

- Temperatura corporal
- Frequência cardíaca
- Status do animal
- Histórico individual

---

# 🖥️ Aplicativo Desktop

## Dashboard

O painel desktop possui:

- Gráficos em tempo real
- Histórico de estresse
- Controle de fugas
- Gestão dos animais
- Anotações individuais
- Relatórios analíticos

---

## Métricas Monitoradas

### 🌡️ Temperatura Média
Monitoramento térmico do rebanho.

### ❤️ Batimentos Cardíacos
Análise fisiológica dos animais.

### 🚨 Alertas
Sistema automático de notificações.

### 📍 Geolocalização
Histórico completo de posicionamento.

---

# 🗃️ Banco de Dados

## Estrutura

O sistema utiliza banco de dados relacional para armazenamento de:

- Dados fisiológicos
- Localização GPS
- Histórico dos animais
- Informações das coleiras
- Alertas e eventos

---

# 🔐 Segurança

## Recursos de Segurança

- Autenticação de usuários
- Controle de acesso
- Criptografia de comunicação
- Backup em nuvem

---

# 👨‍💻 Equipe

## Desenvolvedores

- Arthur Fukunaga Fagundes Nepomuceno
- Cristhian Hatzman Trigo
- João Paulo Goreri Rustichelli
- Leonardo de Lima
- Vinícius de Souza Camargo Costa

---

# 📚 Referências

As referências utilizadas no desenvolvimento do projeto estão disponíveis no artigo científico oficial do Bubatag.

---

# 🚀 Status do Projeto

| Status | Situação |
|---|---|
| Desenvolvimento | Em andamento |
| Infraestrutura IoT | Em validação |
| API | Em desenvolvimento |
| Aplicativo Mobile | Protótipo |
| Aplicativo Desktop | Protótipo |