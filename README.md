// main.c
#include <stdio.h>
#include <stdlib.h>

#define MAX_MESSAGE_SIZE 30

int main(int argc, char **argv) {
  char *str = malloc(sizeof(char) * MAX_MESSAGE_SIZE);
  str = argv[1];
  puts(str);
  free(str);

  return 0;
}
