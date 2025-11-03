# Projeto Landing Page

**Visualização da página:** [Landing Page](https://willyamandrade.github.io/LandingPage-WEB1-S4/index.html)

**Equipe:** Willyam Andrade Medeiros

```
Desenvolvimento Web I
Instituto Federal do Ceará - Campus Maranguape
Curso Técnico Integrado em Informática - prof. Thomaz Maia
```

## 1. Objetivo do Projeto

Criar uma landing page para promover um servidor do IFCE campus Maranguape, aplicando todos
os conceitos de HTML e CSS aprendidos até o momento.  
A atividade deve ser feita em dupla e cada dupla deve escolher um servidor como tema do site. O
servidor pode ser um professor, um técnico administrativo, um intérprete de libras, etc.  
Não pode haver repetição de servidor entre as duplas.

## 2. Requisitos Técnicos
### 2.1 Estrutura da página principal (index.html)

- Nome completo do servidor em destaque (h1)
- Foto do servidor (img)
- Uma pequena biografia (p)
- Um menu de navegação (nav) com links (a) para as outras páginas
- Uso de tags semânticas como header, section, article, aside e footer
- Link com botão para baixar o currículo do servidor
- Estilização com CSS: tipografia, cores, margens, paddings e posicionamentos relativos e absolutos. (obs: Não utilizar conceitos de Flexbox (display: flex) e nem de Grid Layout (display: grid))

### 2.2 Sub-páginas obrigatórias
- sobre.html - com informações sobre a pessoa, fotos, hobbys, etc.
- formacao.html - com as formações e experiências da pessoa (usando ul e ol)
- disciplinas.html - para o caso de professores criar uma tabela de horários
- contato.html - formulário com: nome (input text), e-mail (input email), assunto (select), mensagem (textarea) e botão de envio (submit)

### 2.3 Regras de Estilo (CSS)
- O CSS deve estar em arquivo externo (css/style.css)
- Devem ser usados:
    - Cores personalizadas (fundo, texto, links, etc.)
    - Estilização de fontes (tamanho, cor, tipo)
    - Box model com padding, margin, border
    - Posicionamento usando position: relative e absolute onde necessário
    - Estilização de tabelas, listas, links e formulários
- Não é permitido usar Flexbox ou Grid Layout nesta atividade.

### 2.4 Estrutura de pastas

```
projeto/
        index.html
        html/   sobre.html
                formacao.html
                disciplinas.html
                contato.html
        css/style.css
        img/ (imagens utilizadas)
        docs/ (arquivo PDF do currículo da pessoa)
```