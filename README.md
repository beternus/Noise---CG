# Exercício de geração procedural de texturas

Disciplina: Computação Gráfica

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

1) frequência: 0,8
   oitavas = 4
   persistência = 0,6
  
  ![oitavas 1](https://user-images.githubusercontent.com/90293389/175180483-4b9b9f47-e003-49d5-ba73-10870a62bdd4.jpeg)

2) frequência: 0,7
   oitavas = 4
   persistência = 0,6
   
   ![oitavas 2](https://user-images.githubusercontent.com/90293389/175180533-b1caa609-1bf8-4665-8901-fc69bb7551ca.jpeg)

3) frequência: 0,6
   oitavas = 3
   persistência = 0,6
   
   ![oitavas 3](https://user-images.githubusercontent.com/90293389/175180582-ea7310ed-7379-4938-9f3e-c974947a807a.jpeg)

4) frequência = 0,6
   oitavas = 5
   persistência = 0,5
   
   ![oitavas 4](https://user-images.githubusercontent.com/90293389/175180635-189e9d8b-19b0-49fe-8dfb-5e30e3062ec3.jpeg)

5) frequência = 0,5
   oitavas = 4
   persistência = 0,9
   
   ![oitavas 5](https://user-images.githubusercontent.com/90293389/175180696-b40a21f5-ac30-46c2-8f95-ece474ba8ae9.jpeg)

6) frequência = 0,1
   oitavas = 1
   persistência = 0,1
   
   ![oitavas 6](https://user-images.githubusercontent.com/90293389/175180767-4ab0638f-657f-4172-839f-17d3beb7db1c.jpeg)

7) frequência = 0,9
   oitavas = 6
   persistência = 0,9
   
![oitavas 7](https://user-images.githubusercontent.com/90293389/175180895-1adf9602-2ca4-48d6-b7cc-3e558a2822d1.jpeg)

8) frequência = 5
   oitavas = 4
   persistência = 0,7

![oitavas 8](https://user-images.githubusercontent.com/90293389/175180875-eee2b937-49f3-4042-8474-c95f2b398353.jpeg)






3) Criando 2 diferentes mapeamentos de biomas (Gradientes) com 2 imagens

Bioma 1 - Superficie global - 

![image](https://user-images.githubusercontent.com/90293389/175092065-ab5a287c-7ca3-4bd1-9983-04e59b667777.png) 

Bioma 2 - 

![image](https://user-images.githubusercontent.com/90293389/175093010-5a07546f-feb8-442a-a108-cb76d6aba4b7.png)

