# cdi_05
#include <studio.h>

int main(){
  gpio_int_mask(0x3ff);
  gpio_set_dir_in_masked(0x3ff);
  gpio_set_dir_out_masked(0x7f);
  int contador=0;
  int numero0=0x3f;
  int numero1=0x6;
  int numero2=0x5b;
  int numero3=0x4f;
  int numero4=0x66;
  int numero5=0x6d;
  int numero6=0x7d;
  int numero7=0x07;
  int numero8=0x7f;
  int numero9=0x6b;
  
  while(1){
    char val=gpio_get(7);
    char val12=gpio_get(8);
    char val13=gpio_get(9);
    
    if(val ==1) {
        contador++;
    if(val ==0)
    contador--;
    if(val3 ==3)
    contador ==0;
    if(contador>9)
    contador ==9;
    if(contador<0)
    contador==0;
    
    }
    if(contador==0)
    gpio_put(0x7f,numero0);
    if(contador==1)
    gpio_put(0x7f,numero1);
    if(contador==2)
    gpio_put(0x7f ,numero2);
    if(contador==3)
    gpio_put(0x7f ,numero3);
    if(contador==4)
    gpio_put(0x7f ,numero4);
    if(contador==5)
    gpio_put(0x7f ,numero5);
    if(contador==6)
    gpio_put(0x7f ,numero6);
    if(contador==7)
    gpio_put(0x7f ,numero7);
    if(contador==8)
    gpio_put(0x7f ,numero8);
    if(contador==9)
    gpio_put(0x7f ,numero9);
