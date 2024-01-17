Компиляция:
bison -d MySmartHome.y
flex MySmartHome.l
gcc -o Main MySmartHome.tab.c lex.yy.c MySmartHome.c -lm
Запуск программы:
./Main input.txt > output.txt
or 
./Main input.txt