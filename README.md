![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenCV](https://img.shields.io/badge/opencv-%23white.svg?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
# FotoMedida

## 1. Sobre o projeto
Sistema de metrificação fotográfica para controle de escalas. Registra quantas fotos foram recebidas por fotógrafo, quantas foram selecionadas e quantas foram descartadas, gerando um percentual de aprovação.

## 2. Estrutura do projeto
- `fotometria.py`: menu principal.
- `contar-raw.py`: contagem de entrada.
- `raw-apagadas.py`: contagem de saída e subtração.
- `arquivos-fotos.py`: criação de pastas.
- `interface/`: cores do terminal.
- `logs/`: TXTs e JSON gerados.

## 3. Fluxo de uso
1. Criar pasta.
2. Mover fotos do cartão.
3. Rodar `contar-raw.py`.
4. Selecionar fotos.
5. Rodar `raw-apagadas.py`.

## 4. Requisitos
- Python 3.x
- Windows
- Extensões suportadas: `.cr2`, `.cr3`, `.arw`, `.jpeg`, `.jpg`

## 5. Status do projeto
Em fase de testes — aguardando validação em escala real. Bugs conhecidos e melhorias futuras serão registrados após os testes.
