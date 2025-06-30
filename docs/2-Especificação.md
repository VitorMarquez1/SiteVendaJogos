# Especificações do Projeto

Abaixo serão apresentados as personas, as histórias de usuários, os requisitos do projeto e 
as restrições. A criação de personas possibilita o maior entendimento do cliente, a identificação de 
possíveis problemas e o melhor alinhamento da missão. As histórias de usuários refletem 
suas necessidades. Os requisitos do projeto descrevem o que será implementado no 
software. E as restrições são limitações ou condições impostas ao projeto sobre as 
quais a equipe de desenvolvimento não tem controle.

## Personas

Foram desenvolvidas quatro personas para representar os diferentes perfis de usuários do site, auxiliando na compreensão de suas necessidades e objetivos.

### Nome: José
* **Idade:** 18 anos
* **Profissão:** Programador
* **Hobbies:** Jogar videogame no quarto aos finais de semana.
* **Objetivos:** Comprar jogos e itens relacionados.
* **Personalidade:** Calmo e reservado.

### Nome: Karen
* **Idade:** 21 anos
* **Profissão:** Estagiária em uma PetShop.
* **Hobbies:** Jogar jogos de tiro competitivos nos finais de semana e acompanhar os próximos lançamentos.
* **Objetivos:** Acompanhar os lançamentos de seus jogos preferidos e receber notificações quando estiverem disponíveis.
* **Personalidade:** Calma, racional e bem-humorada.

### Nome: Gohan
* **Idade:** 24 anos
* **Profissão:** Analista de Sistema.
* **Hobbies:** Jogar RPG por duas horas todas as noites e colecionar seus jogos favoritos.
* **Objetivos:** Procurar jogos específicos de seu gosto e diferentes edições de um mesmo título.
* **Personalidade:** Direto em suas opiniões e corajoso.

### Nome: Ronald
* **Idade:** 19 anos
* **Profissão:** Trabalha em um escritório.
* **Hobbies:** Jogar jogos com tema de fazenda durante o almoço e ao chegar em casa.
* **Objetivos:** Encontrar e comprar jogos que não foram lançados oficialmente no Brasil.
* **Personalidade:** Reservado e comunicativo.

## Histórias de Usuários

Com base na análise das personas, foram identificadas as seguintes histórias de usuários:

| EU COMO... `PERSONA` | QUERO/PRECISO ... `FUNCIONALIDADE` | PARA ... `MOTIVO/VALOR` |
| :--- | :--- | :--- |
| Cliente | Saber o valor dos produtos. | Me planejar financeiramente. |
| Cliente | Filtrar o estilo, o preço e o console dos jogos que quero comprar. | Facilitar na busca dos jogos de interesse. |
| Cliente | Visualizar a avaliação e a quantidade disponível de cada produto. | Saber se há produto disponível para compra e, também, sua qualidade. |
| Cliente | Realizar um pré-cadastro no site de forma a receber notificações relevantes. | Saber informações sobre produtos de meu interesse. |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

| ID | Descrição do Requisito | Prioridade |
| :--- | :--- | :--- |
| RF-001 | O sistema deve permitir que usuários naveguem pelo catálogo de jogos por gênero, plataforma, preço e popularidade. | ALTA |
| RF-002 | O sistema deve permitir que usuários pesquisem jogos por título, desenvolvedora ou editora. | ALTA |
| RF-003 | O sistema deve exibir informações detalhadas sobre cada jogo, incluindo descrição, capturas de tela, vídeos, requisitos e avaliações. | ALTA |
| RF-004 | O sistema deve permitir que usuários adicionem jogos ao carrinho de compras. | ALTA |
| RF-005 | O sistema deve permitir que usuários criem e gerenciem suas contas (perfil, histórico de compras, lista de desejos). | ALTA |
| RF-006 | O sistema deve permitir pagamentos com diferentes métodos (cartão de crédito, pix, etc.). | ALTA |
| RF-007 | O sistema deve enviar confirmações de compra por e-mail aos usuários. | MÉDIA |
| RF-008 | O sistema deve permitir que usuários façam o download dos jogos adquiridos. | ALTA |
| RF-009 | O sistema deve permitir que usuários avaliem e comentem sobre os produtos. | MÉDIA |
| RF-010 | O sistema deve oferecer um sistema de recomendação de jogos. | BAIXA |
| RF-011 | O sistema deve permitir que administradores gerenciem o catálogo de produtos (cadastrar, editar, remover). | ALTA |
| RF-012 | O sistema deve permitir a aplicação de cupons de desconto. | MÉDIA |

### Requisitos não Funcionais

| ID | Descrição do Requisito | Prioridade |
| :--- | :--- | :--- |
| RNF-001 | O site deve ter um tempo de resposta máximo de 3 segundos para carregamento. | ALTA |
| RNF-002 | O site deve suportar pelo menos 1000 usuários simultâneos sem perda de desempenho. | MÉDIA |
| RNF-003 | O site deve ser compatível com os navegadores web mais recentes (Chrome, Edge, etc). | ALTA |
| RNF-004 | O site deve ser responsivo e adaptar-se a diferentes tamanhos de tela. | ALTA |
| RNF-005 | O site deve utilizar HTTPS para garantir a segurança das informações. | ALTA |
| RNF-006 | Os dados dos usuários e informações de pagamento devem ser armazenados de forma segura e criptografada. | ALTA |
| RNF-007 | O site deve ter alta disponibilidade. | MÉDIA |
| RNF-008 | O design do site deve ser intuitivo e fácil de usar. | ALTA |
| RNF-009 | O código do site deve ser bem documentado e de fácil manutenção. | MÉDIA |
| RNF-010 | O desenvolvimento deve utilizar as tecnologias HTML, CSS e JavaScript. | ALTA |
| RNF-011 | O site deve ser publicado em um ambiente de hospedagem escalável e publicamente acessível. | ALTA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

| ID | Restrição |
| :--- | :--- |
| 01 | O projeto deverá ser entregue até o final do semestre letivo. |
| 02 | O projeto deve ser desenvolvido utilizando exclusivamente as tecnologias front-end (HTML, CSS, JavaScript), sem a criação de um back-end próprio. A persistência de dados será simulada ou realizada através de um servidor JSON. |
| 03 | O escopo do projeto não contempla a integração real com gateways de pagamento. A finalização da compra será simulada. |
| 04 | O sistema de recomendação de jogos será baseado em regras simples (como gênero ou plataforma), não envolvendo algoritmos complexos de machine learning. |
| 05 | A gestão de produtos é realizada através da interface de CRUD, acessível apenas pelo usuário "Administrador". Não está no escopo a criação de um painel de gerenciamento simplificado para um "cliente final" ou "dono de loja" sem perfil técnico. |