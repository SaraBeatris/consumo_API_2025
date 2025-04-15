💻 Projeto: Consumo de APIs com Python
🧩 Descrição
Este projeto tem como objetivo consumir diferentes APIs utilizando Python e a biblioteca requests. Ele implementa o padrão de projeto Strategy, o que permite adicionar novos consumidores de API de forma modular, sem modificar o código principal.

🔄 Fluxo de Execução
O programa utiliza diferentes classes para consumir APIs:

API Pokémon → Obtém informações sobre Pokémons.

API Rick and Morty → Retorna dados dos personagens da animação.

Star Wars API → Retorna dados sobre personagens do universo Star Wars.

API Ice and Fire → Obtém informações sobre personagens de As Crônicas de Gelo e Fogo.

🗂️ Estrutura do Projeto
bash
Copiar
Editar
consumo_API_2025/
├── api.py           # Implementação das classes de consumo de API
├── main.py          # Script principal para execução
├── README.md        # Documentação do projeto
├── requirements.txt # Dependências do projeto
📈 Instalação (Windows)
Como estou utilizando uma máquina virtual, aqui estão os passos que segui:

bash
Copiar
Editar
# Clonar o repositório
git clone https://github.com/SaraBeatris/consumo_API_2025.git
cd consumo_API_2025

# Criar e ativar ambiente virtual
python -m venv venv
venv\Scripts\activate

# Instalar dependências
pip install -r requirements.txt

# Executar o script principal
python main.py
🚀 Em Desenvolvimento
Este projeto será constantemente atualizado ao longo da disciplina, com novos commits para:

Aprimorar a arquitetura do código;

Adicionar novas APIs;

Consolidar o aprendizado prático em consumo de APIs com Python.
