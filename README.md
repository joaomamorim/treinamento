# Treinamento em Raspagem de Dados para Jornalistas

*Informação de instalação baseada no curso da FolhaSP*

## O que é necessário instalar?
### Python
     
*Atenção: existe Python 2 e Python 3, usamos a versão 3*

[Link de Instalação do Python3](https://www.python.org/downloads/release/python-363/)
##### Windows:

     No Windows dar download, habilitar o PATH e voilá

      Se você tiver um notebook, sem as atualizações do Service Pack ou se der erro de DLL, instale uma versão mais antiga, Python 3.4 é a que tem dado certo.
     
![Imagem de habilitar o PATH](/addtopath.jpg)

##### Linux

     Já existe, só que você chama como python3

##### MacOS 

      Tem o pkg para instalar no link acima

      Instalar também https://www.python.org/download/mac/tcltk/

      Pela versão do seu sistema baixar do site da ActiveState

      Dúvidas: https://panda.ime.usp.br/panda/static/data/python/macos.html



### IDLE: 

##### Windows:

    Já vem instalado junto com o Python 3 (IDLE Python)

##### MacOS:  
    Mudar o teclado EUA Internacional para EUA simples

##### Linux: 

    sudo apt-get install idle3

  

### Demais bibliotecas a serem utilizadas:

Na linha de comando (cmd) executar o comando abaixo (demora um pouco):

    pip install requests beautifulsoup4 spotipy pdfminer3k selenium twitter wbdata pandas matplotlib lxml tweepy uber-rides xlrd PyPDF2 
    
Ou
    
    pip install -r requirements.txt

Também

    Lembre que, se você usar MacOS e Linux, terá ao mesmo tempo Python2 e Python3. Então deverá instalar o pip3 e rodar o comando acima com pip3 install etc, etc.


### Jupyter Notebooks
    Uma opção muito utilizada são os notebooks Jupyter, acrescente o comando abaixo na linha de comando (cmd do Windows) ou terminal (Mac e Linux)
    pip install numpy ipython jupyter

    Após a instalação você pode usar o Python e suas bibliotecas no seu navegador preferido:
    jupyter notebook


### Baixar também:

    http://phantomjs.org/download.html (deixar acessível)

    Baixar Abraji.zip e raspa.zip (descompactar)




## FAQS

1- Onde ficará o material atualizado?

      - github.com/fmasanori/treinamento



2- Tem algum livro para estudar depois?

      - Web Scraping with Python



3- Este curso estará disponível online?

     - Se eu conseguir parar de viajar tanto, prometo gravar :-)



4- Como entrar em contato com Fernando Masanori?

    - about.me/fmasanori



5- Existem outros repositórios de jornalistas, com raspagens?

    Sim!
    - mtrpires: raspafamilia politistalker

    - rodrigoburg: copa2014 basometro congresso imoveis doacoes2014



6- Onde conseguir ajuda? 

     - PyLadies

     - Grupo Python Programadores (FB, Telegram e lista discuss?o)



7- Onde o Python fica no Windows?


     C:\Users\Fernando\AppData\Local\Programs\Python\Python36-32



## Descrição do conteúdo de raspa.zip

01-html

02-h1

03-trechos verdes

04-texto da div

05-filhos da tabela

06-tabela sem o cabeçalho

07-preço através do último td

08-imagens com ER

08a-baixar as imagens

09-tag com 2 atributos

10-links da wikipedia

11-filtrar links

12-percorrer os links

13-outra forma de fazer 12

14-outra forma

15-outra 

16-percorrer links a partir de uma url

17-wbdata (world bank api python)

world cup api+

18-yellow pages

19-spotipy (spotify api python)

20-twitter timeline

21-twitter hashtag

22-gravar csv, twitter ao redor da Folha

        (twitter python api geolocation)

23-megasena

24-json, pegar localização do IP

25-json

26-localização dos colaboradores wikipedia

27-gravar csv de uma tabela

28-utf-8 russo

29-ler CSV

30-ler PDF

31-ler WORD

32-Form nome e sobrenome

33-Cookie

34-outra forma Cookie

35-Tela Login

36-Ajax página muda, espera tempo

37-Ajax espera o botão aparecer

38-Ajax redirect

39-CAPTCHA

40-itinerários ônibus SJC

41-lxml enunciados concursos

42-Billboard 100

43-maior número de meninas

44-Evolução mencoes acervo folha

(networking Sergio, Fernanda)

for01-pizzarias próximas

geo01-Lat Long de um local

geo02-traça rotas

geo03-Local de uma Lat Long

poke01-Habilidade Battle Armor

poke02-Tipo Voadores 




