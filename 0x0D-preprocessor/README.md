0.
#ifndef OBJECT_LIKE_MACRO_H
#define OBJECT_LIKE_MACRO_H

#define SIZE 1024

#endif

1.
#ifndef PI_H
#define PI_H

#define PI 3.14159265359

#endif

2.
#include <stdio.h>

/**
 * main - prints the name of the file
 *
 * Return: Always 0 (Success)
 */

int main(void)
{
	printf("%s\n", __FILE__);
	return (0);
}

3.
#ifndef FUNCTION_LIKE_MACRO_H
#define FUNCTION_LIKE_MACRO_H

#define ABS(x) ((x) < (0) ? -(x) : (x))

#endif

4.
#ifndef SUM_H
#define SUM_H

#define SUM(x, y) ((x) + (y))

#endif
