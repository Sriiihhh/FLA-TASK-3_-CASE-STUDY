# FLA – PDA and CFG Case Study Analysis

## Project Overview
This project explores the design and implementation of Pushdown Automata (PDA) and Context-Free Grammars (CFG) through three practical case studies.

## Case Studies

1. **Balanced Brackets** – Checks whether brackets are correctly balanced using a stack-based PDA.
2. **Arithmetic Expression Validation** – Validates arithmetic expressions using CFG and operator precedence.
3. **Palindrome Checking** – Recognizes palindromes over the alphabet `{a, b}` using a PDA and CFG.

## Features
- PDA simulation using Python.
- CFG design for each case study.
- Ambiguous and unambiguous grammar analysis.
- Bounded ambiguity checking.
- Parse-tree generation and visualization.
- Automated testing using pytest.

## Technologies Used
- Python 3
- Graphviz
- NLTK
- Pytest
- Visual Studio Code

## Project Structure

```text
FLA_PDA_CFG_Project/
│
├── case_studies/
│   ├── balanced_brackets.py
│   ├── balanced_brackets.md
│   ├── arithmetic_expression.py
│   ├── arithmetic_expression.md
│   ├── palindrome.py
│   └── palindrome.md
│
├── diagrams/
│   ├── balanced_brackets_pda.py
│   ├── arithmetic_expression_pda.py
│   ├── arithmetic_parse_tree.py
│   ├── palindrome_pda.py
│   ├── bounded_ambiguity_check.py
│   └── (Generated PNG diagrams)
│
├── tests/
│   ├── test_balanced_brackets.py
│   ├── test_arithmetic_expression.py
│   └── test_palindrome.py
│
└── README.md
```

## Installation

Install the required Python packages:

```bash
pip install pytest graphviz nltk
```

Install the Graphviz application separately and ensure it is added to PATH.



## Test Results

All six automated test cases passed successfully.

## Conclusion

This project demonstrates how Pushdown Automata and Context-Free Grammars are used to recognize structured languages, validate expressions, and analyze grammar ambiguity. It also illustrates the importance of stack memory and parsing techniques in formal language theory.
