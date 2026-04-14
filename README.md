# TSP Heurísticas de Inserção

Implementação das heurísticas Nearest Insertion e Smallest Insertion para o Problema do Caixeiro Viajante (TSP) em Java.

## Como executar

1. Compile os arquivos:
   ```
   cd src
   javac *.java
   ```

2. Execute com um arquivo de entrada:
   ```
   java Main ../dados/usa13509.txt
   ```

## Resultados para usa13509.txt

- Nearest insertion: comprimento ≈ 77449.98
- Smallest insertion: comprimento ≈ 45074.78

## Descrição das Heurísticas

- **Nearest Insertion**: Insere o novo ponto próximo ao ponto mais próximo no tour atual.
- **Smallest Insertion**: Insere o novo ponto na posição que causa o menor aumento no comprimento total.

## Vídeo Explicativo

[Link do vídeo](https://example.com/video)  // Substitua pelo link real

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
