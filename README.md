# Monitoramento e Alertas via Telegram

## Descrição do Projeto
Este projeto tem como objetivo monitorar arquivos de log em busca de padrões específicos e gerar alertas automáticos via Telegram sempre que determinadas condições são atendidas. O programa utiliza uma interface gráfica desenvolvida em Tkinter para exibir o status de diferentes pistas e permite a consulta das frases encontradas.

## Funcionalidades
- Monitoramento automático de arquivos de log de diversas pistas.
- Identifica e contabiliza ocorrências de frases específicas.
- Gera alertas no Telegram quando um padrão excede um limite predefinido.
- Interface gráfica interativa para visualizar e consultar os eventos registrados.
- Registra logs diários com as frases encontradas.

## Tecnologias Utilizadas
- **Python**: Linguagem principal do projeto.
- **Tkinter**: Para criação da interface gráfica.
- **Threading**: Para execução de tarefas em paralelo sem travar a interface.
- **Regex**: Para busca e extração de informações nos arquivos de log.
- **Requests**: Para envio de mensagens ao Telegram.
- **OS**: Para manipulação de arquivos e diretórios.
- **Datetime**: Para manipulação de datas e registros de logs.

## Configuração do Ambiente
### 1. Clonar o Repositório
```bash
Por conter dados sensíveis utilizados em produção, não estou disponibilizando o código fonte.

### 2. Criar e Ativar um Ambiente Virtual (opcional, mas recomendado)
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows
```

### 3. Instalar as Dependências
```bash
pip install -r requirements.txt
```

### 4. Configurar o Token do Telegram
Crie um arquivo `.env` na raiz do projeto e adicione:
```env
TELEGRAM_BOT_TOKEN=SEU_TOKEN_AQUI
TELEGRAM_CHAT_ID=SEU_CHAT_ID_AQUI
```

## Como Executar o Projeto
```bash
python main.py
```

## Estrutura do Projeto
```
.
├── main.py                 # Arquivo principal do programa
├── monitoramento.py        # Módulo responsável pela leitura de logs e envio de alertas
├── interface.py            # Módulo da interface gráfica em Tkinter
├── logs/                   # Diretório onde são salvos os logs diários
├── requirements.txt        # Lista de dependências do projeto
├── README.md               # Documentação do projeto
└── .env                    # Arquivo de configuração (não deve ser versionado)
```

## Prints da Interface
(Adicione imagens para ilustrar a interface do sistema)





 
