# 🦙 llamaIndexAgents — Agentes Inteligentes com LlamaIndex

## 💡 Visão Geral

Este projeto foi desenvolvido como parte dos estudos do curso [Desenvolvimento de Agentes de IA: Do Zero ao Avançado](https://www.udemy.com/course/desenvolvimento-de-agentes-de-ia-do-zero-ao-avancado) na Udemy, ministrado por Rodrigo Macedo e Paulo Andrade, PhD.

O objetivo é explorar a criação de agentes inteligentes utilizando o **LlamaIndex**, uma poderosa ferramenta que permite conectar LLMs (Large Language Models) a dados estruturados, documentos e fontes externas. Com LlamaIndex, é possível transformar funções em ferramentas, criar mecanismos de busca personalizados e integrar agentes com dados reais.

---

## 🧠 Conceitos Aplicados

- **LlamaIndex**: Framework para conectar LLMs a dados e documentos.
- **LangChain**: Base para integração de ferramentas, memória e raciocínio.
- **Tools**: Funções transformadas em ferramentas acessíveis pelos agentes.
- **Embeddings**: Representações vetoriais de textos para busca semântica.
- **ReAct Agent**: Agente que raciocina e age com base em contexto e ferramentas.

---

## 🛠️ Tecnologias Utilizadas

- `Python`  
- `LlamaIndex`  
- `LangChain`  
- `OpenAI API`  
- `dotenv` para variáveis de ambiente  
- `Streamlit` (opcional para interface)  
- `YAML` para configuração de ferramentas e fluxos

---

## 🚀 Primeiros Passos

### ✅ Pré-requisitos
- Python 3.12+
- pip
- Chave de API (OpenAI ou outro provedor LLM)

### 📦 Instalação e Ambiente Virtual

```bash
python3.12 -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r .\requirements.txt
```

Configure o arquivo .env com sua chave de API:
```env
OPENAI_API_KEY=sk-xxxxxxxxxxxxxxxxxxxx
```

### ▶️ Executando o Projeto
```bash
python main.py
```
Ou, se houver interface web:
```bash
streamlit run app.py
```

## 📁 Estrutura do Projeto
```
llamaIndexAgents/
├── main.py               # Execução principal
├── tools/                # Ferramentas personalizadas
├── data/                 # Arquivos e documentos utilizados
├── .env                  # Chave de API
├── requirements.txt      # Dependências
└── README.md             # Documentação
```

##📚 Aprendizados
- Criação de ferramentas inteligentes com LlamaIndex
- Integração de agentes com dados reais e documentos
- Implementação de mecanismos de busca semântica
- Uso de embeddings e engines de consulta
- Construção de agentes ReAct com lógica contextual

## 🔮 Próximos Passos
- Adicionar múltiplos agentes com especializações distintas
- Criar dashboards com Streamlit para visualização dos resultados
- Testar diferentes provedores de LLMs e embeddings
- Integrar com CrewAI para coordenação multiagente

## 👩‍💻 Autora

Aline Assunção

Engenheira de Qualidade em transição para Inteligência Artificial

📫 [LinkedIn](https://www.linkedin.com/in/alineassuncaoai/)  

📬 aline.jassuncao@gmail.com

>_"Conectar inteligência artificial a dados reais é transformar informação em ação."_





















