## Jogo da Velha em Socket - Linguagem C | @ 2016
![Flow Game](https://github.com/alexsandertech/jogo-da-velha-socket-c/blob/main/asset/jogo.png)

#### Em um computador com linux e com compilador gcc instalado:
- Gere os objetos:
```sh
gcc client.c -o cliente
gcc servidor.c -o servidor
```
- Rode o servidor:
```sh
./servidor
```
Em um novo console execute o primeiro cliente:
```sh
./cliente 127.0.0.1
```
Em um novo console execute o segundo cliente:
```sh
./cliente 127.0.0.1
```