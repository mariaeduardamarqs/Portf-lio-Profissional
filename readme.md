# Portfólio — Maria Eduarda Chub Marques

Site de portfólio pessoal de **Maria Eduarda**, Desenvolvedora de Sistemas (Full Stack / Backend / Mobile). O site apresenta quem eu sou, minha trajetória técnica, os projetos que desenvolvi e uma página de cadastro para quem tiver interesse em entrar em contato.

Construído com **HTML semântico**, **CSS** e **Bootstrap 5**, sem backend.

---

## 📑 Sumário

- [Páginas do site](#-páginas-do-site)
- [Projetos em destaque](#-projetos-em-destaque)
- [Tecnologias utilizadas](#-tecnologias-utilizadas)
- [Estrutura de arquivos](#-estrutura-de-arquivos)
- [Formulário de cadastro](#-formulário-de-cadastro)
- [Como executar](#-como-executar)
- [Autora](#-autora)

---

## 🧭 Páginas do site

| Página | Arquivo | Conteúdo |
|--------|---------|----------|
| **Home** | `bootstrap01.html` | Banner, apresentação ("Olá, sou Maria Eduarda — Desenvolvedora de Sistemas") e resumo do perfil profissional. |
| **Sobre mim** | `sobremim.html` | Foto, minha história na tecnologia e **como atuo**: boas práticas, código limpo e testável, comunicação transparente e facilidade de adaptação. |
| **Trajetória técnica** | `tragetória.html` | Linha do tempo (stepper) com três etapas: primeiro contato com a programação no ensino médio, curso de Desenvolvimento de Sistemas e experiência como Jovem Aprendiz. |
| **Projetos feitos** | `projetos-feitos.html` | Cards com imagem, descrição e link para o repositório de cada projeto. |
| **Cadastro** | `formularioMeu.html` | Formulário para interessados entrarem em contato. |
| **Resultado** | `resultadoForm.html` | Página que recebe os dados do formulário e confirma o cadastro. |

---

## 💻 Projetos em destaque

| Projeto | Descrição | Repositório |
|---------|-----------|-------------|
| **Jogo da Forca** | Jogo da forca jogado pelo terminal. O programa sorteia uma palavra relacionada à programação e o jogador tenta descobri-la chutando uma letra por vez. | [GitHub](https://github.com/mariaeduardamarqs/Jogo-da-Forca) |
| **Sistema Matemático** | Projeto modular em Node.js para operações aritméticas fundamentais e resolução de equações do 2º grau pela Fórmula de Bhaskara. | [GitHub](https://github.com/analizdefreitasvasques-del/sistema-matematico) |
| **Sistema de Gestão de Biblioteca** | Sistema CLI em Node.js para cadastro de leitores, livros físicos e e-books, com cálculo automático de multas por atraso na devolução. | [GitHub](https://github.com/mariaeduardamarqs/Biblioteca-Municipal) |
| **Sistema de Cadastro e Busca** | Aplicação de terminal para matricular alunos, contratar professores e buscar cadastros pelo CPF, com dados armazenados em memória durante a execução. | [GitHub](https://github.com/mariaeduardamarqs/Sistema-de-cadastro-e-busca) |
| **Sistema de Gestão MVC** | Núcleo back-end de um sistema corporativo via linha de comando para controle de equipamentos de TI e técnicos de suporte, aplicando regras de negócio e validações com o padrão MVC (Model-View-Controller). | [GitHub](https://github.com/analizdefreitasvasques-del/Arquitetura-MVC) |

---

## 🛠️ Tecnologias utilizadas

- **HTML5** — estrutura semântica (`nav`, `header`, `main`, `section`, `footer`, `form`)
- **CSS3** — estilos próprios em `estilo.css` e `estiloMim.css` (layout com Flexbox e CSS Grid, stepper com contadores CSS, cards responsivos)
- **Bootstrap 5.3.8** — carregado via CDN (navbar, navegação, cards e componentes de formulário)
- **JavaScript** — usado apenas na página de resultado, para ler os dados enviados pelo formulário na URL (`URLSearchParams`)

---

## 📁 Estrutura de arquivos

```
portfolio/
├── bootstrap01.html          # Home
├── sobremim.html             # Sobre mim
├── tragetória.html           # Trajetória técnica
├── projetos-feitos.html      # Projetos feitos
├── formularioMeu.html        # Formulário de cadastro
├── resultadoForm.html        # Página de resultado do cadastro
├── estilo.css                # Estilos da home e do formulário
├── estiloMim.css             # Estilos das demais páginas
├── eu.png                    # Foto/logo
└── (imagens dos projetos e do banner)
```

---

## 📝 Formulário de cadastro

A página de cadastro reúne os campos:

- E-mail
- Data de nascimento
- Telefone
- Senha
- Mensagem
- Aceite dos termos e condições (obrigatório)

Ao enviar, o formulário (método `GET`) redireciona para `resultadoForm.html`, que:

- exibe **"Cadastro Feito e Recebido"** com uma mensagem de boas-vindas quando recebe dados;
- exibe **"Cadastro não recebido"**, com um aviso e o link para voltar ao formulário, quando nenhum dado chega.

---

## 🚀 Como executar

Não é necessário instalar nada.

1. Clone o repositório:
   ```bash
   git clone https://github.com/mariaeduardamarqs/NOME-DO-REPOSITORIO.git
   ```
2. Entre na pasta do projeto:
   ```bash
   cd NOME-DO-REPOSITORIO
   ```
3. Abra o `bootstrap01.html` no navegador (ou use a extensão *Live Server* do VS Code).

> É preciso estar conectado à internet para carregar o Bootstrap via CDN.

---

## 👩‍💻 Autora

**Maria Eduarda Chub Marques**
Desenvolvedora de Sistemas — SENAI Antonio Noschese (Santos)

- 🐙 GitHub: [mariaeduardamarqs](https://github.com/mariaeduardamarqs)
- 🏫 [SENAI Santos](https://www.sp.senai.br/unidade/santos/)

---

© 2026 Maria Eduarda Chub Marques. Todos os direitos reservados. Reprodução ou distribuição sem autorização prévia é proibida.
