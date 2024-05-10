# Estilizações de Texto e Cores

Este arquivo contém estilizações de texto e cores para o projeto.

## Modo de Uso

Para utilizar essas estilizações no seu projeto, siga os passos abaixo:

1. Adicione este arquivo dentro da pasta de components do Sass.

2. Adicione as cores definidas neste arquivo dentro das variáveis do Sass.

3. Após importar as fontes necessárias para o projeto, atualize o `font-family` com o nome definido na importação. Exemplo:
   
    // Importação da fonte
   
@font-face {
    font-family: 'DMSans Bold';
    font-style: normal;
    font-weight: normal;
    src: url("../../src/fonts/DMSans-Bold.woff") format("woff");
}

   // Nomeação das fontes no avariables
       $fonteBold: "DMSans Bold";
       

   // Atualização do font-family
    h1 {
        font-family: $fonteBold;
    }

   -- Se as fontes importadas já virem com Regular, Medium e Bold, podemos retirar o font-weight

Certifique-se de compilar o arquivo Sass para que as estilizações sejam aplicadas corretamente no seu projeto.
