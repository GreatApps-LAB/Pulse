# GreatPages-Pulse

<a href="https://www.buymeacoffee.com/claitonllemes" target="_blank" rel="noopener noreferrer"><img src="https://user-images.githubusercontent.com/99222756/210368404-216273fb-c930-453e-b32b-e3614872eba3.png" width="100%"/></a><br>

https://github.com/GreatApps-LAB/Pulse/assets/99222756/59a646b4-26f8-43fc-ba2a-f1a968e2389d

```html

<style>

  /* Define variáveis CSS para cores principais */
  :root {
    --main-color: #268df3; /* Cor principal para a sombra inicial */
    --highlight-color: rgba(0, 200, 0, 0.2); /* Cor destacada para a sombra durante a animação */
  }

  /* Aplica a animação de pulso ao elemento com ID "e_0000000000 .c" */
  #e_00000000000 .c {
    animation: pulse 2s infinite;
  }

  /* Define a animação de pulso usando a notação de keyframes */
  @keyframes pulse {
    0% {
      box-shadow: 0 0 0 0 var(--main-color); /* Sombra inicial sem desfoque */
    }
    80% {
      box-shadow: 0 0 20px 0 var(--highlight-color); /* Sombra destacada com desfoque de 20px */
    }
    100% {
      box-shadow: 0 0 0 0 var(--highlight-color); /* Retorna à sombra sem desfoque no final */
    }
  }

</style>
