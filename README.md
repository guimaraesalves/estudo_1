https://imasters.com.br/front-end/realidade-aumentada-na-web-com-10-linhas-de-html

site:
## Realidade Aumentada na Web com só 10 linhas de HTML

Uma tecnologia que sempre chamou a minha atenção é a Realidade Virtual. O termo não é nem um pouco recente e muitos experimentos já foram feitos, desde os fracassados, como é o caso do Virtual Boy (não é mesmo, Nintendo?), até os mais bem sucedidos que vemos hoje no mercado, como o Oculus Rift, HTC Vive e afins.

No entanto, apesar do hardware ser muito mais avançado e proporcionar uma experiência bastante imersiva, ele ainda é extremamente caro. Além disso, é composto de muitos sensores e fios, o que impossibilita sua locomoção.

Em paralelo ao avanço desta tecnologia, surgiu a chamada Realidade Aumentada. A premissa, por sua vez, é diferente da que temos com o VR. Aqui, a ideia não é inserir o usuário em um novo mundo, mas sim, ultrapassar os limites da realidade física e trazer novos elementos virtuais ao nosso plano.

Por ser uma tecnologia mais barata, e consequentemente mais acessível, muitas empresas estão apostando algumas fichas nela e muita coisa bacana já está saindo. Um exemplo disso é a própria Apple (a primeira empresa do mundo que alcançou o valor de mercado de US$ 1.000.000.000.000 de dólares!), que lançou uma plataforma dedicada exclusivamente a isso, o ARKit.

E como estou falando de evolução, não tem como fugir da Web; e é neste ponto que as coisas começam a ficar interessantes. Hoje já existem algumas APIs que nos permitem utilizar tanto a realidade virtual quanto a aumentada no navegador. É isso mesmo! E como eu sei que você não está acreditando, vou provar com apenas 10 linhas de HTML.

Conheça o AR.js
No primeiro trimestre de 2017 foi lançada uma biblioteca muito curiosa chamada AR.js. O projeto hoje já possui mais de onze mil estrelas no GitHub, está sob licença MIT, e não para de crescer. Desde o seu início, uma das premissas é que podemos brincar com realidade aumentada com poucas linhas de código.

Para provar isso, os engenheiros disponibilizaram uma demo que podemos testar tanto no nosso computador quanto no celular. Essa demo não é nada mais do que um HTML com 10 linhas de código:

```
<!doctype HTML>
<html>
<script src="https://aframe.io/releases/0.6.1/aframe.min.js"></script>
<script src="https://cdn.rawgit.com/jeromeetienne/AR.js/1.5.0/aframe/build/aframe-ar.js"> </script>
  <body style='margin : 0px; overflow: hidden;'>
    <a-scene embedded arjs>
  	<a-marker preset="hiro">
            <a-box position='0 0.5 0' material='color: black;'></a-box>
  	</a-marker>
  	<a-entity camera></a-entity>
    </a-scene>
  </body>
</html>
```

Referências
https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf
https://github.com/jeromeetienne/ar.js
https://hacks.mozilla.org/2018/09/webxr/
https://webxr.io/webar-playground/
https://pt.wikipedia.org/wiki/Virtual_Boy