Name - Sejal Nitinkumar Vibhakar
UTA ID - 1001765264


Programming language - Python

How the code is structured?
	Initially the program takes three input from the command prompt i.e wumpus_rules, additional information and statement.
	Check_true_false takes three arguments as knowledge base, statement and additional symbols. First, the program check_true_false checks whether the knowledge 		base entails statement and returns true or false accordingly. Then it checks whether the knowledge base entails negation of the statement and returns true or 		false accordingly. The information in the additional file is used to reduce calls to the TT_Check_all function and the additional information symbols and truth 	value is stored in additional_symb. TT_True method determines if sentence is true or false. The output is stored in the result.txt file

How to run the code?
	python check_true_false.py wumpus_rule.txt additional_knowledge_file(e.g. kb_6) statement_file(e.g. statement.txt)
