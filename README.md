# 🧮 CLI Calculator

This is a simple Python-based command-line calculator that allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, division, and exponentiation. The calculator runs in an interactive loop, prompting users to select an operation and input values, then returning the result.

## 🚀 Features

- Interactive command-line interface
- Five basic mathematical operations:
  - Addition
  - Subtraction
  - Multiplication
  - Division
  - Exponentiation
- Looped execution for continuous calculations
- Clean UI with automatic terminal clearing (using `os.system("clear")`)

## 🛠️ Technologies

- Python 3
- `os` module for terminal management

## 📂 How to Run

1. Make sure you have Python 3 installed.
2. Clone this repository or download the script.
3. Run the script from your terminal:

```bash
python calculadora.py
```

4. Follow the on-screen prompts to perform calculations.

## 📸 Example

```
0 : Soma
1 : Subtração
2 : Multiplicação
3 : Divisão
4 : Exponenciação

Escolha a operação que deseja realizar:
0

>>> + escolhida.

Qual o primeiro valor?
10
Qual o segundo valor?
5

10.0 + 5.0 = 15.0
Deseja fazer outra operação? 0 - SIM, 1 - NÃO
```

## 📌 Notes

- The terminal is cleared after each operation (may need `cls` on Windows).
- Only basic error handling is in place; invalid inputs may raise exceptions.

