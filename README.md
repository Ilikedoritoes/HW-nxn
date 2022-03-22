#include <stdlib.h>
#include <stdio.h>
#define row 4
#define colume 4
#define _CRT_SECURE_NO_WARNINGS

int main()
{
	int mtrx[row][colume] = { {1,1,1,1},{1,1,1,1},{1,1,1,1},{1,1,1,1}};  
	int down = 0, up = 0, x, y;
	int pp = row - 1;

		for (x = 0; x <= pp; x++)
		{
			for (y = 0; y <= pp; y++)
			{

				up == (mtrx[x][y] + up);

			}
		}

		for (x = row; x >= pp; x--)
		{
			for (y = colume; y >= pp; y--)
			{

				down == (mtrx[x][y] + down);

			}
		}

		if (down == up)
			printf("the numbers above are equal to the ones under...\n");
		else
			printf("fuck");

	


	system("pause");
}
