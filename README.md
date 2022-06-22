# Exercício de geração procedural de texturas

Disciplina: Computação Gráfica

Autor: Bernardo Ternus de Abreu

**Compilação da Biblioteca Libnoise:**

Primeiramente, inicializar o submodule que contém a libnoise
$ git submodule update --init
Rodar script gerado para compilar a biblioteca
$ ./build-libnoise.sh

*Compilando e executando o código da geração:*

$ mkdir -p build && cd build
$ cmake ..
$ make
$ ./app

**Resultados**

1) Gerando 4 mapas vizinhos com 4 imagens

![image](https://user-images.githubusercontent.com/90293389/175091854-16434cde-bd90-4a2a-9e4b-3763b19c2658.png)

![image](https://user-images.githubusercontent.com/90293389/175091919-ee89d2f2-1408-4966-8a47-ba32a82db1aa.png)

![image](https://user-images.githubusercontent.com/90293389/175091950-07345bc1-2dc7-4446-aabf-21e908ca5bd7.png)

![image](https://user-images.githubusercontent.com/90293389/175091978-2e8fd8a5-d770-431c-b69d-3bdc4c8c26c2.png)

2) Explorando números diferentes de oitavas, frequencia e persistência com 8 imagens

3) Criando 2 diferentes mapeamentos de biomas (Gradientes) com 2 imagens

Bioma 1 - Superficie global - 

![image](https://user-images.githubusercontent.com/90293389/175092065-ab5a287c-7ca3-4bd1-9983-04e59b667777.png) 

Bioma 2 - 

![image](https://user-images.githubusercontent.com/90293389/175093010-5a07546f-feb8-442a-a108-cb76d6aba4b7.png)

