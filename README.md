# Projeto ETL: Extração de Dados de API

## Descrição do Projeto
Este projeto implementa um pipeline ETL (Extract, Transform, Load) para extrair dados de uma API, realizar transformações necessárias e carregá-los em um sistema de destino, como um banco de dados ou arquivo estruturado.

O objetivo é criar um fluxo automatizado, escalável e confiável para gerenciar e processar dados oriundos de fontes externas.

---

## Estrutura do Projeto
- **`src/`**: Contém os scripts de extração, transformação e carregamento.
  - **`extract.py`**: Código responsável por se conectar à API e extrair os dados.
  - **`transform.py`**: Código que realiza a limpeza e transformação dos dados extraídos.
  - **`load.py`**: Código que carrega os dados transformados no destino final.
- **`config/`**: Configurações do projeto, como credenciais da API e variáveis de ambiente.
- **`logs/`**: Arquivos de log gerados pelo pipeline.
- **`tests/`**: Scripts para testes unitários das etapas do pipeline.
- **`README.md`**: Documentação do projeto.
- **`requirements.txt`**: Dependências do projeto.

---

## Pré-requisitos
- **Linguagem**: Python 3.8 ou superior.
- **Dependências**: Instale as bibliotecas listadas em `requirements.txt` com o comando:
  ```bash
  pip install -r requirements.txt

API_URL=https://api.exemplo.com
API_KEY=sua_chave_de_api