<p align="center">
  <img src="https://img.shields.io/badge/Python-3.9+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Flask-3.0+-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask">
  <img src="https://img.shields.io/badge/Docker-ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey?style=for-the-badge" alt="Platform">
</p>

<h1 align="center">AI Consult — AI Strategy Factory</h1>

<p align="center">
  <strong>Gere um pacote completo de estratégia de IA para qualquer empresa em minutos, não semanas.</strong>
</p>

<p align="center">
  <a href="#-quick-start">Quick Start</a> •
  <a href="#-features">Features</a> •
  <a href="#-como-funciona">Como Funciona</a> •
  <a href="#-entregáveis">Entregáveis</a> •
  <a href="#-instalação">Instalação</a> •
  <a href="#-uso">Uso</a> •
  <a href="#-curso-inemaclub">Curso INEMA.CLUB</a>
</p>

---

## O Que É Isso?

Digite o nome de uma empresa → receba um pacote completo de estratégia de IA:

| Saída | Descrição |
|-------|-----------|
| **15 Documentos Estratégicos** | Inventário tech, pontos de dor, roadmaps, análise de ROI |
| **Diagramas de Arquitetura** | Visualizações Mermaid geradas automaticamente |
| **Apresentações Executivas** | Decks PowerPoint prontos para stakeholders |
| **Relatórios de Implementação** | Documentos Word detalhados com recomendações |

**Custo por análise: ~$0,05–0,50** usando APIs Perplexity + Gemini

**Todos os documentos em Português Brasileiro.**

---

## Iniciante? Comece Aqui

<details>
<summary><strong>Clique aqui se é sua primeira vez ou está intimidado</strong></summary>

### Não entre em pânico! Veja o que isso faz

Esta ferramenta é como ter uma consultoria numa caixa. Você digita o nome de uma empresa (ex: "Natura" ou "sua padaria local"), e ela automaticamente:

1. **Pesquisa** a empresa usando IA (como ter um assistente de pesquisa)
2. **Escreve** 15 documentos estratégicos profissionais (como ter um consultor)
3. **Cria** apresentações PowerPoint e documentos Word (como ter um analista)

**É isso.** Você não precisa entender o código. Só precisa executá-lo.

### O Que Você Precisa

| O Quê | Por Quê | Tempo para Obter |
|-------|---------|-----------------|
| Um computador | Windows, Mac ou Linux funcionam | Você provavelmente já tem |
| Python instalado | A linguagem de programação usada | 5 minutos |
| Duas chaves de API gratuitas | Para usar Perplexity e Gemini AI | 10 minutos |
| Claude Code (opcional) | Facilita tudo 10x | 2 minutos |

### A Forma Mais Fácil (Usando Claude Code)

