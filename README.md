# Organizador de Arquivos por Extensão

Este script organiza arquivos em uma pasta selecionada, movendo-os para subpastas específicas com base em suas extensões. É uma solução prática para manter diretórios organizados de maneira automática.

## Funcionalidades

- Permite ao usuário selecionar uma pasta usando uma interface gráfica (via `tkinter`).
- Identifica os arquivos presentes na pasta selecionada.
- Organiza os arquivos em subpastas com base em extensões predefinidas:
  - **imagens**: `.png`, `.jpg`
  - **planilhas**: `.xlsx`
  - **pdfs**: `.pdf`
  - **csv**: `.csv`
- Cria automaticamente as subpastas, se ainda não existirem.
- Move os arquivos para as subpastas apropriadas.

## Pré-requisitos

- Python 3.6 ou superior.
- Bibliotecas padrão do Python (não é necessário instalar pacotes externos).

## Como usar

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/organizador-arquivos.git
