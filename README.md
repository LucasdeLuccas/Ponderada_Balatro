# 🎮 Intelatro

Uma adaptação mobile do famoso jogo Balatro, desenvolvida com React Native e Expo. Intelatro é um jogo de cartas estratégico onde você deve construir a melhor mão possível em 10 rodadas, escolhendo cartas com diferentes efeitos para maximizar sua pontuação.

## Demonstração

[![Demonstração do Jogo](balatro/assets/icon.png)](https://youtube.com/shorts/3MCPPfg-g10?feature=share)


## 📱 Sobre o Jogo

Intelatro é inspirado no jogo Balatro, mas adaptado para uma experiência mobile mais acessível e rápida. O objetivo é simples: em 10 rodadas, você escolhe uma carta de cada vez entre 3 opções disponíveis, construindo uma mão que será avaliada ao final do jogo.

### Objetivo

Construir a melhor mão possível escolhendo cartas estrategicamente para maximizar sua pontuação final.

### 🃏 Tipos de Cartas

- **Cartas de Cor** (Vermelha, Azul, Verde, Amarela): +1 ponto cada
- **Carta Sorte**: +2 pontos
- **Carta Azar**: -2 pontos
- **Carta Nula**: 0 pontos
- **Carta Especial**: Dobra a pontuação final
- **Carta Bônus de Cores**: +3 pontos se tiver 3 cartas da mesma cor

## 🚀 Tecnologias Utilizadas

### Frontend

- **React Native** - Framework mobile
- **Expo** - Plataforma de desenvolvimento
- **TypeScript** - Tipagem estática
- **React Navigation** - Navegação entre telas
- **React Native Paper** - Componentes de UI
- **AsyncStorage** - Armazenamento local

### Backend

- **Node.js** - Runtime JavaScript
- **Express.js** - Framework web
- **MongoDB** - Banco de dados
- **Socket.io** - Comunicação em tempo real
- **JWT** - Autenticação

> ⚠️ **Nota**: O backend está em um repositório separado para melhor organização do projeto.

## 📋 Pré-requisitos

- Node.js (versão 18 ou superior)
- npm ou yarn
- Expo CLI
- Expo Go (app para testar no dispositivo)

## 🛠️ Configuração

### 1. Clone o repositório

```bash
git clone https://github.com/LucasdeLuccas/Ponderada_Balatro.git
cd balatro
```

### 2. Instale as dependências

```bash
npm install
```

### 3. Execute o projeto

```bash
# No diretório balatro
npx expo start
```

### 4. Teste o aplicativo

- **Android**: Escaneie o QR code com o Expo Go
- **iOS**: Use a câmera do iPhone para escanear o QR code
- **Web**: Pressione `w` no terminal

## 🎮 Como Jogar

1. **Início**: Digite seu nome e toque em "Iniciar Jogo"
2. **Rodadas**: Em cada uma das 10 rodadas, você verá 3 cartas
3. **Escolha**: Toque em uma carta para adicioná-la à sua mão
4. **Estratégia**: Considere os efeitos das cartas para maximizar pontos
5. **Resultado**: Ao final, veja sua pontuação e posição no ranking

## 🎮 Funcionalidades

- ✅ **Sistema de Ranking**: Compare sua pontuação com outros jogadores
- ✅ **Regras Integradas**: Acesse as regras diretamente no app
- ✅ **Interface Intuitiva**: Design moderno e responsivo
- ✅ **Persistência Local**: Seus dados são salvos localmente
- ✅ **Tema Personalizado**: Cores laranja amarelado e verde petróleo


