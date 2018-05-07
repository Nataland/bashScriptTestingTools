# bashScriptTestingTools
Two useful testing tools to - produce output of a program and compare actual vs expected output.

##To produce outputs only:
Run the following command (replace findGreater with the name of your program)
```
./produceOutputs suite.txt ./findGreater
```
##To compare actual output with expected output:
Run the following command (replace findGreater with the name of your program)
```
./runSuite suite.txt ./findGreater
```
The program will output the test cases where actual output is not equal to expected output.
If you run `./runSuite` and nothing happened, this means that all test cases have passed.
