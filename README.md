# 📱 Prosefa Mobile – Validação de Selo Fiscal

Este app simula a funcionalidade de **validação de selos fiscais** como na plataforma oficial **Prosefa**, usada em Angola para gestão de Selos Fiscais de Alta Segurança (SFAS).

O objetivo deste teste técnico é avaliar sua capacidade de desenvolver um aplicativo React Native com base em um cenário real de um sistema governamental.

## 🎯 Objetivo do Desafio

Criar um aplicativo em React Native que permita ao usuário **consultar e validar um selo fiscal**, digitando seu código ou lendo via QR Code.

## ✅ Funcionalidades Obrigatórias

- Tela de busca com campo de input para digitar o código do selo.
- Validação contra uma API local (mock) com dados de selos.
- Tela de resultado exibindo:
  - Código do selo
  - Tipo de produto (bebida, tabaco, etc.)
  - Nome do fabricante
  - Data de emissão
  - Status (válido, expirado, cancelado)
- Estilização simples e funcional.

## ➕ Funcionalidades Bônus (opcional)

- Leitura de QR Code (usando `expo-barcode-scanner` ou `react-native-camera`).
- Lista com os últimos selos consultados.
- Ícone ou cor visual para indicar o status (verde = válido, vermelho = expirado/cancelado).

## 💡 Tecnologias Esperadas

- React Native (Expo ou CLI)
- TypeScript
- React Navigation
- Context API ou Zustand
- Estilização básica com qualquer abordagem

## 📂 Mock API

Os dados dos selos estão disponíveis em:  
`src/data/selos.json`

## ⚙️ Como Executar

```bash
git clone https://github.com/seu-usuario/prosefa-selo-app.git
cd prosefa-selo-app
npm install
npm start
```

## 📤 Entrega

- Suba seu código em um repositório público (GitHub ou similar).
- Envie o link para avaliação técnica.
- Prazo sugerido: até **48 horas** após o recebimento.

## 👨‍💻 Boa sorte!
