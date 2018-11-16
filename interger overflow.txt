#include <stdio.h>

int main(void) {
  // 2147483647
  int a = 2147483676;
  printf("%d", a);	// result: -2147483620
  return 0;
}