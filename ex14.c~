#include <stdio.h>
#include <ctype.h>
#include <string.h>

// forward declarations
int l[];
void print_letters(int l[], char arg[]);

void print_arguments(int argc, char *argv[])
{
    int i = 0;
    int l[argc];

    for(i = 0; i < argc; i++) {
        l[i] = strlen(argv[i]);
        print_letters(l[i], argv[i]);
    }
}

void print_letters(int l, char arg[])
{
    int i = 0;

    for(i = 0; i <= l; i++) {
        char ch = arg[i];

        if(isalpha(ch) || isblank(ch)) {
            printf("'%c' == %d ", ch, ch);
        }
    }

    printf("\n");
}


int main(int argc, char *argv[])
{
    print_arguments(argc, argv);
    return 0;
}
