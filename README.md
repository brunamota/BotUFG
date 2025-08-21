# 🏛️ UFG Campus Bot

Bot do WhatsApp para ajudar estudantes da UFG a encontrar localizações e informações sobre o campus.

## 🚀 Funcionalidades

- ✅ **Resposta única**: Cada usuário recebe resposta apenas 1 vez por hora
- ✅ **Não responde grupos**: Funciona apenas em conversas individuais
- ✅ **Ativação automática**: Responde a qualquer mensagem enviada
- ✅ **Informações completas**: Menu com todos os prédios e serviços principais
- ✅ **Sistema de cooldown**: Previne spam com controle de tempo de 1 hora

## 📋 Informações Disponíveis

### 🏢 Prédios Principais
- Reitoria
- ICE (Instituto de Ciências Exatas)
- FACOMB (Comunicação e Biblioteconomia)
- FACE (Ciências Econômicas)
- FL (Faculdade de Letras)
- FCS (Ciências Sociais)
- FH (Faculdade de História)

### 🏥 Serviços
- RU (Restaurante Universitário)
- Biblioteca Central
- Casa do Estudante

## 🛠️ Instalação

1. **Instalar dependências:**
\`\`\`bash
npm install
\`\`\`

2. **Executar o bot:**
\`\`\`bash
npm start
\`\`\`

3. **Escanear QR Code:**
   - O QR Code aparecerá no terminal
   - Escaneie com o WhatsApp para conectar

## ⚙️ Como Funciona

1. **Primeira mensagem**: Usuário envia qualquer mensagem
2. **Resposta completa**: Bot envia menu com todas as informações
3. **Cooldown ativado**: Usuário fica 1 hora sem poder receber nova resposta
4. **Reativação**: Após 1 hora, usuário pode receber nova resposta

## 🔧 Configurações

- **Tempo de cooldown**: 1 hora (configurável em `COOLDOWN_TIME`)
- **Limpeza de cache**: A cada 2 horas remove usuários inativos
- **Logs detalhados**: Registra todas as interações com timestamp

## 📝 Logs

O bot registra:
- Conexões e desconexões
- Mensagens recebidas e enviadas
- Usuários em cooldown
- Limpeza automática do cache
- Erros e falhas de autenticação

## 🚫 Limitações

- Não responde em grupos do WhatsApp
- Limite de 1 resposta por hora por usuário
- Requer conexão ativa com WhatsApp Web
