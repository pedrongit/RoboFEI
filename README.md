# RoboFEI Stream Deck

Este repositório contém os arquivos necessários para construir um Stream Deck utilizando uma placa de circuito impresso, um Arduino Nano e um enclosure desenhado no Fusion360 para impressão 3D.

## Conteúdo

### Pastas

- **3D**: Contém arquivos de design 3D para imprimir o enclosure do Stream Deck.
- **Placa**: Inclui arquivos relacionados às placas de circuito do projeto.

### Arquivos

- **ArduinoSparkfun.lbr**: Biblioteca de componentes Sparkfun para uso no Arduino.
- **Curso Produção de PCBs RoboFei.pptx**: Apresentação em PowerPoint sobre como produzir PCBs e montar um Stream Deck utilizando uma placa de circuito impresso, um Arduino Nano e um enclosure impresso em 3D.
- **USBHost-master.zip**: Arquivo zip contendo código e/ou bibliotecas para suporte a USB Host.
- **README.md**: Este arquivo de documentação que você está lendo.

## Como usar

### Design 3D

Os arquivos na pasta `3D` podem ser usados para imprimir em 3D o enclosure do Stream Deck. Recomendamos usar o Autodesk Fusion 360 para editar ou visualizar os arquivos.

### Placas de Circuito

![image](https://github.com/user-attachments/assets/3d820bcc-6db4-48f9-8bb5-343a60590551)
![image](https://github.com/user-attachments/assets/fdf3e469-65fd-4061-9582-80ce9c2e8930)


Na pasta `Placa`, você encontrará esquemáticos e layouts para a criação da placa de circuito do Stream Deck. Esses arquivos podem ser abertos e editados com softwares como o Eagle ou KiCad.

### Bibliotecas de Arduino

O arquivo `ArduinoSparkfun.lbr` deve ser adicionado ao diretório de bibliotecas do Arduino. Para isso, siga os passos abaixo:

1. Abra o Arduino IDE.
2. Vá para `Sketch` > `Include Library` > `Add .ZIP Library`.
3. Selecione o arquivo `ArduinoSparkfun.lbr` e clique em `Open`.

### Material do Curso

O arquivo `Curso Produção de PCBs RoboFei.pptx` é uma apresentação que fornece instruções detalhadas sobre como produzir um Stream Deck. Pode ser aberto com o Microsoft PowerPoint ou qualquer software compatível com arquivos .pptx.

### Suporte USB Host

Descompacte o arquivo `USBHost-master.zip` para obter os arquivos necessários para implementar o suporte a USB Host no seu projeto. Siga as instruções fornecidas nos arquivos descompactados.

![image](https://github.com/user-attachments/assets/36910fb1-60e1-4699-bf29-1f71160a6cca)
![image](https://github.com/user-attachments/assets/44dec17f-a54c-49b8-a888-56bb7b17d354)
