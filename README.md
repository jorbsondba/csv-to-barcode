# CSV to Barcode Converter

![Python](https://img.shields.io/badge/Python-3.x-blue)

## 📌 Descrição
Este projeto permite converter dados de uma planilha CSV em códigos de barras. Ele gera imagens no formato PNG e exporta um novo arquivo CSV contendo os códigos de barras correspondentes.

## 🚀 Funcionalidades
- Leitura de um arquivo CSV
- Geração de códigos de barras para valores de uma coluna específica
- Armazenamento das imagens dos códigos de barras
- Exportação de um novo CSV com os caminhos das imagens

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Pandas
- Python-Barcode

## 📂 Estrutura do Projeto
```
📂 csv-to-barcode
│── 📂 codigos/              # Pasta onde os códigos de barras serão salvos
│── 📜 dados.csv             # Arquivo CSV de entrada
│── 📜 dados_codigos.csv     # Novo CSV gerado com os códigos de barras
│── 📜 python-barcode.py     # Script principal
│── 📜 README.md             # Documentação do projeto
```

## 📌 Instalação e Uso

### 1️⃣ Clonar o repositório
```sh
git clone https://github.com/seu-usuario/csv-to-barcode.git
cd csv-to-barcode
```

### 2️⃣ Instalar dependências
```sh
pip install pandas python-barcode
```

### 3️⃣ Executar o script
```sh
python python-barcode.py
```

### 4️⃣ Configuração (Opcional)
No código, altere a variável `coluna_para_codigo` para definir qual coluna do CSV deve ser convertida em código de barras.

## 📜 Exemplo de Uso
### 📥 Entrada (dados.csv)
| codigo_produto | nome_produto |
|---------------|-------------|
| 123456789     | Produto A   |
| 987654321     | Produto B   |

### 📤 Saída (dados_codigos.csv)
| codigo_produto | caminho_codigo_barras |
|---------------|----------------------|
| 123456789     | codigos/123456789.png |
| 987654321     | codigos/987654321.png |


---
💡 **Contribuições são bem-vindas!** Caso tenha sugestões ou melhorias, fique à vontade para abrir um PR ou Issue. 🚀

