
Compilador:

[Open Watcom v2 C/C++ ](https://github.com/open-watcom/open-watcom-v2/);

---

## Variaveis 

### Em C temos os seguintes tipos bsicos de variáveis:

| Tipo | bytes | Faixa mínima |
|--- |--- |--- |
| char | 8 | -127 a 127 |
| int | 16 | -32.767 a 32.767 |
| float | 32 | Seis dígitos de precisão  |
| double | 64 | Dez dígitos de precisão |


### Temos algumas variações destes tipos, que são:

| Tipo | Tamanho aproximado em bytes | Faixa mínima |
|--- |--- |--- |
| unsigned char | 8 |  0 a 255 |            
| signed char | 8 | -127 a 127 |                                            
| unsigned int |  16 | 0 a 65.535 |                      
| signed int |  16 | O mesmo que int |                                        
| short int |  16 | O mesmo que int |
| unsigned short int |  16 | 0 a 65.535 |
| signed short int | 16 | O mesmo que short int|
| long int | 32 | -2.147.483.647 a 2.147.483.647 |
| signed long int | 32 | o mesmo que long int |
| unsigned long int | 32 | 0 a 4.294.967.295 |
| long double | 80 | Dez dígitos de precisão |

## Forma de declaração de variável:

~~~c
tipo nome_variavel;
~~~

Os atributos podem ser inicializado , <b> com </b> ou <b> sem </b> a declaração do valor. 

~~~c
#include <stdio.h>

int main(void){
    int evento = 5 ;
    char corrida = ’C’;
    float tempo = 27.25;
    printf("O tempo vitorioso na eliminat´oria %c",corrida);
    printf("\nda competi¸c~ao %d foi %f.", evento, tempo);
    return 1;
} 
~~~

