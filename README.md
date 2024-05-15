<h1 align="center">🖼️ Segmentação de Imagens no Processing 🖼️</h1>

<p align="center">
<img alt="Static Badge" src="https://img.shields.io/badge/STATUS-CONCLU%C3%8DDO-green?style=for-the-badge">
</p>

<h2 align="left"> 📝 Descrição </h2>
A segmentação de imagens é essencial na visão computacional, permitindo analisar imagens detalhadamente para diversas aplicações. Ela divide uma imagem em partes, como objetos ou pixels individuais, revelando insights valiosos sobre sua estrutura.
<br>Objetivos como identificação precisa de objetos, delimitação de regiões e extração de características impulsionam avanços em áreas como medicina, robótica e segurança.
<br>Para ilustrar sua importância, examinamos 5 diferentes tipos de placas, desde sinais de trânsito até avisos de rua. A segmentação dessas imagens traz benefícios práticos, como melhorar a segurança viária e facilitar a navegação autônoma em ambientes urbanos complexos.
<br>Este projeto foi desenvolvido na <a href="https://www.usf.edu.br">Universidade São Franscisco</a> durante o 7º semestre de Engenharia da Computção na matéria de Computação Visual lecionada pelo <a href="https://www.usf.edu.br">Prof. José Guilherme Picolo</a>.
<br>
<br>
Como dito acima, nosso tema escolhido para o projeto foram placas!
<img src="https://pbs.twimg.com/media/GCcsHE8XYAAzsxz?format=jpg&name=medium" width="300" height="400" align="center"/>
<br>
<br>
<h2 align="left">🧮 Ferramentas e Tecnologias </h2>
<a href="https://processing.org/">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/processing/processing-original.svg" width="40" height="40"/>
</a>
<br>
<br>

<h2 align="left"> 🌐 Imagens Escolhidas </h2>
Essas imagens foram retiradas do seguinte <a href="https://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/dataset.html">banco de dados</a>
<br><br>

<body>
<div class="container">
    <img src="https://i.imgur.com/EOpTQwm.jpeg" >
    <img src="https://i.imgur.com/kAH92c8.jpeg" >
</div>
</body>

<body>
<div class="container">
    <img src="https://i.imgur.com/O1OErkp.jpeg" >
    <img src="https://i.imgur.com/exKJnus.jpeg" >
</div>
</body>

<body>
<div class="container">
    <img src="https://i.imgur.com/1CVUvJl.jpeg" >
</div>
</body>
     

<br>
<h2 align="left"> 📋 Resultados </h2>
Os resultados se darão da seguinte forma:
<br>

- `Imagens Segmentadas originalmete ao lado da nossa segmentação respectivamente`
- `Nossa segmentação com apenas a área pintada segmentada`
  
<br>

Camelo na pista 🐫
- `Filtros Usados`: Escala de cinza, filtro de média, filtro de brilho, limiarizarização, bouding box e preenchimento por inundação
- `Dificuldades`: Preecher a parte segmentada e deixar, deixar a placa inteira segmentada, pontos fora da placa sendo segmentada junto.
- `Resolução`: Uso do preenchimento por inundação, aumentar o brilho, diminuir a limiarização e bouding box respectivamente.
<body>
<div class="container">
    <img src="https://i.imgur.com/10ZMg6v.png" >
    <img src="https://i.imgur.com/0aeZDJo.jpeg" >
</div>
</body>
<br>

Rodovia do Olho do Macaco 🐒
- `Filtros Usados`: Filtro de saturação, sobel, escala de cinza e ajuste de brilho.
- `Dificuldades`: Incluir letras na segmentação, degradê de coloração do céu e não foi possivel retirar uma parte do suporte da placa.
- `Resolução`: Técnica de preenchimento, uso da saturação e a limiarização respectivamente.
<body>
<div class="container">
    <img src="https://i.imgur.com/07fyXKs.png">
    <img src="https://i.imgur.com/bDK8ZaD.jpeg">
</div>
</body>
<br>

Rua do leite 🐄
- `Filtros Usados`: Filtro de saturacao, filtro de brilho, limiarização, escala de cinza, operador logico or, e sobel.
- `Dificuldades`: Separar as partes mais iluminadas do fundo da imagem, captar a borda preta da placa.
- `Resolução`: Aumento da saturacao da imagem p/ descobrir as cores sao predominantes, limiarizacao por cor o operador logico or para melhorar a qualidade do groundtruth gerado utilizando uma limiarizacao da imagem na escala de cinza.
<body>
<div class="container">
    <img src="https://i.imgur.com/XuSHPrm.png">
    <img src="https://i.imgur.com/ZOHhkHf.jpeg" alt="Imagem 2">
</div>
</body>
<br>

Rua Nº1 🛣️
- `Filtros Usados`: Escala de cinza, filtro de média, filtro de brilho, limiarizarização, bouding box e preenchimento por inundação
- `Dificuldades`: Preecher a parte segmentada e deixar, deixar a placa inteira segmentada, pontos fora da placa sendo segmentada junto.
- `Resolução`: Uso do preenchimento por inundação, aumentar o brilho, diminuir a limiarização e bouding box respectivamente.

<body>
<div class="container">
    <img src="https://i.imgur.com/ddLRKay.png" >
    <img src="https://i.imgur.com/iN6oQWL.jpeg" >
</div>
</body>
<br>

Não alimente as gaivotas 🍟
- `Filtros Usados`: Conversão de escala de cinza, brilho e limiarização
- `Dificuldades`: Não houveram
- `Resolução`: ---
<body>
<div class="container">
    <img src="https://i.imgur.com/79W078n.png" >
    <img src="https://i.imgur.com/uU44wAx.jpeg" >
</div>
</body>
<br>

Segmentação pintada 🖍️
<body>
<div class="container">
    <img src="https://i.imgur.com/f6cCu3W.jpeg" >
    <img src="https://i.imgur.com/3JbN8pX.jpeg">
</div>
</body>
<br>
<body>
<div class="container">
    <img src="https://i.imgur.com/2fvrqS1.jpeg" >
    <img src="https://i.imgur.com/424M9CO.jpeg" >
</div>
</body>

<body>
<div class="container">
    <img src="https://i.imgur.com/oZ2gTrB.jpeg" >
</div>
</body>
<br>
<br>


<h2 align="left">✅ Conclusão </h2>
A segmentação de imagens é crucial na visão computacional, permitindo uma análise detalhada de cenários complexos. Seus objetivos variados impulsionam a inovação em diversos campos, desde segurança viária até marketing. Apesar de desafios, nossas segmentações alcançaram uma média de precisão de 99,08%, destacando sua eficácia em extrair informações. Isso ressalta o potencial da segmentação para impulsionar avanços em áreas diversas, mesmo diante de dificuldades.
<br>
<br>
<h2 align="left">🖌️ Autores </h2>

| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/146893811?v=4" width=115><br><sub>Pedro H. Possa<br>RA: 202102625</sub>](https://github.com/pedrohpossa) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/145297917?v=4" width=115><br><sub>Faber<br>RA: 202122739</sub>](https://github.com/faber-junior) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/146894068?v=4" width=115><br><sub>Daniel de Oliveira<br>RA: 202103430</sub>](https://github.com/olvdan) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/146894760?v=4" width=115><br><sub>João Vitor Tosto<br>RA: 202110716 </sub>](https://github.com/zacktosto) | [<img loading="lazy" src="https://avatars.githubusercontent.com/u/99860324?v=4" width=115><br><sub>Matheus Franco<br>RA: 202107447</sub>](https://github.com/Matiobiribo) |
|:---: | :---: | :---: | :---: | :---: |
