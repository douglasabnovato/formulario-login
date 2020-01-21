### Formulário animado com JS puro e CSS Animation

### Criação: 15 de janeiro de 2020
### Atualização: 16 de janeiro de 2020 - 18:42
### Terminado: Sim
### Publicado: https://douglasabnovato.github.io/youtuberocketseatformulario.github.io/
### Prática : @douglasabnovato

## Ferramentas : 

![Git](/images/logo-git.png)
![Github](/images/logo-github.png)
![HTML/CSS/Javascript](/images/logo-html-css-js.jpeg)
![Youtube](/images/logo-youtube.png)
![Rocketseat](/images/logo-rocketseat.png)

### Desafios

- [x] 1. Fazer o formulário aparecer, suavemente, quando a página abrir
- [x] 2. Fazer os campos aparecem da esquerda pra direita, suavizando a entrada e fazendo-os entrar em momentos distintos
- [x] 3. Quando clicar em Login, fazer o formulário sair da tela, indo para baixo
- [x] 4. Remover formulário do html e não mostrar rolagem enquanto o formulário está saindo da tela
- [x] 5. Adicionar um efeito diferente de timing para a saída do formulário
- [x] 6. Fazer o formulário dizer não-não (vibrar) caso haja campos vazios.
- [x] 7. Criar alguns quadrados animados (que fiquem girando) e que saem de baixo da tela (fora do campo de visão) e vão para cima da tela (que saia do campo de visão também). _Detalhes_: Deve ter tamanhos diferentes, sairem em momentos diferentes, terem timing diferente, animação contínua.

### Terminado
![JS puro e CSS animation](/images/tela-1.jpg)
>@douglasabnovato

### Animation

8 propriedades:

- animation-name: animationname;
- animation-duration: 2s;
- animation-delay: 3s;
- animation-fill-mode: none;
- animation-play-state: running;
- animation-timing-function: ease;
- animation-direction: reverse;
- animation-iteration-count: infinite;

```css
@keyframes animationname {
  0% {

  }

  100%{

  }
}
```

podemos ter múltiplas animações no mesmo elemento

```css
.animate {
  animation: slide-top 2s, bounce 1s, fade 0.2s;
}
```

### References

[CSS Animation Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)<br/>
[Animation Timing Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function)<br/>
[Site para criar animações](http://animista.net/play/basic/scale-up)<br/>
[Site para criar cubic Bézier timming](https://matthewlein.com/tools/ceaser)<br/>

:. De Mayk Brito | Formulário Animado com JS puro e CSS Animation - `https://www.youtube.com/watch?v=GykTLqODQuU`