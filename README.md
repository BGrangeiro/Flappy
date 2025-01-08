# Flappy Bird Clone - Jogo em Python

Este projeto é um clone do famoso jogo Flappy Bird, desenvolvido em Python utilizando a biblioteca **Pygame**.

---

## Requisitos do Sistema

- Python 3.8 ou superior
- Biblioteca Pygame instalada

---

## Como Configurar o Jogo

### 1. Instalar o Python

Certifique-se de que o Python está instalado em sua máquina. Você pode baixá-lo e instalá-lo a partir do site oficial:
[https://www.python.org/](https://www.python.org/)

Verifique a instalação executando o seguinte comando no terminal:

```bash
python --version
```

ou, dependendo do sistema:

```bash
python3 --version
```

### 2. Instalar a Biblioteca Pygame

A biblioteca **Pygame** é necessária para rodar este jogo. Para instalá-la, execute o seguinte comando no terminal:

```bash
pip install pygame
```

Certifique-se de que a instalação foi bem-sucedida:

```bash
pip show pygame
```

---

## Configuração de Arquivos

1. **Imagens Necessárias:**

   - Certifique-se de que as seguintes imagens estão localizadas na pasta `imgs`:
     - `bird1.png`
     - `bird2.png`
     - `bird3.png`
     - `pipe.png`
     - `base.png`
     - `bg.png`

2. **Estrutura de Pastas:**

   - O diretório do projeto deve seguir esta estrutura:
     ```
     projeto/
     |-- main.py
     |-- imgs/
         |-- bird1.png
         |-- bird2.png
         |-- bird3.png
         |-- pipe.png
         |-- base.png
         |-- bg.png
     ```
   - Substitua `main.py` pelo nome do arquivo contendo o código principal do jogo.

3. **Configuração Adicional:**

   - Certifique-se de que o diretório atual (onde você executa o jogo) contém as pastas e arquivos mencionados acima.

---

## Como Executar o Jogo

1. No terminal, navegue até o diretório do projeto:
   ```bash
   cd /caminho/para/o/diretorio/do/projeto
   ```
2. Execute o arquivo principal do jogo:
   ```bash
   python main.py
   ```
   ou, dependendo da configuração:
   ```bash
   python3 main.py
   ```

---

## Controles

- **Espaço (SPACE):** Faz o pássaro pular.
- **Fechar (QUIT):** Fecha o jogo.

---

## Descrição do Jogo

O objetivo do jogo é controlar o pássaro para que ele passe pelos canos sem colidir. Quanto mais canos forem superados, maior será sua pontuação.

Se o pássaro colidir com um cano ou o chão, o jogo será encerrado e exibirá uma mensagem de "Game Over" com uma contagem regressiva.

---

## Solução de Problemas

1. \*\*Erro: \*\***`ModuleNotFoundError: No module named 'pygame'`**

   - Certifique-se de que o Pygame foi instalado corretamente utilizando o comando `pip install pygame`.

2. **Erro: Imagens não carregadas**

   - Verifique se a pasta `imgs` está no mesmo diretório que o arquivo principal do jogo.
   - Confirme se os nomes das imagens correspondem exatamente aos usados no código.

3. **O jogo não inicia**

   - Verifique a versão do Python e do Pygame.
   - Certifique-se de que o comando para executar o jogo está correto.

---

## Créditos

Este projeto foi criado como um exemplo de jogo simples para aprendizado de Python e Pygame. Sinta-se à vontade para modificar e expandir o código!

Canal do youtube: Tech With Tim\
Link: [https://tinyurl.com/flappyBHGC](https://tinyurl.com/flappyBHGC)

\
\
