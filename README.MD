# Projeto Criando um podcast com IAs


 > ℹ️ **NOTE:** Repositório criado durante o Bootcamp "CAIXA - IA Generativa com Microsoft Copilot", curso que realizei na plataforma [DIO](https://dio.me)

Objetivo: Gerar um Podcast utilizando ferramentas de IA.

## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [Craiyon](https://www.craiyon.com/)
- [ElevenLabs](https://beta.elevenlabs.io/)
- [Capcut](https://www.capcut.com/pt-br/)

## ✨ Como foi feito ?

- Roteiro gerado via chatgpt
- Audio gerado pela elevenLabs
- Craiyon para gerar capa
- Capcut para tratar aúdio e adicionar sons de fundo

## 🛠️ Modo de execução

Utilizei os prompts para criar um podcast de maneira automatizada, conforme passo a passo abaixo:

- 🤖 1. Gerei o roteiro e o título do Podcast no `chagpt`
- 🤖 2. Usei os prompts de roteiro gerados pelo chatgpt para transformar texto em áudio no `ElevenLabs`
- 🤖 3. No `Capcut` usei o áudio gerado no `ElevenLabs` e uma música de fundo disponível no próprio Capcut para editar o podcast
- 🤖 4. Fiz um prompt para gerar a capa em português e usei o ChatGPT para traduzir para o inglês 
- 🤖 5. Usei o prompt em inglês gerado pelo CHatGPT para obter a capa no `Craiyon`

## 🧠 Prompts

ChatGPT：

|   Ação   | Prompt                                                                                                                                                                                                                                                                         |
| :------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Conteúdo | Como roteirista de podcast, crie um roteiro para um podcast sobre "Prevenção à Lavagem de Dinheiro", focado nos principais conceitos e notícias da grande mídia, chamado "Ponto de Alerta - Prevenção à Lavagem de Dinheiro em 2 minutos". O podcast será utilizado por um assistente sênior chamado João como ferramenta para treinar sua equipe. Adote o formato: [INTRODUÇÃO] [conceito básico] [notícia] [FINALIZAÇÃO] {REGRAS} - no bloco [INTRODUÇÃO] faça uma saudação e um convite cordial ao episódio de forma sucinta, mas cordial - no bloco [conceito básico] substitua por um conceito básico sobre prevenção à lavagem de dinheiro - no bloco [notícia] substitua pelo resumo de uma notícia recente sobre lavagem de dinheiro no Brasil - no bloco [FINALIZAÇÃO] substitua por uma despedida terminando com 'Assim terminamos o episódio de hoje. Até o próximo!' - somente João apresentará os episódios - os episódios devem ser didáticos e com duração de aproximadamente 2 minutos {REGRAS NEGATIVAS} - Não use muitos termos técnicos  |
| Título  | Você é um assistente sênior e deve treinar sua equipe sobre o tema "Prevenção à Lavagem de Dinheiro" por meio de um podcast. O podcast abordará aspectos conceituais básicos e acontecimentos recentes relacionados ao tema veiculados na grande mídia brasileira. Os episódios serão curtos, com duração aproximada de 2 minutos. Liste 5 alternativas de nomes e subtítulos para o podcast. {REGRAS} O nome deve remeter à ideia de algo rápido, mas relevante  |   
| Tradução do prompt para uso no Craiyon  | Traduza para o inglês e otimize o texto do prompt a seguir, que será usado como descrição de imagem a ser criada por IA: "Imagem realista de um podcaster que é assistente sênior, trabalhando de seu home office, sorrindo e lendo o roteiro." |


Craiyon：

|  Ação  | Prompt                                                                                 |
| :----: | -------------------------------------------------------------------------------------- |
| Imagem de fundo da capa | "Realistic image of a senior assistant podcaster working from their home office, smiling while reading the script." |


## 👨‍💻 Expert

<p>
    <p>&nbsp&nbsp&nbspIngrid Braga<br>
       &nbsp&nbsp&nbsp
       <a href="https://github.com/eu-ingrid"> GitHub</a>
    </p>
</p>
