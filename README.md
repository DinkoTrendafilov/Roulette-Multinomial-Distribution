# Roulette Multinomial Distribution Analyzer

A Python script that calculates and visualizes the probability distribution of outcomes in European Roulette over multiple spins using multinomial distribution.

## 🎯 Features
- Calculates all possible combinations of Red/Black/Zero outcomes
- Uses multinomial coefficients for probability computation
- Displays:
  - All possible outcome combinations sorted by probability
  - Top 5 most likely outcomes
  - Expected values (means)
  - Frequency distribution of multinomial coefficients
- Logarithmic calculations for numerical stability

## 🎰 Mathematical Background
European Roulette probabilities:
- **Red**: 18/37 ≈ 48.65%
- **Black**: 18/37 ≈ 48.65%
- **Zero**: 1/37 ≈ 2.70%

For `n` spins, the script computes:

P(red=r, black=b, zero=z) = n!/(r!·b!·z!) × (18/37)^r × (18/37)^b × (1/37)^z


## 📊 Output Includes
- All combinations with their probabilities
- Multinomial coefficients
- Odds format (1 in X trials)
- Cumulative probabilities for top combinations
- Expected value analysis

## 🚀 Usage
```bash
python roulette_multinomial_distribution.py
Enter number of events: 10

📈 Example Application

Useful for:

    Probability analysis in gambling studies

    Understanding multinomial distributions

    Statistical modeling of independent events

    Educational purposes in probability theory

📋 Requirements

    Python 3.x

    Standard library only (math, collections)
