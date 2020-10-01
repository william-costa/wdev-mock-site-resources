# Mock de recursos site WDEV

Repositório complementar do canal [WDEV](https://youtube.com/wdevoficial) para a integração de frontends reativos.

Nesse repositório você vai encontrar variáveis CSS, mocks de APIs e arquivos de imagens necessários para a implementação do frontend.

___________________

## Vídeo WDEV

Para assistir o vídeo dessa implementação, acesse: [VueJS + Axios: desenvolvendo uma aplicação web completa consumindo dados de APIs (YouTube)](https://www.youtube.com/watch?v=kmsM_hHrDHE)

___________________

## Variáveis CSS

Para facilitar a implementação das cores no projeto, seguem abaixo as variáveis CSS com o esquema de cores do front:
```css
:root {
  --color-background:#F3F3F3;
  --color-background-nav:#2B3D50;
  --color-background-home:#344960;
  --color-text-light:#EDEDED;
  --color-text-title:#FF5555;
  --color-text-dark:#3D3D3D;
}
```

___________________

## Imagens

* **Logo WDEV:**  
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/wdev.svg
```

* **Inscreva-se:**
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/subscribe.svg
```

* **Menu Mobile:**
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg
```

As imagens das redes sociais estarão disponíveis no response da API de `GET /social-links.json`;
___________________

## Mocks de APIs

Esse repositório será o endpoint das APIs do front, então é necessário configurar a seguinte URL como base:
```
https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/api
```

A partir dessa URL teremos os seguintes recursos:
* **Redes sociais** `GET /social-links.json`
* **Vídeos** `GET /videos.json`
* **Sobre** `GET /about.json`
* **Contatos** `GET /contacts.json`

___________________

## Canal no YouTube
<img height="60" style="margin-bottom:10px;" src="https://raw.githubusercontent.com/william-costa/william-costa/master/assets/images/logo-wdev.png">

Canal de tecnologia com conteúdos sobre programação e super dicas para a galera que está começando no mundo dev.

Toda **quinta** às **20h** tem vídeo novo, então inscreva-se para não perder nenhuma novidade:

<a href="https://youtube.com/wdevoficial"><img height="30" src="https://raw.githubusercontent.com/william-costa/william-costa/master/assets/images/subscribe-youtube.png"></a>