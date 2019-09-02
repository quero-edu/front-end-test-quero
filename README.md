# Front End Test Quero

## Bolsas favoritas

O **Querobolsa.com** é um marketplace de bolsas de estudo, que já ajudou milhares de alunos a escolher e ingressar no curso ideal, por um preço que podem pagar.
A sua missão é fazer uma página onde o aluno possa filtrar bolsas de estudo de seu interesse e adicionar à uma lista de bolsas favoritas.




## Requisitos do projeto:
* Apenas código front-end será considerado nesse projeto: HTML5, CSS e Javascript.
* Pré-processadores CSS podem ser usados à vontade.
* Frameworks CSS não são permitidos. Todo código CSS deve ser escrito por você.
* O projeto pode ser escrito em javascript puro ou utilizar frameworks como Vue.js, React ou outro.
* Gerenciadores de pacotes e task runners podem ser usados à vontade.
* Ícones e imagens não precisam ser fiéis ao layout. Fique à vontade para utilizar a biblioteca de ícones de sua preferência. Nós recomendamos a versão gratuita do FontAwesome: https://fontawesome.com.
* O projeto precisa ser responsivo, respeitando os layouts que iremos disponibilizar.




## Layouts:
As telas que você irá desenvolver estão neste link: https://drive.google.com/drive/folders/1W-tYS90OG4Jn7QiWQ9pTU6b2U64_PijO?usp=sharing

## Especificações de design:
* Cores:
  * Azul principal: `#18ACC4` ![#18ACC4](https://placehold.it/15/18ACC4/000000?text=+)
  * Azul secundário: `#007A8D` ![#007A8D](https://placehold.it/15/007A8D/000000?text=+)
  * Amarelo principal: `#FDCB13` ![#FDCB13](https://placehold.it/15/FDCB13/000000?text=+)
  * Amarelo secundário: `#DE9E1F` ![#DE9E1F](https://placehold.it/15/DE9E1F/000000?text=+)
  * Verde: `#0FA866` ![#0FA866](https://placehold.it/15/0FA866/000000?text=+)
  * Preto (textos): `#1F2D30` ![#1F2D30](https://placehold.it/15/1F2D30/000000?text=+)
  * Cinza (background): `#FBFBFB` ![#FBFBFB](https://placehold.it/15/FBFBFB/000000?text=+)
  * Overlay do modal: Preto (`#1F2D30` ![#1F2D30](https://placehold.it/15/1F2D30/000000?text=+) ) com 88% de opacidade.

## Especificações de funcionalidades:
* O projeto possui uma única página, com a lista de favoritos e um modal para a busca de cursos;
* A clicar em Adicionar curso, deve abrir o modal de busca;
* A busca deve conter os seguintes filtros:
  * Cidade;
  * Curso;
  * Modalidade (Presencial/EaD);
  * Preço;
* A lista de cursos deve ter ordenação por nome da faculdade;
* Múltiplos cursos podem ser selecionados e adicionados à lista de favoritos;
* O botão Adicionar bolsa(s) deve ficar desabilitado enquanto não houver cursos selecionados;
* Os cursos podem ser removidos da lista de favoritos, através do botão Excluir;
* O botão Ver oferta não leva a lugar algum;
* Bolsas com { enabled: false }, devem aparecer com o botão Indisponível;
* A lista de favoritos deve respeitar o semestre selecionado.



## Dados:
Disponibilizamos uma API de testes, onde você pode consultar a lista de cursos, fazendo uma requisição GET na seguinte url: https://testapi.io/api/redealumni/scholarships

A resposta da requisição irá retornar uma lista de bolsas de estudo no seguinte formato:

    "full_price": float,
    "price_with_discount": float,
    "discount_percentage": float,
    "start_date": string,
    "enrollment_semester": string,
    "enabled": boolean,
    "course": {
      "name": string,
      "kind": string,
      "level": string,
      "shift": string
    },
    "university": {
      "name": string,
      "score": float,
      "logo_url": string
    },
    "campus": {
      "name": string,
      "city": string



## Instruções para entrega do projeto:
* Desenvolva e versione esse projeto usando git.
* Utilize o serviço de hospedagem de código de sua preferência: github, bitbucket, gitlab ou outro.
* Crie um README com instruções claras sobre como executar seu projeto.


## Critérios de avaliação:
* Fidelidade ao layout solicitado;
* Fidelidade às funcionalidades solicitadas;
* HTML estruturado de forma semântica;
* Clareza de nomenclatura do CSS;
* Adesão ao mobile first.


## Sugestões extras (não obrigatórias):
* Desenvolvimento de testes;
* Seguir algum style guide de Javascript;
* Seguir algum style guide de CSS;
* Componentização e extensibilidade dos componentes Javascript;
* Persistir a lista de favoritos no browser do cliente;
* Aplicar animações de transição.
