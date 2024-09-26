# T1-SistemasDistribuidos
Versão simplificado do googlemeet usando broker ZMQ como unidade centralizadora para troca de dados de texto, áudio e mensagem.

# Instruções de como executar o código:
    ## Primeiramente, baixe os arquivos (client.py e broker.py). Para rodar em duas máquinas ou mais, é necessário seguir os seguintes passos:
        - Baixar todas as dependências exigidas pelo código. Para instalar no linux basta digitar ("pip install zmq numpy opencv-python pyaudio") no terminal.
        - Escolher uma máquina para executar o broker. Lembrando que o broker é uma unidade centralizadora responsável por gerenciar o recebimento e o envio
    dos dados de texto, mensagem e vídeo.
        - No código do client e do broker é necessário inserir o ipv4 da máquina que roda o broker.
        - Feito isso, primeiro passo, portanto, é executar o broker.
        - Agora, basta executar o código do cliente para se comunicar com os computadores que se comunicam pelo tópico desejado.
    
