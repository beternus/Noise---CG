# Noise---CG
Noise - CG

**Exercício de geração procedural de texturas**

Disciplina: Computação Gráfica
Autor: Bernardo Ternus de Abreu

**Compilação da Biblioteca Libnoise:**
Primeiramente, inicializar o submodule que contém a libnoise
$ git submodule update --init
Rodar script gerado para compilar a biblioteca
$ ./build-libnoise.sh

Compilando e executando o código da geração:

$ mkdir -p build && cd build
$ cmake ..
$ make
$ ./app

**Resultados**
1) Gerando 4 mapas vizinhos (4 imagens)
2) Explorando números diferentes de oitavas, frequencia e persistência (8 imagens)
3) Criando 2 diferentes mapeamentos de biomas (Gradientes) (2 imagens)

