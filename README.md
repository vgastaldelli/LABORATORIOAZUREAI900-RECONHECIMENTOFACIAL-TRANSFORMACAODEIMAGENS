# MICROSOFT AZURE AL VISION STUDIO - UM NOVO OLHAR SOBRE AS IMAGENS

_O AL VISION STUDIO proporciona uma nova perspectiva para os recursos da inteligência artificial, principalmente no que tange o uso de imagens para detectação de faces, leitura de dados e rastreio de informações muito importantes que são por vezes imperceptíveis a olho nu_.

Utilizamos como base as seguintes documentações abaixo:

[Detect Faces in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html)

[Read Text in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html)

[Analyze images in Vision Studio](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html)


1 - Primeiro criar um resource no Azure Al Services

![image](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-RECONHECIMENTOFACIAL-TRANSFORMACAODEIMAGENS/assets/160192109/76c71df7-ec32-4d07-8633-3b2fdc3eaaf6)

2 - Depois devemos conectar o nosso resource criado no Azure Al Services com Azure Vision Studio.

![vision connection](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-RECONHECIMENTOFACIAL-TRANSFORMACAODEIMAGENS/assets/160192109/ed3c4c68-c09b-48ca-a648-bf05ecdaec2d)

3 - Para podermos utilizar os recursos, devemos primeiro marcar a seguinte box:"I acknowledge that this demo will incur usage to resource "seu domínio" in my Azure account":

![box marcação](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-RECONHECIMENTOFACIAL-TRANSFORMACAODEIMAGENS/assets/160192109/3f00f963-3448-4eae-bdf6-aac004b31b5b)

# Etapa "Detect faces in an image"

4 - Primeiro, foi selecionado três imagens de celebridades reconhecidas: Fernanda Montenegro, atriz brasileira; Jimmy Fallon, aprensentador de televisão norte-americano;
Paola Carosella, chefe de cozinha argentina-brasileira.

Segue exemplo abaixo de Paola Carosella, chefe de cozinha argentina-brasileira:

![Face Detection Result - Paola Carosella](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-RECONHECIMENTOFACIAL-TRANSFORMACAODEIMAGENS/assets/160192109/21f4001e-eaa3-4085-bd63-795e3aaa01f1)

As imagens originais das celebridades, se encontram armazenadas na pasta INPUT do repositório e os resultados na pasta OUTPUT do repositório, com o seguinte nome: "Face Detection Result - nome da celebridade".

# Etapa "Extract text from images"

5 - Nesta etapa também foi selecionado três imagens: anotações em um caderno; capa de um livro de fotografia; e a capa de um DVD.

Segue exemplo abaixo de capa de um DVD:

![Extract Text Result - Capa de um DVD](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-RECONHECIMENTOFACIAL-TRANSFORMACAODEIMAGENS/assets/160192109/1feb5af2-8915-4a5c-b1fd-607aa2c89536)

As imagens originais se encontram armazenadas na pasta INPUT do repositório e os resultados na pasta OUTPUT do repositório, com o seguinte nome: "Extract Text Result - nome da imagem".

_Observação: o interessante desse recurso do Al Vision Studio, é que pode ser utilizado para extrair informações de grandes documentações antigas de arquivos de bibliotecas universitárias e museus, proporcionando uma maior preservação de fatos históricos e a garantia do direito a memória de gerações futuras_.

# Etapa "Add captions to images"

6 - Nesta etapa também fora selecionado três imagens: cachorro pequeno; viagem de trem; e reunião de amigos.

Segue exemplo abaixo de cachorro pequeno: 

![Image Captioning Result - Cachorro pequeno](https://github.com/vgastaldelli/LABORATORIOAZUREAI900-RECONHECIMENTOFACIAL-TRANSFORMACAODEIMAGENS/assets/160192109/12ebdf23-17e2-47c8-935b-e0d176ef186f)

As imagens originais se encontram armazenadas na pasta INPUT do repositório e os resultados na pasta OUTPUT do repositório, com o seguinte nome: "Image Captioning Result - nome da imagem".

_Observação: pensando no âmbito da inclusão escolar, professores podem utilizar essa ferramenta do Al Vision Studio, para elaboração de materiais para estudantes com deficiência visual, visando adaptação dos conteúdos em sala de aula e elaboração aprimorada
dos planos de ensino-aprendizagem_.
