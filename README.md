# Portfólio Profissional - Larissa da Silva Costa

## Título do Projeto
Portfólio Profissional e Acadêmico - Larissa da Silva Costa

## Nome do Aluno
Larissa da Silva Costa

## Descrição do Portfólio
Este portfólio pessoal foi desenvolvido como projeto integrador do curso técnico em Desenvolvimento de Sistemas. O site apresenta minha trajetória acadêmica, informações de perfil, habilidades técnicas, projetos práticos realizados ao longo da formação e canais de contato profissional.

## Tecnologias Utilizadas
- **HTML5:** Estruturação semântica da página.
- **CSS3:** Estilização customizada, animações de hover e transições suaves.
- **Bootstrap 5.3.3:** Framework CSS para criação de componentes responsivos.
- **Devicon:** Biblioteca de ícones vetoriais para tecnologias e ferramentas.
- **Git & GitHub / GitHub Pages:** Controle de versão e hospedagem online gratuita.

## Link do Site Publicado
[https://larissadetolinni.github.io/portfolio/](https://larissadetolinni.github.io/portfolio/)

## Explicação do Funcionamento do Projeto
O projeto está estruturado em uma página única (Single Page Application / Landing Page) com navegação fluida através de links âncora no menu superior:
1. **Menu de Navegação (Navbar):** Fixo no topo e responsivo.
2. **Hero Section (Destaque):** Mensagem de boas-vindas com botão direto para o perfil.
3. **Seção de Perfil:** Apresenta cartão com link direto para o GitHub (`larissadetolinni`), dados pessoais, formação e cards com tecnologias estudadas.
4. **Seção de Habilidades (Recurso Novo):** Exibe barras de progresso interativas e distintivos de competências técnicas.
5. **Seção de Projetos:** Exibe cards dinâmicos contendo os 3 repositórios reais:
   - **Controle Nível de Água:** [https://github.com/larissadetolinni/controle-nivel-agua](https://github.com/larissadetolinni/controle-nivel-agua)
   - **Meus Sites Favoritos:** [https://github.com/larissadetolinni/meus-sites-favoritos](https://github.com/larissadetolinni/meus-sites-favoritos)
   - **Pesquisa de Satisfação:** [https://github.com/larissadetolinni/pesquisa_satisfacao](https://github.com/larissadetolinni/pesquisa_satisfacao)
6. **Seção de Contato:** Cartão centralizado com botões de ação direta para e-mail (`silvacostalarissa1963@gmail.com`) e GitHub (`https://github.com/larissadetolinni`).
7. **Rodapé:** Notas de direitos autorais e tecnologias.

## Descrição do Recurso Novo Adicionado
Como recurso avançado além do modelo base da aula, foi implementada uma **Seção Interativa de Habilidades e Competências Técnicas** (`#habilidades`), acompanhada de **efeitos visuais avançados de animação em hover** nos cards de projetos e ícones vetoriais integrados.

## Explicação de Como Esse Recurso Foi Implementado
- **Estruturação HTML:** Criação de uma nova `<section id="habilidades">` contendo componentes de barra de progresso (`progress` e `progress-bar`) do Bootstrap combinados com sistema de grid.
- **Estilização CSS Customizada:** Adição de regras CSS no cabeçalho (`<style>`) aplicando transições suaves (`transition: transform 0.4s ease`) nos banners dos cards para gerar efeito de zoom ao passar o mouse (`:hover`), bem como elevação dinâmica nos cards.
