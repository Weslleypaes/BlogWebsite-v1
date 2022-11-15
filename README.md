<h1>Blog Website v-1</h1>
<p>Se trata de um desafio proposto durando meu curso de Fullstack no qual o objetivo final seria, criar uma rota no qual teria dois inputs, um seria do título do assunto, e o outro input, o assunto.</p>
<p>E os dados que eu pusesse nos inputs, deveriam ser postado na página Home do site.</p> 
<p>Utilizei Node/Express, EJS, Css e Bootstrap. Além de outras ferramentas como Body Parser e Lodash.</p>

<p> Essa é a página Home, sem nada publicado.</p>

![Captura de tela de 2022-11-15 14-48-08](https://user-images.githubusercontent.com/95313382/201994152-ca52bb24-cd14-482e-a14f-bf4254e61173.png)

<br>
<br>
<p> Página no qual eu insiro alguns dados para que esse seja enviado para o Home.</p>
<i>OBS:A única forma de acessar essa rota, é manipulando o URL da página, nota-se que eu acessei a rota /compose para chegar nessa página</i>


![Captura de tela de 2022-11-15 14-50-18](https://user-images.githubusercontent.com/95313382/201995010-a008e9eb-5262-4e13-b3b4-429f6922dfb4.png)

<br>
<br>
<p> Depois de clicar no botão Publish, e acessando a rota home novamente.</p>
<p> Nota-se que possui uma âncora escrito "Read More". Ela está ali para que a página home não fique poluída com textos gigantes. E como ter acesso ao conteúdo completo ? </p>

![Captura de tela de 2022-11-15 14-50-41](https://user-images.githubusercontent.com/95313382/201996068-030b7937-42d5-48f3-b390-2d0e4c4b3101.png)

<br>
<br>
<p> Para ter acesso ao conteúdo completo, basta clicar na âncora, ou utilizar o nome do tópico na url, por exemplo: localhost:3000/posts/copa-do-mundo </p>
<p>Após isso, é renderizado uma tela que se aproveita do template do site, e essa tela possui todo o conteúdo do tópico "Copa do Mundo" que foi digitado anteriormente.</p>

![Captura de tela de 2022-11-15 14-50-51](https://user-images.githubusercontent.com/95313382/201998546-4a44634a-c9e6-4fd3-8818-178a1c7024ac.png)

<br>
<br>
<p> Assim é possível criar infinitos tópicos e conteúdos diferentes.</p>

![Captura de tela de 2022-11-15 14-51-28](https://user-images.githubusercontent.com/95313382/201998806-a302abc9-ff49-49f3-8607-6acee06b2f68.png)