Se você tem [Claude Code](https://claude.ai/code) instalado, basta dizer:

```
Clone o repositório em https://github.com/MonicaMSal/AI-CONSULT e me ajude a configurar e executar
```

O Claude Code vai:
- Baixar todos os arquivos
- Instalar tudo necessário
- Ajudar a obter as chaves de API
- Executar o app para você

### Passo a Passo para Iniciantes Completos (Sem Claude Code)

#### Passo 1: Instalar Python (5 minutos)

**No Mac:**
1. Abra o Terminal (pesquise "Terminal" no Spotlight)
2. Digite: `python3 --version`
3. Se aparecer um número de versão, pronto!
4. Caso contrário, acesse [python.org/downloads](https://python.org/downloads)

**No Windows:**
1. Acesse [python.org/downloads](https://python.org/downloads)
2. Baixe e execute o instalador
3. **IMPORTANTE:** Marque a opção "Add Python to PATH"
4. Clique em Install

#### Passo 2: Obter Suas Chaves de API (10 minutos)

**Chave Perplexity:**
1. Acesse [perplexity.ai](https://perplexity.ai)
2. Crie uma conta (gratuito)
3. Vá em Settings → API
4. Clique em "Generate API Key"
5. Copie em lugar seguro (parece com `pplx-abc123...`)

**Chave Gemini:**
1. Acesse [aistudio.google.com/apikey](https://aistudio.google.com/apikey)
2. Entre com o Google
3. Clique em "Create API Key"
4. Copie em lugar seguro (parece com `AIzaSy...`)

#### Passo 3: Baixar Este Projeto (2 minutos)

**Opção A — Baixar ZIP (mais fácil):**
1. Clique no botão verde "Code" no topo desta página
2. Clique em "Download ZIP"
3. Descompacte em algum lugar acessível (ex: Desktop)

**Opção B — Usar Git:**
```bash
git clone https://github.com/MonicaMSal/AI-CONSULT.git
```

#### Passo 4: Configurar o Projeto (3 minutos)

1. Abra Terminal (Mac) ou Prompt de Comando (Windows)

2. Navegue até a pasta:
   ```bash
   cd Desktop/AI-CONSULT   # ou onde você colocou
   ```

3. Execute o setup:
   ```bash
   python setup.py    # Windows
   python3 setup.py   # Mac
   ```

4. Adicione suas chaves de API:
   - Abra o arquivo `.env` em qualquer editor de texto
   - Substitua o texto placeholder pelas suas chaves reais
   - Salve o arquivo

#### Passo 5: Execute! (1 minuto)

```bash
python -m strategy_factory.webapp    # Windows
python3 -m strategy_factory.webapp   # Mac
```

Seu navegador abrirá em **http://localhost:8888**

Digite qualquer nome de empresa e clique em "Start Analysis"!

### O Que Fazer se Algo Der Errado?

**"Python not found"**
- Certifique-se de que o Python está instalado
- No Windows, verifique se marcou "Add Python to PATH"
- Tente reiniciar o terminal

**"API key error"**
- Verifique se o arquivo `.env` tem as chaves corretas
- Certifique-se de que não há espaços extras
- Verifique se as chaves estão em linhas separadas

**"Module not found"**
- Execute `pip install -r requirements.txt` novamente
- Certifique-se de estar na pasta correta

**Ainda travado?**
- Abra uma issue no GitHub
- Ou pergunte ao Claude Code: "Estou recebendo este erro: [cole o erro]. Me ajude a corrigir."

</details>

---

## Quick Start

### Opção 1: Docker (Recomendado para VPS)

```bash
# Clone o repositório
git clone https://github.com/MonicaMSal/AI-CONSULT.git
cd AI-CONSULT

# Crie o arquivo .env com suas chaves de API
cp .env.example .env
# Edite .env com suas chaves reais

# Suba com Docker Compose
docker-compose up -d

# Acompanhe os logs
docker-compose logs -f
```

Acesse **http://ip-do-servidor:8888** ou **http://localhost:8888**

```bash
# Parar a aplicação
docker-compose down

# Rebuildar após mudanças
docker-compose up -d --build
```

### Opção 2: Claude Code (Mais Fácil)

Se você tem [Claude Code](https://claude.ai/code):

```
Só diga: "Clone e execute o AI Consult para mim"
```

### Opção 3: Setup Manual

```bash
# Clone o repositório
git clone https://github.com/MonicaMSal/AI-CONSULT.git
cd AI-CONSULT

# Execute o script de setup (funciona no Windows, macOS, Linux)
python setup.py

# Adicione suas chaves de API ao arquivo .env
# Depois execute o web app
python -m strategy_factory.webapp
```

Acesse **http://localhost:8888** e insira o nome de uma empresa!

---

## Features

### Motor de Pesquisa
- **Perplexity AI** para inteligência em tempo real sobre empresas
- 9–18 queries por análise
- Agregação automática de fontes

### Síntese de Documentos
- **Google Gemini 2.5 Flash** para geração de documentos
- 15 templates de entregáveis especializados
- Output consistente com qualidade de consultoria
- Todos os documentos em **Português Brasileiro**

### Opções de Export
- Documentos Markdown
- Apresentações PowerPoint (PPTX)
- Relatórios Word (DOCX)
- Diagramas de arquitetura (PNG + .mmd editável)

### Experiência do Usuário
- Interface web moderna
- Acompanhamento de progresso em tempo real
- **Continuar análises interrompidas** com seleção de empresa
- **Cancelar análises** em andamento
- Diretórios com timestamp para múltiplas versões da mesma empresa
- Páginas de resultados públicas (sem necessidade de login para compartilhar)
- Suporte multiplataforma

---

## Como Funciona

```
┌─────────────────────────────────────────────────────────────────────┐
│                         ENTRADA DO USUÁRIO                           │
│                    "Analisar Stripe"                                 │
└─────────────────────────────────────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    FASE 1: PESQUISA                                  │
│                                                                      │
│   Queries Perplexity AI:                                            │
│   • Visão geral e modelo de negócios                                │
│   • Stack tecnológico e infraestrutura                              │
│   • Cenário da indústria e concorrentes                             │
│   • Iniciativas atuais de IA/ML                                     │
│   • Pontos de dor e desafios                                        │
│   • Prioridades estratégicas                                        │
│                                                                      │
│   Saída: JSON de pesquisa abrangente                                │
└─────────────────────────────────────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    FASE 2: SÍNTESE                                   │
│                                                                      │
│   Google Gemini gera:                                               │
│   • 15 entregáveis em markdown                                      │
│   • Código para diagramas Mermaid                                   │
│   • Recomendações estruturadas                                      │
│                                                                      │
│   Saída: Documentos de estratégia                                   │
└─────────────────────────────────────────────────────────────────────┘
                                │
                                ▼
┌─────────────────────────────────────────────────────────────────────┐
│                    FASE 3: GERAÇÃO                                   │
│                                                                      │
│   Outputs finais:                                                   │
│   • 2 apresentações PowerPoint                                      │
│   • 2 documentos Word                                               │
│   • 5+ diagramas de arquitetura (PNG + .mmd)                       │
│                                                                      │
│   Saída: Entregáveis prontos para executivos                        │
└─────────────────────────────────────────────────────────────────────┘
```

---

## Entregáveis

### Avaliação Estratégica
| # | Documento | Descrição |
|:-:|-----------|-----------|
| 1 | **Inventário Tecnológico** | Avaliação do stack atual |
| 2 | **Pontos de Dor** | Análise por departamento |
| 3 | **Avaliação de Maturidade** | Score de prontidão para IA (1–5) |
| 4 | **Diagramas Mermaid** | Arquitetura atual e futura |

### Planejamento de Implementação
| # | Documento | Descrição |
|:-:|-----------|-----------|
| 5 | **Roadmap** | Plano 30/60/90/180/360 dias |
| 6 | **Quick Wins** | Oportunidades de alto impacto, baixo esforço |
| 7 | **Comparação de Fornecedores** | Framework build vs buy |
| 8 | **Consolidação de Licenças** | Recomendações de otimização de software |
| 9 | **Calculadora de ROI** | Análise custo-benefício com projeções |

### Governança e Política
| # | Documento | Descrição |
|:-:|-----------|-----------|
| 10 | **Política de IA** | Template de política de uso aceitável |
| 11 | **Governança de Dados** | Framework de gestão de dados |
| 12 | **Gestão de Mudanças** | Playbook de treinamento e adoção |

### Recursos
| # | Documento | Descrição |
|:-:|-----------|-----------|
| 13 | **Biblioteca de Prompts** | Prompts iniciais por departamento |
| 14 | **Biblioteca de Casos de Uso** | Aplicações de IA por departamento |
| 15 | **Glossário** | Termos de IA explicados para stakeholders |

### Outputs Executivos
| Tipo | Arquivo | Descrição |
|------|---------|-----------|
| PPTX | Executive Summary | Apresentação pronta para board |
| PPTX | Full Findings | Deck de análise detalhada |
| DOCX | Strategy Report | Relatório escrito completo |
| DOCX | Statement of Work | Proposta de implementação |

---

## Instalação

### Pré-requisitos

| Requisito | Como Obter |
|-----------|------------|
| Python 3.9+ | [python.org](https://www.python.org/downloads/) |
| Docker (para VPS) | [docker.com/get-docker](https://docs.docker.com/get-docker/) |
| Chave Perplexity API | [perplexity.ai/settings/api](https://www.perplexity.ai/settings/api) |
| Chave Gemini API | [aistudio.google.com/apikey](https://aistudio.google.com/apikey) |

### Instalação Docker (VPS/Produção)

```bash
# 1. Instale Docker e Docker Compose na sua VPS
# Ubuntu/Debian:
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh get-docker.sh
sudo apt install docker-compose-plugin

# 2. Clone o repositório
git clone https://github.com/MonicaMSal/AI-CONSULT.git
cd AI-CONSULT

# 3. Configure o ambiente
cp .env.example .env
nano .env  # Adicione suas chaves de API

# 4. Suba com Docker Compose
docker-compose up -d

# 5. Acompanhe os logs
docker-compose logs -f ai-consult
```

### Instalação Manual

```bash
# 1. Clone o repositório
git clone https://github.com/MonicaMSal/AI-CONSULT.git
cd AI-CONSULT

# 2. Crie ambiente virtual
python3 -m venv venv

# 3. Ative-o
source venv/bin/activate        # macOS/Linux
# OU
.\venv\Scripts\activate         # Windows

# 4. Instale dependências
pip install -r requirements.txt

# 5. Configure o ambiente
cp .env.example .env
```

### Configure as Chaves de API

Edite `.env` com suas chaves:

```env
PERPLEXITY_API_KEY=pplx-xxxxxxxxxxxxxxxxxxxx
GEMINI_API_KEY=AIzaSyxxxxxxxxxxxxxxxxxxxxxxxxx
```

### Referência de Comandos Docker

```bash
# Iniciar aplicação
docker-compose up -d

# Parar aplicação
docker-compose down

# Ver logs
docker-compose logs -f

# Rebuildar após mudanças
docker-compose up -d --build

# Acessar shell do container
docker-compose exec ai-consult bash

# Remover containers e volumes
docker-compose down -v
```

---

## Uso

### Interface Web (Recomendado)

```bash
python -m strategy_factory.webapp
```

Acesse **http://localhost:8888**

### Linha de Comando

```bash
# Análise rápida (~$0,05, 2–3 minutos)
python -m strategy_factory.main run "Stripe"

# Com contexto adicional
python -m strategy_factory.main run "Stripe" --context "B2B payments, fintech"

# Análise completa (~$0,50, 5–10 minutos)
python -m strategy_factory.main run "Stripe" --mode comprehensive

# Verificar status
python -m strategy_factory.main status "Stripe"

# Continuar análise interrompida
python -m strategy_factory.main resume "Stripe"

# Listar todas as análises
python -m strategy_factory.main list
```

---

## Estrutura do Projeto

```
AI-CONSULT/
├── strategy_factory/           # Pacote principal
│   ├── webapp.py              # Aplicação web Flask
│   ├── server.py              # Servidor alternativo
│   ├── main.py                # Ponto de entrada CLI
│   ├── config.py              # Configuração
│   ├── models.py              # Modelos de dados
│   ├── progress_tracker.py    # Gerenciamento de estado (com suporte a timestamp)
│   ├── knowledge_loader.py    # Carregamento de base de conhecimento
│   ├── temporal.py            # Utilitários de data/tempo
│   │
│   ├── research/              # Fase 1: Pesquisa
│   │   ├── orchestrator.py
│   │   ├── perplexity_client.py
│   │   └── query_templates.py
│   │
│   ├── synthesis/             # Fase 2: Síntese
│   │   ├── orchestrator.py
│   │   ├── gemini_client.py
│   │   └── prompts/           # 15 prompts de entregáveis
│   │
│   └── generation/            # Fase 3: Geração
│       ├── orchestrator.py
│       ├── pptx_generator.py
│       ├── docx_generator.py
│       └── mermaid_renderer.py
│
├── docs/                      # Site do curso (GitHub Pages)
│   ├── index.html             # Landing page INEMA.CLUB
│   └── curso/                 # Trilhas do curso
│       ├── trilha1/
│       ├── trilha2/
│       └── trilha3/
│
├── output/                    # Entregáveis gerados
├── Dockerfile
├── docker-compose.yml
├── requirements.txt
├── setup.py
├── DEPLOY.md                  # Guia completo de deploy em VPS
├── DELIVERABLES.md            # Descrição detalhada dos 19 entregáveis
└── README.md
```

---

## Estrutura de Output

```
output/
└── nome-da-empresa_20240615_143022/   # Diretório com timestamp
    ├── markdown/              # 15 arquivos .md
    ├── presentations/         # 2 arquivos .pptx
    ├── documents/             # 2 arquivos .docx
    ├── mermaid_images/        # PNGs + arquivos .mmd editáveis
    ├── research_cache.json    # Dados brutos da pesquisa
    └── state.json             # Rastreamento de progresso
```

---

## Custos de API

| API | Modelo | Custo | Uso |
|-----|--------|-------|-----|
| Perplexity | sonar | $0,001/1K tokens | Pesquisa rápida |
| Perplexity | sonar-pro | $0,003/1K tokens | Pesquisa aprofundada |
| Gemini | 2.5-flash | $0,075/1M input | Síntese de documentos |

**Custos típicos:**
- Modo rápido: **$0,02–0,05** por empresa
- Modo completo: **$0,30–0,80** por empresa

---

## Curso INEMA.CLUB

Este repositório inclui um site de curso completo em **docs/**, servido via GitHub Pages.

O curso cobre o uso do AI Strategy Factory em formato didático PT-BR, com:
- **3 trilhas** de aprendizado
- Landing page com apresentação do método
- Módulos práticos com exemplos reais

---

## Troubleshooting

<details>
<summary><strong>Porta já em uso</strong></summary>

O app encontra automaticamente uma porta disponível. Ou especifique uma:

```bash
python -m strategy_factory.webapp --port 9000
```

</details>

<details>
<summary><strong>Erros de chave de API</strong></summary>

1. Certifique-se de que o arquivo `.env` existe na raiz do projeto
2. Verifique se as chaves estão corretas (sem espaços extras)
3. Verifique se as contas de API têm créditos

</details>

<details>
<summary><strong>Module not found</strong></summary>

```bash
# Certifique-se de estar no ambiente virtual
source venv/bin/activate  # macOS/Linux
.\venv\Scripts\activate   # Windows

# Reinstale as dependências
pip install -r requirements.txt
```

</details>

<details>
<summary><strong>Problemas específicos do Windows</strong></summary>

- Use PowerShell ou Prompt de Comando (não Git Bash)
- Pode ser necessário executar como Administrador
- Use `python` em vez de `python3`

</details>

<details>
<summary><strong>Problemas específicos do macOS</strong></summary>

- A porta 5000 é usada pelo AirPlay Receiver (usamos 8888 por padrão)
- Instale as ferramentas Xcode: `xcode-select --install`

</details>

---

## Contribuindo

Contribuições são bem-vindas! Veja [CONTRIBUTING.md](CONTRIBUTING.md) para diretrizes.

### Áreas para Contribuição

- [ ] Provedores de LLM adicionais (OpenAI, Anthropic)
- [ ] Exportação em PDF
- [ ] Templates específicos por indústria
- [ ] Cache para queries repetidas
- [ ] Processamento em lote de múltiplas empresas

---

## Licença

MIT License — veja [LICENSE](LICENSE) para detalhes.

---

## Agradecimentos

- [Perplexity AI](https://www.perplexity.ai/) — Capacidades de pesquisa
- [Google Gemini](https://ai.google.dev/) — Síntese de documentos
- [python-pptx](https://python-pptx.readthedocs.io/) — Geração de PowerPoint
- [python-docx](https://python-docx.readthedocs.io/) — Geração de documentos Word

---

<p align="center">
  <strong>Construído com Claude Code</strong><br>
  <sub>O assistente de desenvolvimento com IA</sub>
</p>
