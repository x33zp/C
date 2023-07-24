printf("{string/text}\n"); - function that allows you format text in the screen
\n - creates  new line after program is been run, also known as escape sequence
get_string("{string/text}\n"); - function that prompts the user to quote... string answer = get_string("{string/text}\n");
%s - indicates that this is space for a string ...  string answer = get_string("{string/text} \n"); printf("hello, %s\n. answer");
== - to indicate that both are equal to eachother
"" '' - double quotes for strings, single quotes for char
|| - or
++ - adding one to already existing
-- - subtracting one to already existing

while loop...
(
int i = 0;
    while (i < 3)
    {
        printf("meow\n");
        i++;
    } 
.........

)

while loop forever...
(
while (true)
{
    printf("meow\n)
}
)

for loop...
(
int main(void)
{
    for (int i = 0; i < 4; i++)
    {
        printf("?");
    }
    printf("\n");
}
)



compile cs50 - clang hello.c -o hello -lcs50