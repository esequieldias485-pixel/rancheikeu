# Ranch Cart Tally

Crie um aplicativo web completo chamado "Ana Ranchos". O aplicativo deve ser uma calculadora/gerenciador de compras de supermercado com uma interface linda, moderna e responsiva. 

Siga estritamente os requisitos abaixo:

1. TELA DE LOGIN (Autenticação Simulada ou Supabase):

- Uma tela inicial de login com campos de Usuário e Senha.

- Design elegante sobreposto a um fundo suave.

2. DESIGN E VISUAL (Tema Hortifrúti/Supermercado):

- Logotipo: Crie um logotipo centralizado no topo com o nome "Ana Ranchos", usando um ícone moderno de carrinho de compras misturado com folhas orgânicas ou uma mini horta.

- Fundo e Cores: Use uma identidade visual que remeta a mercados e frescor. Utilize tons de verde-folha, laranja-cenoura e fundo limpo (branco/off-white) com padrões sutis de ilustrações de verduras, legumes e frutas (como marcas d'água ou fundos de seção bem elegantes para não atrapalhar a leitura).

3. FUNCIONALIDADE DA CALCULADORA DE PRODUTOS:

- Campos de entrada: "Nome do Produto", "Quantidade" (seletor numérico) e "Valor Unitário".

- REGRA CRÍTICA DO VALOR (Prevenção de Erro de Centavos): Configure o campo de valor para que ele formate automaticamente os centavos. O usuário deve conseguir digitar os valores normalmente e o sistema precisa aceitar tanto o ponto quanto a vírgula como separadores decimais, garantindo que se ele digitar "5" vire "5,00", e se digitar "5,50" os centavos entrem perfeitamente sem quebrar o cálculo.

- Botão "Adicionar ao Rancho".

4. LISTA E TOTAIS:

- Exibir uma tabela ou lista com os produtos adicionados, mostrando: Nome, Qtd, Valor Unitário e Valor Total do Item (Qtd x Valor).

- Botão para excluir itens individualmente.

- Um card destacado no topo ou na parte inferior mostrando o "TOTAL GERAL DO RANCHO" em tempo real.

This project was built with [Lovable](https://lovable.dev).

**Live app**: https://ranch-cart-tally.lovable.app

## Build with Lovable

Continue developing this project in the [Lovable editor](https://lovable.dev/projects/c4db3e9b-fcbc-4142-b29f-f1810b5b31b1).

- **Ship faster**: describe what you want to build and Lovable handles the code.
- **Stay in sync**: every change made in Lovable is committed straight to this repository.
- **Full ownership**: this code is yours. Push to `main` on GitHub and your changes sync back into Lovable, ready for your next prompt.

## Development

Prefer working locally? You need Node.js and npm — [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating).

```sh
git clone <this-repository-url>
cd <repository-name>
npm i
npm run dev
```
