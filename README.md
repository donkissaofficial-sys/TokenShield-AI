# TokenShield AI 🛡️
⚠️ Important (TokenShield AI is a functional multi-agent crypto analysis system — <b>not just a UI concept.<b/>)

Multi-Agent Crypto Safety Assistant for Binance Smart Chain
TokenShield AI is a multi-agent crypto safety assistant designed to help users analyze the risk of tokens on Binance Smart Chain.

The system uses a collaborative AI architecture inspired by OpenClaw, where multiple specialized agents ("Claws") work together to evaluate token risk and explain results in simple language.

## 🚀 Live Demo
https://silver-emu-581336.hostingersite.com/

## 📂 Project Structure

TokenShield AI uses a multi-agent workflow:

Input Claw → Data Claws → Risk Claw → Explanation Claw → Frontend

### Claws

1. Input Claw  
Receives token name or contract address from the user.

2. Holder Analysis Claw  
Fetches token holder distribution using BscScan API.

3. Liquidity Claw  
Analyzes liquidity pool data to estimate trading safety.

4. Risk Claw  
Combines holder concentration and liquidity data to compute a risk level.

5. Explanation Claw  
Generates human-readable explanations for the risk assessment.

6. Frontend Claw  
Displays results to the user including:
- Risk meter
- Holder distribution
- Liquidity insights
- AI explanation
<h2>Risk Analysis Live Proof</h2>
  <img src="Screenshot/Risk Analysis.png" width="800"/>

## ⚙️ Features

- Token risk analysis
- Holder distribution detection
- Liquidity safety check
- AI explanation for beginners
- English / Chinese language toggle
- Clean dashboard UI

## 🧠 Multi-Agent Architecture

TokenShield AI demonstrates a multi-agent architecture inspired by OpenClaw.

Each "Claw" performs a specific task and collaborates with other agents to produce a final token safety evaluation.

This design improves transparency and modular analysis for crypto investors.

## 🔗 APIs Used

- BscScan API (token holder data)
- Optional: CoinGecko or Binance API for token metadata

## 🎯 Use Case

TokenShield AI helps users:

- Detect risky tokens
- Understand token holder concentration
- Evaluate liquidity before trading
- Learn about token safety in simple terms

## 📸 Screenshots

## 🏆 Built For

Binance AI OpenClaw Challenge  
#AIBinanceshowcasing

## 👨‍💻 Author
KSA
