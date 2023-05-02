Download Link: https://assignmentchef.com/product/solved-col226-assignment-2-lexical-analysis-for-spreadsheet
<br>
Assignment 2: Lexical Analysis for Spreadsheet Assignment

Read the resource file describing assignments 2-4.

In Assignment 2: you only need to provide the lex specifications, and so do not need to concern yourself with the meaning and implementation of the operations and how they are used.

You need to write clear specifications of the OCaml functions which you implement, and document your code.

Tokens for OCamllex would be, but not limited to:

<ul>

 <li>Float constants (with optional sign, no redundant initial zeroes before the decimal point or unnecessary trailing zeroes after the decimal point)</li>

 <li>Parenthesis — ( and )</li>

 <li>Brackets — [and ]</li>

 <li>Comma — ,</li>

 <li>Colon— :</li>

 <li>Indices I — [ i ‘ j ]</li>

 <li>Ranges 1)</li>

 <li>Unary operators: SUM, AVG, MIN, MAX, COUNT, etc. (see below)</li>

 <li>Binary operators: ADD (addition), SUBT (subtraction), MULT (multiplication), DIV (division)</li>

 <li>Assignment operator</li>

 <li>Formula termination ; (semicolon)</li>

</ul>

The function operations can be one of the following:

Type 1 (unary operations on ranges of cells):

<ul>

 <li>COUNT</li>

 <li>ROWCOUNT</li>

 <li>COLCOUNT</li>

 <li>SUM</li>

 <li>ROWSUM</li>

</ul>

<h1>• COLSIJM</h1>

<ul>

 <li>AVG</li>

 <li>ROWAVG</li>

</ul>

<h1>• COLAVG</h1>

<ul>

 <li>MIN</li>

 <li>ROWMIN</li>

 <li>COLMIN</li>

 <li>MAX</li>

 <li>ROWMAX</li>

 <li>COLMAX</li>

</ul>

Type 2 (binary operations on ranges of cells):

<ul>

 <li>ADD</li>

 <li>SUBT</li>

 <li>MULT</li>

</ul>

<h1>• DIV</h1>