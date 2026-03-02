# Portaria - Sistema de Controle de Acesso

O **Portaria** é uma solução desktop, desenvolvida em Python com a biblioteca PySide6, destinada ao controle em portarias, de uma empresa de ônibus.

## 🚀 Funcionalidades

O sistema foi projetado para oferecer eficiência nos relatórios de controle utilizado pela portaria, digitalizando os processos manuais:

### 1. Controle de Acesso de Pessoas
- **Colaboradores:** Registro de entrada e saída de funcionários com monitoramento de horários.
- **Visitantes:** Cadastro e monitoramento de visitantes, vinculando-os ao colaborador visitado.
- **Terceiros:** Gestão de prestadores de serviço e office-boys.

### 2. Gestão de Veículos e Materiais
- **Entrada/Saída de Veículos:** Registro detalhado de veículos, incluindo prefixo, motorista e horários.
- **Controle de Materiais:** Registro de materiais utilizados.
- **Manutenção:** Registro de serviços de manutenção realizados (lavagem, elétrica, mecânica, etc.).

### 3. Gestão de Chaves
- **Empréstimo e Devolução:** Sistema para controle de uso das chaves, registrando quem retirou, qual chave e o horário de devolucão.

### 4. interface Administrativa
- **Segurança:** controle de acesso via login para garantir a responsabilização.
- ** persistência de Dados:** back-end robusto utilizando SQLite e SQLAlchemy para armazenamento confiável.

## 🛠 Tecnologias Utilizadas

- **Linguagem:** [Python](https://www.python.org/)
- **Interface Gráfica:** [PySide6 (Qt for Python)](https://doc.qt.io in/qtforpython/)
- **Banco de Dados:** [SQLite](https://www.sqlite.org/)
- **ORM:** [SQLAlchemy](https://www.sqlalchemy.org/)

## 📦 Estrutura do Projeto

- `main.py`: Ponto de entrada da aplicação.
- `index.py`: Lógica principal e gerenciamento de eventos da interface.
- `core/`: Contém models e managers para acesso ao banco de dados.
- `icons/`: Recursos visuais utilizados na interface.

## ⚙️ Como Executar

### Pré-requisitos
Certifique-se de ter o Python 3.x instalado em sua máquina.

1. Clone o repositório:
   ```bash
   git link https://github.com/Luiz-ROCampos/Portaria.git
   cd Portaria
   ```

2. Crie um ambiente virtual e ative-o:
   ```bash
   python -m venv venv
   # No Windows:
   venv\Scripts\activate
   # No Linux/macOS:
   source venv/bin/activate
   ```

3. Instale as dependências:
   ```bash
   pip install PySide6 SQLAlchemy
 chron
 the application:
   ```bash
   python main.py
   ```

## 🤝 Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar pull requests

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.
