# narzedzia_informatyczne
Robię coś nawet nie wiem co <br/>
A [TU](https://pl.pinterest.com/pin/967007351224894038/) możecie popatrzyć na małego lodowego króla
## Moje ulubione bandy
### Śpiewające po angielsku
- My Chemical Romance :skull:
- Bullet for my Valentine :rose:
- blessthefall
### Śpiewające po rosujsku
1. Neversmile
2. Neonate
3. Оригами
```C
#include <stdlib.h>
#include <stdio.h>
int main(void) {
    int seed, n;
    printf("Wpisz wartosc zarodka: ");
    scanf("%d",&seed);
    printf("Wpisz liczbe generowanych liczb pseudolosowych: ");
    scanf("%d",&n);
    int liczby[n];
    srand(seed);
    for(int i = 0; i<n ;i++) {liczby[i]=rand();}
    for(int i = n; i>0; i--){printf("%d ",liczby[i-1]);}
    
    return 0;
}
```
Jakaś | mała | tablica
--- | --- | ---
nie | wiem | co
