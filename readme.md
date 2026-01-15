# 🤖 AYLA Bot

<div align="center">

![Python Version](https://img.shields.io/badge/python-3.8+-blue.svg)
![Discord.py](https://img.shields.io/badge/discord.py-2.0+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-active-success.svg)

**Bot multifuncional para Discord com economia, tickets, eventos e muito mais!**

[Features](#-features) • [Instalação](#-instalação) • [Comandos](#-comandos) • [Configuração](#%EF%B8%8F-configuração)

</div>

---

## 📋 Sobre

AYLA é um bot Discord completo e modular, desenvolvido em Python com discord.py. Oferece uma experiência rica com sistema de economia, tickets de suporte, celebrações de aniversários, eventos sazonais e ferramentas de moderação.

### 🌟 Diferenciais

- 🎨 **Interface Rica** - Embeds coloridos e interativos
- 🔧 **Altamente Configurável** - Sistema de configuração por servidor
- 📦 **Modular** - Ative/desative funcionalidades individualmente
- 🎉 **Eventos Sazonais** - Conteúdo especial durante o ano todo
- 💾 **Persistência de Dados** - Sistema de banco de dados JSON
- 🔒 **Sistema de Permissões** - Controle de acesso por cargo
- 📊 **Sistema de Logs** - Registro automático de ações importantes

---

## ✨ Features

### 🎮 Comandos Básicos
- ✅ Ping e status do bot
- 👋 Saudações personalizadas por horário
- 🎲 Sistema de dados
- 🖼️ Visualização de avatares
- 📊 Informações de servidor e usuários

### 💰 Sistema de Economia
- 💵 Moedas virtuais com sistema de ganhos
- 🎁 Recompensa diária (daily)
- 💼 Sistema de trabalho
- 🛍️ Loja virtual com itens
  - 👑 Cargos temporários VIP
  - ⚡ Power-ups (XP Boost, Coin Boost)
  - 🎁 Caixas misteriosas
  - 🛡️ Proteção anti-roubo
- 📦 Sistema de inventário
- 💸 Transferências entre usuários
- 🏆 Ranking dos mais ricos

### 🎂 Sistema de Aniversários
- 📅 Cadastro de aniversários
- 🎉 Anúncios automáticos
- 👑 Cargo especial de aniversariante
- 📋 Lista de próximos aniversários
- ⏰ Verificação automática diária

### 🎫 Sistema de Tickets
- 🎯 Criação por reação
- 📝 Canais privados automáticos
- 👮 Sistema de claim (assumir atendimento)
- ➕ Adicionar/remover usuários
- 📜 Transcrição de conversas
- 📊 Lista de tickets ativos
- 🔒 Fechamento com confirmação

### 🎉 Eventos Especiais
- 🎄 **Natal** (Dezembro) - Daily 2x, Work 1.5x
- 🎆 **Ano Novo** (Janeiro) - Daily 3x, Mystery Box 2x
- 🎂 **Aniversário da AYLA** (26 de Janeiro) - 10k moedas grátis, Daily 5x
- 💕 **Dia dos Namorados** (14 de Fevereiro) - Bônus em transferências
- 🐰 **Páscoa** (Março/Abril) - Caça aos ovos
- 🎃 **Halloween** (Outubro) - Mystery Box 1.5x
- 🛍️ **Black Friday** (Novembro) - 25% desconto na loja

### 🛡️ Moderação
- 🧹 Limpeza de mensagens em massa
- 👢 Kick (expulsar membros)
- 🔨 Ban/Unban
- 🔇 Timeout (silenciar temporariamente)
- 📋 Sistema de logs automático

### ⚙️ Configuração por Servidor
- 🔀 Prefixo personalizável
- 🎚️ Toggle de funcionalidades
- 📺 Configuração de canais específicos
- 💾 Export/Import de configurações
- 🔄 Reset de configurações

### 🎭 Extras
- 🔄 Status rotativos automáticos
- 💬 Mensagens de boas-vindas
- 📊 Sistema de logs completo
- 🎨 Embeds personalizados

---

## 🚀 Instalação

### Pré-requisitos

- Python 3.8 ou superior
- pip (gerenciador de pacotes Python)
- Uma conta Discord Developer

### Passo a Passo

1. **Clone o repositório**
```bash
git clone https://github.com/seu-usuario/Ayla-BOT.git
cd Ayla-BOT
```

2. **Instale as dependências**
```bash
pip install -r requirements.txt
```

3. **Configure o bot**

Crie um arquivo `.env` na raiz do projeto:
```env
DISCORD_TOKEN=seu_token_aqui
```

Para obter seu token:
- Acesse [Discord Developer Portal](https://discord.com/developers/applications)
- Crie uma nova aplicação
- Vá em "Bot" e clique em "Add Bot"
- Copie o token

4. **Configure as permissões**

O bot precisa das seguintes permissões:
- ✅ Gerenciar Canais
- ✅ Gerenciar Cargos
- ✅ Expulsar Membros
- ✅ Banir Membros
- ✅ Gerenciar Mensagens
- ✅ Ler Mensagens/Ver Canais
- ✅ Enviar Mensagens
- ✅ Gerenciar Mensagens
- ✅ Incorporar Links
- ✅ Anexar Arquivos
- ✅ Adicionar Reações
- ✅ Usar Emojis Externos
- ✅ Moderar Membros

5. **Execute o bot**
```bash
python main.py
```

---

## 📚 Comandos

### Sistema de Ajuda Interativo

```
!ajuda                    - Menu principal
!ajuda basico             - Comandos básicos
!ajuda moderacao          - Comandos de moderação
!ajuda economia           - Sistema de economia
!ajuda tickets            - Sistema de tickets
!ajuda aniversarios       - Sistema de aniversários
!ajuda eventos            - Eventos especiais
!ajuda config             - Configurações (Admin)
```

### Comandos Rápidos

#### 🎮 Básicos
```
!ping                     - Verifica latência
!oi                       - Saudação da AYLA
!dado [lados]             - Rola um dado
!avatar [@usuario]        - Mostra avatar
!serverinfo               - Info do servidor
!userinfo [@usuario]      - Info do usuário
```

#### 💰 Economia
```
!saldo [@usuario]         - Ver saldo
!daily                    - Recompensa diária
!trabalhar                - Ganhar moedas
!loja [categoria]         - Ver loja
!comprar [item]           - Comprar item
!inventario               - Ver inventário
!transferir @user [qtd]   - Transferir moedas
!rank                     - Top 10 mais ricos
```

#### 🛡️ Moderação
```
!limpar [quantidade]      - Limpa mensagens
!kick @usuario [motivo]   - Expulsar membro
!ban @usuario [motivo]    - Banir membro
!unban [id]               - Remover ban
!timeout @user [min] [m]  - Silenciar membro
!untimeout @usuario       - Remover timeout
```

#### 🎂 Aniversários
```
!aniversario DD/MM/AAAA   - Cadastrar aniversário
!meuniver                 - Ver seu aniversário
!aniversarios             - Lista próximos
!removeraniver            - Remover cadastro
!criarcargo               - Criar cargo (Admin)
```

#### 🎫 Tickets
```
Reaja com ⚙️              - Abrir ticket
!fechar                   - Fechar ticket
!claim                    - Assumir (Staff)
!add @usuario             - Adicionar ao ticket
!remove @usuario          - Remover do ticket
!tickets                  - Ver ativos (Staff)
```

#### 🎉 Eventos
```
!evento                   - Ver evento atual
!cacarovos                - Caça aos ovos (Páscoa)
!coletarbonus             - Coletar bônus especial
```

#### ⚙️ Configuração
```
!config                   - Ver configurações
!config toggle [feature]  - Ativar/desativar
!config prefix [novo]     - Mudar prefixo
!config channel [tipo] #  - Definir canal
!config reset             - Resetar tudo
```

---

## ⚙️ Configuração

### Funcionalidades Configuráveis

Ative ou desative recursos por servidor:

```
!config toggle economy      - Sistema de economia
!config toggle birthdays    - Sistema de aniversários
!config toggle tickets      - Sistema de tickets
!config toggle moderation   - Comandos de moderação
!config toggle logs         - Sistema de logs
!config toggle welcome      - Mensagens de boas-vindas
!config toggle status       - Status rotativos
```

### Canais Especiais

Configure canais para funcionalidades específicas:

```
!config channel logs #logs-canal          - Canal de logs
!config channel welcome #bem-vindo        - Canal de boas-vindas
!config channel tickets_category          - Categoria de tickets
```

### Prefixo Personalizado

```
!config prefix ?          - Muda o prefixo para '?'
!config prefix ayla       - Muda o prefixo para 'ayla'
```

---

## 📁 Estrutura do Projeto

```
Ayla-BOT/
│
├── main.py                    # Arquivo principal
├── requirements.txt           # Dependências
├── .env                       # Variáveis de ambiente (não commitado)
├── README.md                  # Documentação
│
├── commands/                  # Módulos de comandos (Cogs)
│   ├── __init__.py
│   ├── basic.py              # Comandos básicos
│   ├── moderation.py         # Moderação
│   ├── economy.py            # Sistema de economia
│   ├── birthday.py           # Sistema de aniversários
│   ├── tickets.py            # Sistema de tickets
│   ├── events.py             # Eventos especiais
│   ├── status.py             # Status rotativos
│   └── config.py             # Configurações
│
└── database/                  # Dados persistentes (JSON)
    ├── economy.json          # Dados de economia
    ├── birthdays.json        # Aniversários cadastrados
    ├── tickets.json          # Tickets ativos/fechados
    ├── events.json           # Dados de eventos
    └── guild_configs.json    # Configurações por servidor
```

---

## 🔧 Tecnologias

- **[Python 3.8+](https://www.python.org/)** - Linguagem principal
- **[discord.py 2.0+](https://discordpy.readthedocs.io/)** - Biblioteca Discord
- **[python-dotenv](https://pypi.org/project/python-dotenv/)** - Gerenciamento de variáveis de ambiente
- **JSON** - Armazenamento de dados

---

## 📝 Requisitos (requirements.txt)

```txt
discord.py==2.3.2
python-dotenv==1.0.0
```

---

## 🎨 Recursos Visuais

### Embeds Personalizados
- 🟢 Verde para sucesso
- 🔴 Vermelho para erros
- 🟡 Laranja para avisos
- 🔵 Azul para informações
- 🟣 Roxo para a AYLA

### Emojis Contextuais
- Saudações diferentes por período do dia
- Status visuais em comandos
- Feedback visual em ações

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. 🍴 Fork o projeto
2. 🔨 Criar uma branch para sua feature (`git checkout -b feature/NovaFeature`)
3. 💾 Commit suas mudanças (`git commit -m 'Adiciona NovaFeature'`)
4. 📤 Push para a branch (`git push origin feature/NovaFeature`)
5. 🔃 Abrir um Pull Request

---

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👨‍💻 Autor

**ChriisIKTZ**
- GitHub: [@ChriisIKTZ](https://github.com/ChriisIKTZ)

---

## 🎉 Agradecimentos

- Comunidade Discord.py
- Todos os contribuidores
- Usuários que testaram e deram feedback

---

## 📞 Suporte

Encontrou um bug? Tem uma sugestão? 

- 🐛 [Abra uma Issue](https://github.com/ChriisIKTZ/Ayla-BOT/issues)
- 💬 Entre em contato via Discord
- ⭐ Deixe uma estrela se gostou!

---

<div align="center">

**Feito com ❤️ e Python**

[⬆ Voltar ao topo](#-ayla-bot)

</div>
