1108-feel-substring-after-function
--------------------

### Description ###

DMN Model [1108-feel-substring-after-function.dmn](./1108-feel-substring-after-function.dmn) tests DMN specification conformance of `FEEL built-in function 'substring after(string, match)`. Tested category is `string functions`.

#### Specification Reference(s): ####
 * DMN 1.1 - 10.3.4.3 Table 60

### Test Cases ###

|Decision Name| Literal Expression (FEEL) | Expected Result (Expected Type)|
|-------------|-------------------------- |--------------------------------|
|feel-substring-after-function_001_f532be66f2|substring after("foobar","ob")|"ar" (string)|
|feel-substring-after-function_002_f20d66fc1e|substring after("foobar","o")|"obar" (string)|
|feel-substring-after-function_003_367612fc8b|substring after("foobar","x")|"" (string)|
|feel-substring-after-function_004_e448ee2dad|substring after("","")|"" (string)|
|feel-substring-after-function_005_429efdafd0|substring after("","a")|"" (string)|
|feel-substring-after-function_006_bf89d6b618|substring after("abc","")|"abc" (string)|
|feel-substring-after-function_007_529baaeb0b|substring after("abc","c")|"" (string)|
|feel-substring-after-function_008_1e611924ea|substring after("abc","a")|"bc" (string)|
|feel-substring-after-function_009_712fe2842f|substring after(string:"foobar",match:"ob")|"ar" (string)|
|feel-substring-after-function_010_40e159d07a|substring after(string:"foobar",match:"b")|"ar" (string)|

         

### Disclaimer ###
This page is a simple view for the underlying DMN model file [1108-feel-substring-after-function.dmn](./1108-feel-substring-after-function.dmn).
The purpose of the model is to test and validate FEEL expressions. Therefore the underlying DMN model is simplistic:
Each decision node contains one literal expression under test. The table above shows the decision, the underlying FEEL expression and the expected result.

Site generated by [ACTICO GmbH](https://actico.com) for [Technology Compatibility Kit (TCK)](https://dmn-tck.github.io/tck/) for the Decision Model and Notation (DMN) standard.

[DMN 1.1. Specification Document](http://www.omg.org/spec/DMN/1.1/) 
  