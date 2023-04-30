## Botando em pratica a criação de [Casos de Teste] 🪲🔍

- Aqui vou passar umas dicas de como fazer alguns **Casos de Teste**. 
- Doc. voltado para: *QA/Testers.*

## **Casos de teste**

A segunda forma mais detalhada de documentar o trabalho de um teste são os casos. Os casos de teste descrevem uma ideia específica a ser testada, sem detalhar os dados necessários e etapas exatas a serem executadas. Por exemplo, um caso de teste poderia ser “Testar se um código de desconto pode ser aplicado em um produto em promoção”. Isso não descreve quantos vão ser códigos ou como serão utilizados. A forma de testar este caso pode variar de tempos em tempos. O testador pode usar um link para aplicar o desconto, inserir um código, solicitar alguém do suporte ao consumidor para aplicar o desconto ou tentar outras formas criativas de encontrar o resultado. Os casos de teste proporcionam uma flexibilidade para os testadores decidirem de que forma eles pretendem completar o teste.

Esta flexibilidade dos casos é boa e ruim. Flexibilidade é benéfica quando o testador já é familiarizado com testes e com os detalhes do software que está sendo testado. Se o testador entendeu claramente o que já foi testado, o que foi modificado recentemente no programa e quantos usuários geralmente usam o programa, as estratégias de teste pode ser tanto usar os caminhos que os usuários normalmente usam ou formas mais inusitadas, para encontrar bugs escondidos.

Por outro lado, se os testadores não tiverem compreendido como o programa é usado, os riscos recentes e como avaliar esses riscos como um testador, eles podem não ter a informação ou habilidade necessária para realizar ações que podem encontrar bugs importantes.

## **Cenários de teste**

O tipo menos detalhado de documentação é o cenário de teste. Um cenário de teste é uma descrição de um objetivo que o usuário pode encontrar ao utilizar o programa. Um exemplo seria “Testar se um usuário consegue deslogar do programa ao fechá-lo”. Tipicamente, um cenário de teste vai precisar de diferentes tipos de testes para garantir que o objetivo tenha sido bem testado. Utilizando o exemplo, o testador pode escolher fechar o programa pelo menu, fechá-lo pelo gerenciador de tarefas, desligar o computador ou como o programa reage quando fica sem memória e dá erro. Já que os cenários de testes oferecem pouca informação sobre como completar o teste, os testadores tem uma grande flexibilização para buscar uma solução.

Assim como os casos de teste, a flexibilidade dos cenários oferecem prós e contras similares. O conhecimento de causa e as habilidades em testes podem facilitar os testadores a transformar os cenários em ideias concretas, escolher a abordagem mais lógica e rodar os testes que podem extrair os problemas importantes. Este tipo de trabalho é um desafio para um testador habilidoso, mas pode ser difícil ou até mesmo impossível para um novato. Entretanto, se o novato estiver amparado em uma equipe, ele pode aprender o suficiente para conseguir.

> Fonte: https://www.primecontrol.com.br/o-que-sao-cenarios-scripts-e-casos-de-teste/


## 📑 Resumo - [Notion]
[Notion - Base](https://thirsty-piano-160.notion.site/38b29a335ae94ef2822ee525c58af191?v=0306adb0cacf49aa86eca6c5ba088bc1)
No link acima, tem o template detalhado 
**Só clicar no link em azul!**

## 🔗Sites para Exercícios

> *https://www.magazineluiza.com.br/*

> *https://www.nike.com/*

> *https://www.netshoes.com.br/*

> *https://amazon.com.br/*

> *https://www.mercadolivre.com.br*

> *https://br.shein.com/*

## 💻 Iniciando ...

- Escolha 1 site, ex: *https://www.magazineluiza.com.br/*;
- Escolha funcionalidades, como - [Cadastro, Login ou Reset de senha];
- Registre o passo a passo da funcionalidade de forma direta e com alguns exemplos.

> Modelo de script abaixo:

-   **Nome do caso de Teste:** Realizar login com usuário válido
---
-   **Objetivo:** Verificar se é possível realizar login no site.
---
-   **Pré-condições:**

1.  O usuário deverá estar no link do site: [MAGALU - Área de Cadastro | Login](https://sacola.magazineluiza.com.br/#/cliente/login/?next=https%3A//www.magazineluiza.com.br/%3Fpartner_id%3D974%26gclid%3DCj0KCQjw8qmhBhClARIsANAtboetB67Yy1A8G7obpG2f6_fF_lnGd9BJBbyltuL2l8fLpHl6c_hoXQ0aAhV3EALw_wcB%26gclsrc%3Daw.ds&origin=magazineluiza);
2.  O usuário deverá identificar o campo de [Já sou cliente].
---
-   **Passos:**

1.  Inserir (E-mail, CPF ou CNPJ), [Ex: [ttuao.teste@gmail.com](mailto:ttuao.teste@gmail.com)]; 
2. Inserir senha para obter acesso, [Ex: 123456]; 
3. Clicar no botão de [Continuar].
---
-   **Resultados esperados:**
1.  O sistema deverá realizar o login com usuário válido;
2.  O sistema deverá redirecionar para a tela inicial.
---
-   **Pós-condições:**
1.  O usuário está conectado ao sistema;
2.  O sistema exibe a página principal.
---
-   **Observações:**
1.  Se o login for invalido, uma mensagem de erro deve ser exibida ao usuário;
2.  Se qualquer dado estiver incorreto, o usuário não deve ser logado no sistema.



## 📑 Resumo - Geral

- Ser direto é necessário para o entendimento posterior dos casos;
- Ser detalhista ajuda a não se perder no processo;
- É sempre bom testar funcionalidades em vários sites públicos, assim a capacidade analítica aumenta e ajuda a realizar futuros testes com base na experiência de testador;
- Caso inconformidades apareçam durante o processo de testes as mesmas são reportadas utilizando ferramentas de "bug tracker". As mais conhecidas são (Mantis, Jira, Bugzilla, Trac). Farei apontamentos em um novo artigo de como é o processo de report das inconformidades.

``Finalizando por aqui.. Para visualizar casos mais detalhados acessar o link do template do [Notion]. ``
