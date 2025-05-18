## Olá eu sou o Jansen na Imersão IA da ALURA 👋
### Agentes de IA trabalhando juntos para analisar arquivos ajudando a detectar fake news.

- 🔭 Atualmente estou trabalhando como professor de desenvolvimento de sistemas
- 🌱 Atualmente estou aprendendo na Imersão IA da ALURA e mestrando em Engenharia Computacional na UTFPR
- 👯 Estou procurando colaborar em 
- 🤔 Estou procurando ajuda com o Discord 🤣
- 📫 Como entrar em contato comigo no e-mail: jansen@alunos.utfpr.edu.br
- ⚡ Curiosidade: Gosto muito de automação e aeromodelismo.


---
### Para acessar basta clicar abaixo em Projeto e você será redirecionado para o seu Colab ja com o código.

# [Projeto](https://colab.research.google.com/drive/1dNbXe63AQq2LSsyn4lxanf8WhqCcVqT5#scrollTo=LVxQz_07kjWH)


---
## 💡 Projeto: Detetive de Fake News com Agentes de IA
### 🎯 Objetivo do Sistema:
#### Receber uma notícia, post ou afirmação e verificar sua veracidade com base em fontes confiáveis, análises linguísticas e evidências factuais, gerando um parecer com grau de confiabilidade.

## 👥 Equipe de Agentes e seus Papéis
### 1. Agente de Análise Linguística
 - Objetivo: Detectar padrões de linguagem típicos de fake news (sensacionalismo, uso de caixa alta, emoções exageradas).
 - Entrada: Texto da notícia.
 - Saída: Avaliação textual com indícios linguísticos de falsidade ou manipulação.

### 2. Agente de Checagem de Fontes
 - Objetivo: Buscar se a notícia já foi verificada por agências confiáveis (Aos Fatos, Lupa, Snopes, etc).
 - Entrada: Afirmação principal da notícia.
 - Saída: Links e resumos de verificações prévias.

### 3. Agente de Busca de Evidências
 - Objetivo: Fazer buscas em fontes confiáveis (notícias, artigos científicos, órgãos oficiais) sobre o conteúdo.
 - Entrada: Afirmação resumida da notícia.
 - Saída: Lista de fontes primárias que confirmam ou refutam o conteúdo.

### 4. Agente de Contextualização
 - Objetivo: Entender o contexto da notícia (data, local, situação política/social), e verificar se o conteúdo pode estar fora de contexto.
 - Entrada: Texto original + data e local da postagem.
 - Saída: Análise de descontextualização, anacronismo ou reaproveitamento de fatos antigos.

### 5. Agente de Classificação Final
 - Objetivo: Com base nas análises anteriores, classificar a notícia como:
 - Verdadeira
 - Falsa
 - Imprecisa/Enganosa
 - Indeterminada
 - Entrada: Saídas dos agentes anteriores.
 - Saída: Parecer com justificativa e grau de confiança.

### 6. Agente Redator
 - Objetivo: Gerar um relatório claro e objetivo para o usuário, com explicações acessíveis e links de referência.
 - Entrada: Parecer final + fontes.
 - Saída: Relatório ou resumo legível, pronto para publicação ou uso.
