# DesafioEcompJr

# Frontend do Projeto To-do List

Este documento descreve a estrutura do frontend, detalhando os componentes e a interação com o backend.

## Sumário

- [Estrutura do Projeto Frontend](#estrutura-do-projeto-frontend)
- [Instalação do Frontend](#instalação-do-frontend)
- [Configuração](#configuração)
- [Como Adicionar Imagens](#como-adicionar-imagens)
- [Como Executar](#como-executar)

## Estrutura do Projeto Frontend

O frontend do projeto foi desenvolvido utilizando React.js, que gerencia a interface com os usuários, permitindo que eles possam interagir com o sistema de gerenciamento de tarefas.

1. **Components**: A pasta `/components` contém os componentes reutilizáveis do frontend, como botões, formulários e elementos da interface gráfica.

2. **Pages**: A pasta `/pages` contém as páginas principais do sistema, como a página de login, página de registro, página de tarefas e página de administração.

3. **API**: A comunicação com o backend é feita por meio de chamadas à API utilizando Axios para gerenciar requisições HTTP.

4. **Styles**: O frontend utiliza arquivos CSS para estilização, e os estilos estão organizados em uma pasta chamada `/styles`, onde cada página possui seu arquivo de estilo correspondente.

## Instalação do Frontend

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/tamillycosta/DesafioEcompJr.git
   cd DesafioEcompJr/frontend

2. **Instale as dependências:**
   ```bash
   npm install

## Configuração
Antes de executar o projeto, verifique se o backend está rodando e se as rotas estão corretamente configuradas. Você pode definir a URL do backend no arquivo de configuração do frontend.

1. Verificar URL do Backend:

No arquivo src/api/api.js, ajuste o endereço do backend para o caminho correto, dependendo do ambiente (desenvolvimento ou produção):
   ```javascript
   const baseUrl = process.env.REACT_APP_API_URL || 'http://localhost:8000';

## Configuração
