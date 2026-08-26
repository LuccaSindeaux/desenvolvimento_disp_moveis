# desenvolvimento_disp_moveis
Todas as aulas de dispositivos móveis 2026

## Estrutura básica de uma media querie

```css
@media only screen and (/*condicao*/){/*codigo da modificacao*/}
```

#### Exemplo prático:

```css
body{
    background-color: aqua;
}

@media only screen and (min-width: 500px){
    body{
        background-color: darkblue;
    }
}

/* Mexer na tela, deixar com menos de 500 pixels para ver ela se tornar aquamarine */
```

#### obs.: o 'only' é uma medida de segurança para navegadores antigos que não possuem suporte para lerem media queries. Então eles leem o arquivo CSS, enxergam o termo only, e imediatamente não tentam mais aplicar o as configurações ao HTML.