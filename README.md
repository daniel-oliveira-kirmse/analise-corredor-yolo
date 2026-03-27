# 🏃‍♂️ Monitoramento Inteligente de Corredores (YOLOv8 Pose + Flask)

Este projeto é uma aplicação Web profissional desenvolvida para monitorar a movimentação em corredores institucionais. Utiliza IA para rastreio em tempo real, análise biomecânica e geração automática de evidências em vídeo e relatórios.

## ✨ Novas Funcionalidades (v2.0)
- **Processamento de Vídeo On-Demand**: Upload de arquivos via navegador com feedback visual de processamento.
- **Preview & Download**: Visualização instantânea da análise e botão para baixar o vídeo processado com logs aplicados.
- **Relatórios em Tempo Real**: Lista de detecções lateral que se atualiza dinamicamente.
- **Exportação Excel**: Histórico completo salvo em `.xlsx` com data, hora, ID e veredito.

## 🛠️ Tecnologias Utilizadas
- **Backend**: Python 3.13, Flask (Servidor Web)
- **Visão Computacional**: YOLOv8 (Ultralytics), OpenCV (H.264 Codec)
- **Frontend**: HTML5, CSS3, JavaScript (DOM Manipulation)
- **Dados**: Openpyxl, Numpy

## 🚀 Como Executar
1. Clone o repositório.
2. Crie um ambiente virtual: `python -m venv env`.
3. Ative o ambiente e instale as dependências:
   `pip install flask ultralytics opencv-python openpyxl`
4. Execute o servidor: `python app.py`
5. Acesse no navegador: `http://127.0.0.1:5000`

## 📊 Estrutura do Projeto
- `app.py`: Cérebro da aplicação e rotas Flask.
- `templates/`: Interface HTML.
- `static/`: Estilos CSS, logos institucionais e vídeos processados.
- `uploads/`: Armazenamento temporário de vídeos enviados.

---
**Desenvolvido por Daniel Oliveira Kirmse**