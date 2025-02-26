# 🚀 Crypto Trader App - Mobile

## 📌 Overview

Crypto Trader App é um app cross-platform (iOS/Android) para trading de criptomoedas, projetado para oferecer uma experiência fluida e segura para investidores iniciantes e avançados. O app permite desde a conversão de BRL para ativos como BTC, ETH, SOL e USDT via PIX até estratégias automatizadas e análise de mercado.

## 🛠️ Stack Técnica

- **Frontend**: React Native (Expo / Bare Workflow)
- **State Management**: Zustand para persistência leve, Redux Toolkit para sincronização global
- **Navigation**: React Navigation (Stack, Tab)
- **Networking**: Axios + SWR (cache otimizado)
- **UI/UX**: Tailwind + NativeWind
- **Crypto SDKs**: Solana Web3.js, ethers.js
- **Autenticação**: Firebase Auth / OAuth + JWT
- **Payments**: OpenPix API
- **Storage**: AsyncStorage (secure storage para chaves API)
- **Crash Reporting**: Sentry
- **CI/CD**: EAS Build + Fastlane

## 📲 Features

✅ **Onboarding + KYC**: Cadastro seguro e verificação de identidade (OCR e selfie match).  
✅ **PIX On/Off Ramp**: Depósitos e saques instantâneos via OpenPix API.  
✅ **Spot Trading**: Swap instantâneo de SOL/ETH/USDT com taxas competitivas.  
✅ **Bots de Trading**: Stop Loss / Stop Win & Sniper de memecoins.  
✅ **Copiar Whale Trades**: Clone de estratégias de grandes players do mercado.  
✅ **Listagem de Tokens**: Market cap, holders e análises de ativos populares.  
✅ **Carteiras pré-montadas**: Alocações recomendadas para diferentes perfis.  
✅ **Programa de Afiliados**: Ganhe 10% das taxas de transação dos seus indicados.  
✅ **Cursos In-App**: Vídeos educativos sobre criptomoedas para iniciantes e traders avançados.  

## 🏗️ Roadmap

- [x] Onboarding com autenticação segura
- [x] Integração com PIX para depósitos e saques
- [ ] Adição de WebSockets para preços em tempo real
- [ ] Implementação do módulo de análise fundamentalista
- [ ] Otimização de performance para Android (Hermes)

## 📦 Setup Dev

1. Clone o repositório:
   ```sh
   git clone git@github.com:cryptoapp/mobile.git && cd mobile
