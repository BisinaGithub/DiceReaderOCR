🎲 DiceReaderOCR
DiceReaderOCR é um software de reconhecimento de imagem focado na identificação de valores em dados de RPG. Utilizando técnicas de visão computacional e OCR (Reconhecimento Óptico de Caracteres), ele analisa imagens de dados e retorna o número visível na face superior.

📌 Funcionalidades
✅ Reconhecimento de dados de RPG (ex: d4, d6, d8, d10, d12, d20)
✅ Processamento de imagem para segmentação e análise
✅ Uso de OCR para interpretar os valores dos dados
✅ Suporte a diferentes tipos de iluminação e ângulos
🚀 Tecnologias Utilizadas
OpenCV
Tesseract OCR
Python
📂 Estrutura do Projeto
projeto-tcc/
│── data/ # Conjunto de imagens dos dados
│ ├── raw/ # Imagens brutas coletadas
│ ├── processed/ # Imagens processadas e prontas para análise
│── docs/ # Documentação do projeto
│── models/ # Modelos treinados para reconhecimento
│── src/ # Código-fonte principal
│── tests/ # Testes do sistema
│── README.md # Este arquivo

📌 Como Usar
1️⃣ Clone o repositório:
git clone https://github.com/BisinaGithub/DiceReaderOCR.git
cd DiceReaderOCR

2️⃣ Instale as dependências:
pip install -r requirements.txt

3️⃣ Execute o reconhecimento de imagem:
python src/main.py --input data/raw/dice_image.jpg

🛠 Em Desenvolvimento
Este projeto ainda está em fase inicial e novas funcionalidades serão adicionadas em breve, este arquivo também será atualizado conforme a necessidade de alterações!