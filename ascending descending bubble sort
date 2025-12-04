#include <stdio.h>

int main() {
    int n;
    printf("Enter number of elements: ");
    scanf("%d", &n);
    int a[n];
    printf("Enter %d elements:\n", n);
    for (int i = 0; i < n; i++)
        {
        scanf("%d", &a[i]);
        }
    int x;
    printf("For ascending order 1\nFor descending order 2\n");
    scanf("%d", &x);
    if (x==1)
            {
                for (int i = 0; i < n - 1; i++)
                {
                    for (int j = 0; j < n - i - 1; j++)
                    {
                        if (a[j] > a[j + 1])
                        {
                            int temp = a[j];
                            a[j] = a[j + 1];
                            a[j + 1] = temp;
                        }
                    }
                }
                printf("Sorted array:\n");
                for (int i = 0; i < n; i++)
                {
                    printf("%d ", a[i]);
                }
            }
    else if (x==2)
    {
         for (int i = 0; i < n - 1; i++)
                {
                    for (int j = 0; j < n - i - 1; j++)
                    {
                        if (a[j] < a[j + 1])
                        {
                            int temp = a[j];
                            a[j] = a[j + 1];
                            a[j + 1] = temp;
                        }
                    }
                }
                printf("Sorted array:\n");
                for (int i = 0; i < n; i++)
                {
                    printf("%d ", a[i]);
                }
    }
    else
        {
            printf("Try Again Sir\n");
        }
    return 0;
}
