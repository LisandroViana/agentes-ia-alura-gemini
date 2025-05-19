
# 🤖 Sistema de Agentes de IA com Google Gemini - Imersão Alura

Este repositório apresenta um projeto prático desenvolvido durante a **Imersão em Inteligência Artificial com Google Gemini**, promovida pela [Alura](https://www.alura.com.br) em parceria com o Google. O objetivo foi explorar o uso de **modelos de linguagem (LLMs)** combinados com ferramentas como busca no Google e execução assíncrona, culminando na criação de **um sistema completo de geração de conteúdo automatizado por agentes de IA**.

## 📅 Estrutura do Projeto

O projeto foi construído em 5 aulas e implementado em Python utilizando o SDK oficial do Google para acesso ao Gemini. Durante a imersão, foram desenvolvidos **4 agentes especializados**, que atuam de forma sequencial para automatizar a criação de um post de Instagram baseado em tendências recentes de IA:

### 🔹 1. Agente Buscador de Notícias
Responsável por utilizar a ferramenta `google_search` para encontrar os lançamentos mais relevantes e recentes sobre um tópico indicado.

### 🔹 2. Agente Planejador de Conteúdo
Com base nas notícias recuperadas, estrutura um plano de postagens para redes sociais, identificando os pontos mais relevantes e o tema central.

### 🔹 3. Agente Redator Criativo
Gera um rascunho de post engajador para o Instagram, com linguagem acessível e uso de hashtags, adaptando-se ao público jovem da Alura.

### 🔹 4. Agente Revisor de Qualidade
Analisa o texto gerado, ajusta tom, clareza e concisão. Caso o conteúdo esteja adequado, aprova para publicação; caso contrário, sugere melhorias.

## 💡 Tecnologias e Ferramentas

- **Python 3.11+**
- **Google Gemini SDK (`google-genai`)**
- **Google ADK (`google-adk`)**
- **Colab** como ambiente de desenvolvimento
- **Ferramentas Integradas:**
  - `google_search` para busca em tempo real
  - `InMemorySessionService` para gestão de sessões dos agentes

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   cd seu-repositorio
   ```

2. Abra o notebook no [Google Colab](https://colab.research.google.com/)

3. Insira sua **Google API Key** usando:
   ```python
   from google.colab import userdata
   os.environ["GOOGLE_API_KEY"] = userdata.get('GOOGLE_API_KEY')
   ```

4. Execute o notebook célula por célula. Ao final, o sistema pedirá o tema desejado para criação do post.

## 📸 Exemplo de Execução

```text
🚀 Iniciando o Sistema de Criação de Posts para Instagram com 4 Agentes 🚀
❓ Por favor, digite o TÓPICO sobre o qual você quer criar o post de tendências: Agente IA
```

A seguir, serão exibidas as saídas de cada agente:
- Notícias relevantes (buscador)
- Plano de conteúdo (planejador)
- Rascunho de post (redator)
- Avaliação e revisão (revisor)

## 🎓 Aprendizados

Durante esta imersão, foi possível:

- Utilizar modelos de linguagem em pipelines multi-agente
- Integrar ferramentas externas (como Google Search) com agentes LLM
- Criar fluxos assíncronos com o `google-adk`
- Aplicar conceitos de engenharia de prompts e automação criativa

## 📁 Arquivo

> O notebook completo está disponível neste repositório:  
> 📄 `Imersão_IA_Alura_+_Google_Gemini_Aula_05_Agentes.ipynb`

## ✍️ Autor

**Lisandro Lee**  
Graduando em Ciência da Computação | Professor e entusiasta de IA e Ciência de Dados  
[LinkedIn](https://linkedin.com/in/seu-usuario) • [GitHub](https://github.com/seu-usuario)

## 📜 Licença

Este projeto foi desenvolvido para fins educacionais durante a Imersão Alura + Google Gemini.  
Sinta-se à vontade para reutilizar com os devidos créditos.
