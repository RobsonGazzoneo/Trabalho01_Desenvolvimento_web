# 🚀 1° Trabalho Desenvolvimento Web: Curso Básico de HTML e CSS

Olá! Seja bem-vindo(a) ao repositório do projeto **Curso Básico de HTML e CSS**, desenvolvido como parte da disciplina de Análise e Desenvolvimento de Sistemas (ADS).

Este projeto representa a **evolução** do meu trabalho inicial no 1º semestre, com foco em demonstrar a importância de um código bem estruturado e a aplicação de 
técnicas de CSS puro para garantir fluidez e responsividade.

## 🎯 O Desafio: Do Esqueleto à Pele Fluida

O objetivo inicial era criar uma página de *landing page* simples usando apenas HTML e CSS. O desafio desta revisão foi transformar a versão inicial, que estava 
"funcional, mas não apresentável", em uma página profissional, respeitando a limitação de usar **somente HTML e CSS puro** (sem frameworks como Bootstrap).

### 🛠️ Tecnologias Utilizadas

| Tecnologia | Função na Página | Analogia Descontraída |
| :---: | :---: | :---: |
| **HTML5** | Estrutura e Conteúdo | O **Esqueleto** do site. Ele define onde a cabeça (título), o corpo (seções) e os pés (rodapé) estarão. |
| **CSS3** | Estilização e Design | A **Roupa, a Maquiagem e o Fitness** do site. Ele garante as cores, as fontes e, o mais importante, a fluidez dos movimentos. |

## ✨ Destaques da Revitalização com CSS Puro

Para garantir que a página fosse "digna de apresentação" e completamente fluida, foram aplicadas técnicas avançadas de layout que dispensaram o uso de frameworks externos:

### 1. Responsividade e Fluidez (O Corpo Flexível)

* **Flexbox (`display: flex`):** Foi essencial para alinhar e distribuir itens de forma organizada (como os 4 itens de característica ou o formulário).
    * **Analogia:** Pense no Flexbox como um **personal trainer**. Ele garante que os elementos se estiquem e se encolham de maneira harmoniosa, preenchendo o espaço
    * disponível sem deformar.
* **Media Queries (`@media`):** Essencial para adaptar o design a diferentes telas (celulares, tablets, desktops).
    * **Analogia:** É o **óculos de grau** do seu site. Ele diz: "Se a tela for pequena (celular), diminua o tamanho da fonte e empilhe os elementos; se for grande,
    * deixe-os lado a lado."

### 2. Organização e Reutilização (A Limpeza da Casa)

* **Variáveis CSS (`:root`):** Padronizei cores e estilos em variáveis, como `--color-primary` e `--color-highlight`.
    * **Analogia:** São os **Rótulos** na sua despensa. Se você quiser mudar o "Açúcar" de azul para verde, basta trocar o rótulo uma vez, e todos os potes de "Açúcar"
    * na casa mudam automaticamente!
* **Centralização de Blocos:** Elementos complexos, como o formulário de inscrição, foram centralizados usando a combinação de `max-width` e `margin: auto`.
    * **Analogia:** É a técnica de **"dar um abraço"** no elemento. Você limita o tamanho dele (`max-width`) e diz para ele se abraçar no centro (`margin: auto`).

## ⚙️ Estrutura do Projeto

O projeto é dividido semanticamente em 7 seções principais, garantindo que o fluxo de informação seja claro para o usuário.

| Seção | Conteúdo Principal | Classe/Tag |
| :---: | :---: | :---: |
| 1 | Banner e Inscrição Principal | `<header>` / `.header-content` |
| 2 | Rotina do Curso (Itens em Grid) | `<section>` / `.course-routine-grid` |
| 3 | Quem Somos (Texto ao Lado da Imagem) | `<section>` / `.about-us-content` |
| 4 | Como Funciona (Vídeo 16:9 e Texto) | `<section>` / `.video-text-layout` |
| 5 | Relato e Testemunho de Aluno | `<section>` / `.testimonial-content` |
| 6 | Segunda Inscrição / Contato | `<section>` / `.section-darker-bg` |
| 7 | Informações Finais (Logo) | `<footer>` / `.section-footer` |

---

Este projeto demonstra que é possível criar layouts complexos e de alta qualidade usando apenas as ferramentas base da web, HTML e CSS, o que é fundamental para qualquer 
Analista e Desenvolvedor de Sistemas.
