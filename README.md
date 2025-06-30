<h1 align="center">
  🪙 DanCoin Blockchain
</h1>

<p align="center">
  Rede blockchain Proof of Stake construída com Cosmos SDK, pronta para testes, expansão e deploy público.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Chain-ID-dancoin--testnet-blue" />
  <img src="https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 📜 Visão Geral

A **DanCoin** é uma blockchain customizada com 21 milhões de tokens `danc`, construída com o Cosmos SDK, rodando em Proof of Stake (PoS). Ela está pronta para uso local, criação de validadores, contratos inteligentes CosmWasm e futura abertura pública (testnet/mainnet).

---

## 🚀 Como Rodar a DanCoin

### Pré-requisitos

- Go 1.21+
- Linux/WSL ou macOS
- Git
- Starport (opcional)
- Cosmos SDK (compilado)

### Passos

```bash
git clone https://github.com/seu-usuario/dancoin.git
cd dancoin
chmod +x scripts/*.sh
./scripts/init.sh
./scripts/start.sh
