# NFChecker
A Python tool to analyze functional dependencies in a relational schema. It identifies candidate keys, prime and non-key attributes, and determines the highest normal form (1NF, 2NF, 3NF, BCNF). Users input attributes and functional dependencies, and the tool computes normalization details, aiding in efficient database design.
## Database Normalization & Functional Dependency Analyzer

This Python tool helps analyze functional dependencies (FDs) in a relational database schema. It identifies:
1. Candidate Keys
2. Prime & Non-Key Attributes
3. Highest Normal Form (1NF, 2NF, 3NF, BCNF)

# Features
1. Finds all Candidate Keys for any given schema
2. Detects Prime and Non-Key Attributes
3. Determines the Highest Normal Form (1NF → BCNF)
4. Works for any number of attributes & FDs

# Usage
1️ Run the script and enter the attributes.
2️ Provide the functional dependencies interactively.
3️ The tool will analyze and display the keys & normal form.

# Example Input & Output
Enter attributes (comma-separated): A,B,C,D  
Enter the number of functional dependencies: 2  
Enter LHS of FD: A  
Enter RHS of FD: B  
Enter LHS of FD: B  
Enter RHS of FD: C,D  

# Output:
Candidate Keys: [('A')]  
Prime Attributes: {'A'}  
Non-Key Attributes: {'B', 'C', 'D'}  
Highest Normal Form Satisfied: BCNF  
