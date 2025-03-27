# Impermanent Loss Hedging in Constant Product AMMs

This repository contains the code and simulations presented in the blog post and paper:  
**"Impermanent Loss from a Quantitative Perspective: Static Replication and Hedging via Options"**

We develop a simple yet powerful framework to model impermanent loss (IL) in constant product automated market makers (CPMMs), such as Uniswap v2. Using Python and Jupyter, we simulate:

- The dynamic value of liquidity provider (LP) positions
- The IL incurred under price movements
- A static hedging strategy based on a long strangle of European options

The goal is to provide DeFi researchers, quant developers, and protocol designers with an educational and adaptable tool for exploring IL mitigation strategies.

📈 **Try it live on Google Colab**  
[Open Notebook](https://colab.research.google.com/drive/110hccZ7ovWjhFUVmDAHWOr4yAYJizMe3)

---

## Contents

- `hedging_simulation.ipynb` – main notebook with simulations
- `data/` – placeholder for option price inputs if using real data
- `README.md` – documentation and references

---

## License

MIT License

---

## Authors

- Agustín Muñoz González — [@AguuMg]([https://twitter.com/agusmux](https://x.com/AguuMg))
- Juan I. Sequeira
- Ariel Dembling
