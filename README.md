```cpp
#include <gmpxx.h>
#include <string>

typedef struct
{
  std::string name;
  int age;
  mpz_class lines_written;
} Human;

int main(int argc,char **argv)
{
  Human human;
  human.name = "Enzo";
  human.age = 19;
  human.lines_written = 28;
} 
```
