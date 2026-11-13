# 💻 Portfólio Profissional
# 👦🏽 Thiago Mendes

## 📌 Descrição do projeto
Este projeto consiste em um portfólio profissional desenvolvido para apresentar minhas informações pessoais, conhecimentos em tecnologia e projetos realizados durante meus estudos na área de Desenvolvimento de Sistemas.

O site possui um design responsivo, organizado em seções, com o objetivo de facilitar a navegação e proporcionar uma experiência agradável ao usuário.

## 🛠️ Tecnologias utilizadas
- **HTML5:** estrutura do conteúdo do site.
- **CSS:** personalização visual e animações.
- **Bootstrap:** layout responsivo, cartões, botões e carrossel.
- **Devicon:** ícones das tecnologias e ferramentas.

## 🌐 Link do site publicado
🔗 **Acesse o portfólio:** [https://mbdsthiago.github.io/portfolio](https://mbdsthiago.github.io/portfolio/)

## ⚙️ Funcionamento do projeto
O portfólio é dividido nas seguintes partes:

- **Menu de navegação:** permite acessar as seções Perfil, Projetos e Contato.
- **Carrossel:** apresenta imagens que alternam automaticamente, com transição suave e degradê azul.
- **Perfil profissional:** apresenta informações sobre formação, interesses e objetivos.
- **Tecnologias e ferramentas:** exibe as tecnologias e ferramentas estudadas.
- **Projetos:** mostra cartões com imagens, descrições e botões para acessar os projetos.
- **Contato:** apresenta opções de comunicação por e-mail, GitHub.

## ✨ Recursos novos adicionados

### 1. Elevação dos cartões
Foi adicionado um efeito que faz os cartões subirem levemente quando o usuário passa o cursor do mouse sobre eles. Isso destaca os cartões e torna a página mais interativa.

**Como foi implementado:**

O efeito utiliza CSS com `transition`, `transform` e `box-shadow`. A pseudoclasse `:hover` identifica quando o cursor está sobre o cartão. A propriedade `transform: translateY(-5px)` desloca o cartão para cima, enquanto `box-shadow` reforça sua sombra. A propriedade `transition` suaviza a animação.

### 2. Animação nos links do menu
Foi adicionada uma linha animada abaixo dos links do menu quando o usuário passa o cursor sobre eles, destacando a opção apontada.

**Como foi implementado:**

O efeito utiliza CSS com a pseudoclasse `:hover` e o pseudoelemento `::after`. O `::after` cria uma linha que começa com largura zero. Ao passar o cursor sobre o link, sua largura aumenta para `100%`. A propriedade `transition` faz essa mudança acontecer suavemente.
