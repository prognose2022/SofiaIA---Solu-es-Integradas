# SofiaIA --- Soluções Integradas

Chatbot IA via WhatsApp com integração ao Google Calendar e Google Docs. Envie mensagens personalizadas a partir de planilhas no Drive!

## Demonstração Gratuita

Você pode testar o sistema gratuitamente por **1 semana**.

- Chatbot IA comercial
- Integração com Google Calendar e Docs
- Mensagens automáticas via WhatsApp
- Personalização a partir de planilhas Google Drive

## Como Usar a Demo

1. Solicite acesso gratuito por 7 dias.
2. Entre em contato via WhatsApp:
   - **Comercial:** [Clique para conversar](https://wa.me/554892017347)
   - **Pessoal:** [Clique para conversar](https://wa.me/5548998205960)
3. Receba instruções e credenciais para uso.

## Requisitos do Sistema
- Node.js 18+
- Conta Google para integração com Calendar/Docs
- WhatsApp ativo

## Instalação
```bash
# Clone o repositório
https://github.com/prognose2022/SofiaIA---Solu-es-Integradas.git

# Instale as dependências
npm install
```

## Configuração de Ambiente
Crie um arquivo `.env` com suas chaves:
```
API_KEY=coloque_sua_api_key_aqui
WHATSAPP_TOKEN=coloque_seu_token_aqui
GOOGLE_CALENDAR_SECRET=coloque_seu_secret_aqui
SOFIA_SISTEMA=SoftwareSofia SDK
SOFIA_VERSAO=Python3 -y
SOFIA_STATUS=Desenvolvimento ativo
SOFIA_PRECO_NACIONAL=Não definido
SOFIA_PRECO_INTERNACIONAL=Não definido
SOFIA_CONTATO_PESSOAL=oculto
SOFIA_CONTATO_COMERCIAL=oculto
```

## Como Rodar Localmente
```bash
npm start
```
Acesse: [http://localhost:5000](http://localhost:5000)

## Exemplo de Requisição
Acesse a rota `/` para obter informações do sistema em JSON:
```json
{
  "sistema": "SoftwareSofia SDK",
  "versao": "Python3 -y",
  "status": "Desenvolvimento ativo",
  "preco_nacional": "Não definido",
  "preco_internacional": "Não definido",
  "contato_pessoal": "oculto",
  "contato_comercial": "oculto"
}
```

## Informações para Desenvolvedores
- O projeto utiliza Express.js
- Variáveis sensíveis estão no `.env` (não versionar)
- Scripts automatizados para commit/push: `./sync.sh`
- Integração fácil com APIs Google e WhatsApp

## Observações
- Sistema em evolução (SDK Python3)
- Sem precificação definida para SDK
- Após o período de teste, negocie condições comerciais diretamente pelo WhatsApp

---

**SofiaIA --- Soluções Integradas**
Desenvolvimento ativo | Todos os direitos reservados
