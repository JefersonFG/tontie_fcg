# Tontie - FCG

Trabalho final da disciplina de Fundamentos de Computação Gráfica.

## Instruções para desenvolvimento

Para compilar e executar o programa execute os seguintes comandos à partir da raíz do repositório:

```bash
cmake -DCMAKE_BUILD_TYPE=Debug -DCMAKE_SH="CMAKE_SH-NOTFOUND" -G "CodeBlocks - MinGW Makefiles" -B cmake-build-debug
cd cmake-build-debug
make
cd ../bin/Debug
./tontie_fcg
```

E para compilar e executar no modo release:

```bash
cmake -DCMAKE_BUILD_TYPE=Release -DCMAKE_SH="CMAKE_SH-NOTFOUND" -G "CodeBlocks - MinGW Makefiles" -B cmake-build-release
cd cmake-build-release
make
cd ../bin/Release
./tontie_fcg
```
