printf("{string/text}\n"); - function that allows you format text in the screen
\n - creates  new line after program is been run, also known as escape sequence
get_string("{string/text}\n"); - function that prompts the user to quote... string answer = get_string("{string/text}\n");
%s - indicates that this is space for a string ...  string answer = get_string("{string/text} \n"); printf("hello, %s\n. answer");
== - to indicate that both are equal to eachother
"" '' - double quotes for strings, single quotes for char
|| - or

compile cs50 - clang hello.c -o hello -lcs50