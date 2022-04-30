# Pico Pisca
Teste com o Raspberry Pi Pico para piscar um Led.

## Compilação
Para compilar use o seguinte procedimento:

1. Crie um diretório build:

`mkdir build`

Depois entre no diretório build:

`cd build`

2. Use o cmake para gerar o Makefile

`cmake ..`

3. Compile o código usando o comando make:

`make -j2`

4. Copie o a arquivo .uf2 para o Raspbery Pi Pico
