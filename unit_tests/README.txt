In order to test these unit tests, they have to be renamed to ChomskyNF.txt and moved to the 'tests' folder.
If you'd like to alter the code, you could also edit line 102 and 103 in ChomskyNF.py to take the unit_test
file location as input:

	    	print('\nTest : check normal form (test/ChomskyNF.txt)')
    		G.loadFromFile('tests/ChomskyNF.txt') # Change this to whatever file to be tested

Hope this helps!