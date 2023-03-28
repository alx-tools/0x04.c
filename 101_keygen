#include <stdio.h>
#include <stdlib.h>
#include <time.h>

/**
 * main - Generates a random valid password for 101-crackme
 *
 * Return: Always 0
 */
int main(void)
{
    char password[84];
    int i, sum, diff;

    srand(time(NULL));

    for (i = 0, sum = 0; sum < 2772 - 122; i++)
    {
        password[i] = rand() % 94 + 33;
        sum += password[i];
    }

    diff = sum - 2772 + 122;
    password[i] = diff;

    printf("%s", password);

    return (0);
}
