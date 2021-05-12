#include <stdio.h>

void create_array(int arr[10]) {
printf("Введіть масив цілих чисел\n");
for (int i=0; i<10; i++) {
printf("Введіть %d елемент масиву: ", i+1);
scanf("%d", &arr[i]);
}
}

void print_arr(int arr[10]) {
printf("\n\nУтворений масив:\n");
printf("{");
for (int i=0; i<10; i++) {
if (i == 9) {
printf("%d", arr[i]);
}
else {
printf("%d, ", arr[i]);
}
}
printf("}");
}

void min_max(int arr[10]) {
int min = arr[0], max = arr[0], min_index = 0, max_index = 0;

for (int i=0; i<10; i++) {
if (arr[i] < min) {
min = arr[i];
min_index = i;
}
if (arr[i] > max) {
max = arr[i];
max_index = i;
}
}
printf("\nІндекс мінімального елемента: %d\n", min_index);
printf("Індекс максимального елемента: %d\n", max_index);
float n = (max_index + min_index) / 2;
printf("Середнє арифметичне мінімального та максимального індексів: %.2f", n);
}


int main() {
int arr[10];
//Створення масиву
create_array(arr);
// Вивід масиву
print_arr(arr);
// Середнє арифметичне мінімального та максимального індексів
min_max(arr);
}
