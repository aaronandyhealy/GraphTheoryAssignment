## This is a go application that can:
Build a postfix expression from an infix expression
Build an NFA from a regular postfix expression.
Check to see if a string matches a regular expression.

## Description
The aim of this project is to write a program in the Go programming language that can build a non-deterministic finite automaton (NFA) from a regular expression, and can use the NFA to check if the regular expression matches any given string of text. This program does not use the regexp package from the Go standard library nor any other external library. A regular expression is a string containing a series of characters, some of which may have a special meaning. For example, this program can determine between characters ".", "|", "*", "+" and "?" which have the special meanings "concatenate", "or", "Kleene star", "match-one-or-more quantifier" and "match-zero-or-one quantifier" respectively.

## Running the program
This program is made using the Go programming language.

If you do not have Go installed visit this link to do so: https://golang.org/dl/

To clone the repository, open command prompt, and enter:

git clone https://github.com/aaronandyhealy/GraphTheoryAssignment

### To run this program, you need to: 
Navigate to where you the project was cloned to and enter:
go build G00333148_GraphTheory.go

followed by:
go run G00333148_GraphTheory.go

## Testing the Program
To test the program enter the string and regex you want tested when prompted to. The program will give either a true of false return depending on the result. If true the string is a direct match, otherwise the result will be false 
## Technologies Used
GoLang
Visual Studio Code
Git

## Resources
Dr Ian McLoughlin - Galway - Mayo Institute of Technology
https://web.microsoftstream.com/video/9d83a3f3-bc4f-4bda-95cc-b21c8e67675e
https://web.microsoftstream.com/video/68a288f5-4688-4b3a-980e-1fcd5dd2a53b
https://web.microsoftstream.com/video/bad665ee-3417-4350-9d31-6db35cf5f80d
https://www.cs.york.ac.uk/fp/lsa/lectures/REToC.pdf

## Developed By:
Aaron Healy
