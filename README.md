# REMOVEDOR DE FUNDO DE IMAGEM
🎈USE ESSE APP PARA REMOVER O FUNDO DAS SUAS FOTOS.

<img src="FOTO.png" align="center" width="500"> <br>

## DESCRIÇÃO:
Este aplicativo em Tkinter é um utilitário simples para remover o fundo de uma imagem selecionada pelo usuário e salvar a imagem resultante no mesmo diretório da imagem original. Ele consiste em uma interface gráfica que permite ao usuário selecionar uma imagem de seu sistema de arquivos e, em seguida, remove o fundo do mesma selecionada quando o usuário clica no botão "SALVAR".

## CARACTERISTICAS:
1. **Seleção de Imagem**: O usuário pode selecionar uma imagem clicando no botão "SELECIONAR". Isso abrirá uma caixa de diálogo para selecionar o arquivo de imagem desejado.

2. **Remoção de Fundo**: Após selecionar a imagem, o caminho do arquivo selecionado é exibido na interface. O botão "SALVAR" é ativado, permitindo ao usuário remover o fundo da imagem clicando neste botão.

3. **Salvar Imagem**: Quando o usuário clica no botão "SALVAR", o aplicativo remove o fundo da imagem selecionada e salva a nova imagem (sem fundo) no mesmo diretório da imagem original, com um sufixo "_SEM_FUNDO.png" adicionado ao nome do arquivo.

4. **Feedback ao Usuário**: Após a remoção do fundo e a salvamento da imagem, uma mensagem de sucesso é exibida ao usuário informando que o fundo foi removido e a imagem foi salva com sucesso.

5. **Interface Simples**: A interface é limpa e intuitiva, contendo apenas os elementos necessários para selecionar uma imagem e realizar a remoção do fundo.

## EXECUTANDO O PROJETO:
1. **Instalação das Dependências::**
   - Entre no diretório `CODIGO` e execute o comando:

   ```bash
   pip install -r requirements.txt
   ```

2. Para executar o arquivo Python, utilize o comando abaixo no terminal, dentro do diretório `./CODIGO`:

   ```
   python CODIGO.py
   ```
   
3. Isso abrirá uma janela do aplicativo "REMOVER FUNDO".
4. Clique no botão "SELECIONAR" para escolher a imagem da qual deseja remover o fundo.
5. Após selecionar a imagem, clique no botão "SALVAR" para iniciar o processo de remoção do fundo.
6. Aguarde até que o processo seja concluído. Quando terminar, uma mensagem de sucesso será exibida.
7. A imagem com o fundo removido será salva no mesmo diretório da imagem original, com o sufixo "_SEM_FUNDO.png" adicionado ao nome do arquivo.

## SOBRE O EXECUTAVEL:
### 1. EXECUTANDO:
- Este arquivo executável está disponível apenas para `Windows X64`. Para executá-lo, basta dar dois cliques. O executável é bastante útil caso o Python não esteja instalado. Trata-se da mesma aplicação do arquivo `CODIGO.py`. Se desejar, você pode recompilá-lo novamente; é para isso que forneci o arquivo `imagem.ico`.

### 2. GERANDO:
   **1. Instalação do [PyInstaller:](https://pyinstaller.org/en/stable/)**
   - Certifique-se de ter o PyInstaller instalado. Se não tiver, instale usando o comando abaixo:
   ```bash
   pip install pyinstaller
   ```

   **2. Gerando o Executável:**
   - Para gerar o executável, utilize o comando `pyinstaller` seguido de opções:
      - `--icon="imagem.ico"`: Especifica o ícone do executável.
      - `-w`: Especifica que o executável será do tipo "windowed", ou seja, sem exibir uma janela de console.
      - `-F`: Gera um único arquivo executável em vez de vários.
      - `CODIGO.py`: Substitua "CODIGO.py" pelo nome do seu arquivo Python principal.
   ```bash
   pyinstaller --icon="imagem.ico" -w -F CODIGO.py
   ```

## NÃO SABE?
- Entendemos que para manipular arquivos em muitas linguagens, é necessário possuir conhecimento nessas áreas. Para auxiliar nesse aprendizado, oferecemos cursos gratuitos disponíveis:
* [CURSO DE PYTHON](https://github.com/VILHALVA/CURSO-DE-PYTHON)
* [CURSO DE TKINTER](https://github.com/VILHALVA/CURSO-DE-TKINTER)
* [SAIBA MAIS SOBRE O "REMBR"](https://github.com/danielgatis/rembg)
* [CONFIRA MAIS CURSOS](https://github.com/VILHALVA?tab=repositories&q=+topic:CURSO)

## CREDITOS:
- [PROJETO CRIADO PELO VILHALVA](https://github.com/VILHALVA)




