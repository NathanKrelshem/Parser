# Compiler Parser Project
This project implements a compiler parser using Python. The parser is designed to generate a parse tree for a subset of the Jack programming language. The parse tree represents the syntactic structure of the input code.

### How It Works
The CompilerParser class takes a list of tokens as input, where each token represents a component of the Jack code (e.g., keywords, identifiers, symbols). The parser processes these tokens according to the rules of the Jack language grammar to generate a parse tree.

The parse tree is constructed recursively, with each method in the CompilerParser class responsible for generating a specific part of the parse tree (e.g., class definition, variable declaration, statement). The ParseTree class is used to represent nodes in the parse tree.

### What I Learned
- Understanding of recursive descent parsing technique.
- Parsing techniques for programming languages.
- Familiarity with context-free grammars and parsing rules.
- Working with abstract syntax trees (AST) for representing program structure.

### How to Run and Test the Program
- Ensure you have Python installed on your system.
- Clone the repository to your local machine.
- Navigate to the project directory.
- Ensure both CompilerParser.py and ParseTree.py files are present in the directory.
- Open CompilerParser.py file.
- Uncomment the desired test case by removing the comment symbols (#) from the corresponding lines.
- Run the CompilerParser.py file.
Example:

'''bash
python CompilerParser.py
'''

The program will execute the selected test case and print the resulting parse tree.
Note: Modify the tokens list in the __main__ block of CompilerParser.py to test different code snippets.