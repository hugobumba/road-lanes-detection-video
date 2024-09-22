# Detecção de Linhas de Pista em Vídeo

Este projeto utiliza a técnica de Hough Transform para detectar linhas em um vídeo de pistas. O código é baseado na biblioteca OpenCV e realiza processamento em tempo real.

## Requisitos

- Python 3.8.0
- OpenCV
- NumPy

## Instalação

Para instalar as dependências, execute:

```bash
pip install opencv-python numpy
```

## Uso

1. Coloque o vídeo no mesmo diretório do script.
2. Execute o script:

```bash
python lane_detection.py
```

3. O programa abrirá uma janela exibindo o vídeo com as linhas da pista detectadas.

## Funcionamento

- O código lê o vídeo e processa cada frame.
- Aplica-se a detecção de bordas e a transformação de Hough para detectar linhas.
- As linhas detectadas são desenhadas no vídeo e exibidas em tempo real.