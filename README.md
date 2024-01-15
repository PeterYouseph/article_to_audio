# Conversor de arquivos em _.pdf_ para audio _.mp3_ em Python

## Descrição do projeto

Este projeto foi desenvolvido visando a maior facilidade de acesso a conteúdos em _.pdf_ para pessoas com deficiência visual, ou que simplesmente não possuem tempo para ler um ou vários arquivos _.pdf_ (assim como eu 😅).


## Como funciona?

O programa utiliza a biblioteca _PyPDF2_ para ler o arquivo _.pdf_ e a biblioteca _gTTS_ para converter o texto em audio. O programa lê o arquivo _.pdf_ e converte o texto em audio, gerando um arquivo _.mp3_ com o nome do arquivo _.pdf_. Utilizando-se também do _pydub_ para converter o arquivo _.mp3_ em mono, e o _pyttsx3_ para reproduzir o arquivo _.mp3_.


### Pré-requisitos e como rodar a aplicação

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Python](https://www.python.org/downloads/).

Além disto é bom ter um editor para trabalhar com o código como [VSCode](https://code.visualstudio.com/)

Ou importá-lo para o Google Colab e rodar o código lá.

### Bibliotecas utilizadas

* [PyPDF2](https://pypi.org/project/PyPDF2/)
* [gTTS](https://pypi.org/project/gTTS/)
* [pydub](https://pypi.org/project/pydub/)
* [pyttsx3](https://pypi.org/project/pyttsx3/)
* [SpeechRecognition](https://pypi.org/project/SpeechRecognition/)
* [os](https://docs.python.org/3/library/os.html)
* [tkinter](https://docs.python.org/3/library/tkinter.html)

### Instalando as bibliotecas na sua máquina
```python
%pip install gTTS
%pip install PyPDF2
%pip install pydub
%pip install pyttsx3
%pip install SpeechRecognition
%pip install tkinter
```
### Instalando as bibliotecas no Google Colab
```python
!pip install gTTS
!pip install PyPDF2
!pip install pydub
!pip install pyttsx3
!pip install SpeechRecognition
!pip install tkinter
```

### Como utilizar

1. Coloque o arquivo _.pdf_ na pasta _pdfs_ em seu diretório de trabalho
2. Execute o arquivo _main.py_ em seu terminal:

```bash
python main.py
```
3. O programa irá perguntar se o arquivo .pdf está em português ou inglês, digite _pt_ para português e _en_ para inglês

4. O programa irá perguntar se você deseja ouvir o arquivo _.mp3_ gerado, digite _s_ para sim e _n_ para não

5. O programa irá perguntar se você deseja excluir o arquivo _.mp3_ gerado, digite _s_ para sim e _n_ para não

6. O programa irá perguntar se você deseja converter outro arquivo _.pdf_, digite _s_ para sim e _n_ para não

7. O programa irá perguntar se você deseja sair do programa, digite _s_ para sim e _n_ para não



### Autor 
---
<a href="José Pedro Cândido"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/61319056?v=4" width="100px;" alt=""/><br />


Feito com ❤️ por José Pedro Cândido 👋🏽 Entre em contato!

[![Linkedin Badge](https://img.shields.io/badge/-José-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/josé-pedro-cândido-aa1b3b1b2/)](https://www.linkedin.com/in/joselp/)