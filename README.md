<h1 align="center">
    <img alt="Image Trybe" src="https://i.ibb.co/d4W2x4g/trybe.png" width="400px" />
</h1>

<h3 align="center">
  Exercício 6-3: CSS Flexbox - Parte 2 - Concluído o/ o/ o/
</h3>

<blockquote align="center">“Quanto mais você estuda, mais aprende e se aproxima de realizar seu sonhos!”</blockquote>

<h1></h1>

<p align="center">

  <a href="https://www.linkedin.com/in/eduardosouzaprogrammer/">
    <img alt="Made by Eduardo Souza" src="https://img.shields.io/badge/made%20by-Edu%20Souza-%23F8952D">
  </a>&nbsp;

 <a href="https://edusouza-programmer.github.io/">
<img alt="Github page Edu Souza " src="https://img.shields.io/badge/Github%20page-Edu_Souza-orange">
</a>&nbsp;

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

<p align="center">
  <a href="#rocket-Sobre-o-Exercício">Sobre o Exercício</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Entrega">Entrega</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Licença">Licença</a>
</p>

# :rocket: Sobre o Exercício

Para os exercícios a seguir, utilize este playground para testar como as propriedades Flexbox influenciam a disposição dos elementos em um container. Existem outros playgrounds para Flexbox como este, e os links para eles estão nos Recursos adicionais.
Como os exercícios serão feitos na própria plataforma, crie um diretório em seu repositório para o site número 1 (problema do sapo) e outro para o site número 2 (problema das torres).

-   Faça os exercícios de 14 a 24 neste [site](https://flexboxfroggy.com/). O seu objetivo é colocar os sapos em cima de suas respectivas folhas.

-   Neste segundo [link](https://flexboxfroggy.com/), complete os exercícios de 10 a 12. Seu objetivo aqui é posicionar as torres de defesa para que elas abatam os inimigos. Você terá de pensar qual é a melhor posição para cada torre.

-   (Opcional) Para finalizar, escolha alguns exercícios antigos como, por exemplo, o portfólio ou até mesmo os projetos de HTML, CSS e JavaScript e estruture as páginas utilizando Flexbox.

#

# Entrega

### Sumário

#### Parte-1

-   <p><a href="#14">14.</a> Às vezes, inverter a ordem das linhas ou colunas de um contêiner não é suficiente...</p>

-   <p><a href="#15">15.</a> Use a orderpropriedade para enviar o sapo vermelho ao seu nenúfar.</p>

-   <p><a href="#16">16.</a> Outra propriedade que você pode aplicar a itens individuais...</p>

-   <p><a href="#17">17.</a> Agora use align-items para ajudar as rãs a chegarem ao fundo do tanque...</p>

-   <p><a href="#18">18.</a> Conduza o sapo para o centro da lagoa usando uma combinação de justify-contente align-items.</p>

-   <p><a href="#19">19.</a> Os sapos precisam cruzar o lago novamente, desta vez para alguns nenúfares...</p>

-   <p><a href="#20">20.</a> As rãs precisam ficar na mesma ordem que seus nenúfares usando flex-direction. Esta...</p>

-   <p><a href="#21">21.</a> Ajude as rãs a encontrar sua coluna de nenúfares usando flex-direction. Esta propriedade...</p>

-   <p><a href="#22">22.</a> Ajude as rãs a pegar seus próprios nenúfares. Embora pareçam próximos...</p>

-   <p><a href="#23">23.</a> Ajude as rãs a encontrar seus nenúfares usando flex-directione...</p>

-   <p><a href="#24">24.</a> Ajude as rãs a encontrar seus nenúfares usando flex-directione justify-content.</p>

#

## Exercícios [Meus códigos]

### 14°

Às vezes, inverter a ordem das linhas ou colunas de um contêiner não é suficiente. Nesses casos, podemos aplicar a orderpropriedade a itens individuais. Por padrão, os itens têm um valor de 0, mas podemos usar essa propriedade para defini-la também como um valor inteiro positivo ou negativo (-2, -1, 0, 1, 2).

Use a orderpropriedade para reordenar as rãs de acordo com seus nenúfares.

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css
#pond {
    display: flex;
}

.amarelo {
    order: 1;
}
```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_14°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 15°

Use a orderpropriedade para enviar o sapo vermelho ao seu nenúfar.

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css
#pond {
    display: flex;
}

.red {
    order: -1;
}
```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_15°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 16°

Outra propriedade que você pode aplicar a itens individuais é align-self. Esta propriedade aceita os mesmos valores align-itemse seu valor para o item específico.

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css
#pond {
    display: flex;
    align-items: flex-start;
}

.amarelo {
    align-self: flex-end;
}
```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_16°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 17°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_17°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 18°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_18°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 19°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_19°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 20°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_20°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 21°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_21°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 22°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_22°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 23°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_23°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 24°

#### Resposta:

<details>
 <summary>Código CSS</summary>

```css

```

</details>

<p align="right">
    <a href="https://flexboxfroggy.com/">
    <img alt="Go index.html" src="https://img.shields.io/badge/link-exercise_24°-orange">
    </a>&nbsp;
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

## Licença

Este projeto está licenciado sob a Licença MIT - consulte [LICENSE](https://opensource.org/licenses/MIT) para maiores detalhes.
