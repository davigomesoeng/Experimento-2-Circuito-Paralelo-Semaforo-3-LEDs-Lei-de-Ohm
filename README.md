# 🚦 Semáforo Simples — 3 LEDs em Paralelo
> Lei de Ohm e Circuitos em Paralelo na prática

## 📸 Montagem
<img width="1366" height="542" alt="Projeto2" src="https://github.com/user-attachments/assets/461ec739-e002-4b4d-b494-cbbcbf34d96d" />


## 🔧 Componentes
- 1 Bateria CR2032 — 3,0V
- 3 Resistores — 220 Ω cada
- 3 LEDs — Vermelho, Amarelo e Verde

## 🧠 Como montei
- Cada LED tem seu próprio resistor em série
- Todos os conjuntos (LED + resistor) estão conectados em **paralelo**
- O positivo de todos vai para o polo positivo da bateria
- O negativo de todos vai para o polo negativo da bateria

## ⚠️ O ERRO que encontrei e consertei
> No primeiro teste, o LED do meio não acendia. Descobri que **faltava um fio conectando o resistor do meio ao de cima**. Sem um caminho completo, a corrente não chega. A corrente sempre precisa de um circuito fechado!

## 💡 O que aprendi
- Em circuito paralelo: **todos recebem a mesma tensão**
- Cada ramo tem sua própria corrente — se um falha, os outros continuam
- **Conexões incompletas = circuito aberto = não funciona**
- Resistor é sempre necessário para proteger o LED
