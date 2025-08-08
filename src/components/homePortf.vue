<template>
    <div class="informacoes">
        <h1>Vinicius Nunes falcao</h1>
        <li class="ruaDeCasa"><a href="">Rua José Alves Ribeiro, 25 - Vila Paraiso</a></li>
        
        <div class="juntos">
            <a href=""><h4>Aquidauana - MS </h4></a>
            <a href="" class="distanciaPrimeiro"><h4>(67) 9 9118 - 7801</h4></a>
            <a href="" class="distanciaSegundo"><h4>F94nunes@gmail.com</h4></a>
        </div>
        <h4 class="minhaIdade">26 anos | Solteiro</h4>
    </div>
    <div class="resumoProfissional">
        <div class="objetivo">
            <h1>OBJETIVO</h1>
            <h4>Atuar na área de tecnologia da informação, 
                com foco em desenvolvimento de software, 
                utilizando linguagens como Python e JavaScript para criação de soluções práticas e 
                eficientes.
            </h4>
            <h1>RESUMO PROFISSIONAL</h1>
            <h4>Profissional em desenvolvimento na área de tecnologia, com conhecimento prático em 
                Python e JavaScript, além de experiência no uso de bibliotecas, integração com APIs e 
                desenvolvimento full-stack. Vivência internacional em Portugal, onde teve a oportunidade 
                de aprofundar-se no universo da programação. Curioso por natureza e motivado por 
                desafios, possui forte interesse em engenharia reversa e inovação tecnológica.
            </h4>
        </div>
    </div>
    <div class="academicoCursos">
        <div class="tecnicosFaculdade">
            <h1>FORMAÇÃO ACADEMICA</h1>
            <h4><li>Curso Técnico – Full-Stack JavaScript
                High Tech – Guimarães (2023 – 2024)
            </li></h4>
            <h4><li>Curso Técnico – Programação em Python
                Tóquio School – Guimarães (2023)
            </li></h4>
            <h4 style="display: flex;"><li>Ensino Superior – Ciência da Computação
                Centro Universitário Internacional Uninter – Campo Grande (2025 – 2029)
            </li></h4>
        </div>
        <div class="cursosCertificados">
            <h1>CURSOS E CERTIFICAÇÕES</h1>
            <h4><li><a href="">Desenvolvimento Web com JavaScript</a></li></h4>
            <h4><li><a href="">Programação em Python com foco em APIs e automação</a></li></h4>
            <h4><li><a href="">Git e GitHub para controle de versão</a></li></h4>
            <h4><li><a href="">Boas práticas de programação e estruturação de código</a></li></h4>
        </div>
        <div class="informaticaTecnologia">
            <h4><li><a href="">Domínio de Python e JavaScript</a></li></h4>
            <h4><li><a href="">Experiência com bibliotecas, APIs e automação</a></li></h4> 
            <h4><li><a href="">Desenvolvimento full-stack com foco em aplicações práticas</a></li></h4> 
            <h4><li><a href="">Noções de banco de dados, versionamento e integração de sistemas</a></li></h4>
        </div>
        <div class="idiomas">
            <h1>IDIOMAS</h1>
            <h4>Portugues - Nativo</h4>
            <h4>Ingles - intermediario</h4>
        </div>
        <div class="redesSociais">
            <h1>REDES SOCIAIS</h1>
            <h4><li><a href="https://www.instagram.com/time.over.625/#">Instagram</a></li></h4>
            <h4><li><a href="www.linkedin.com/in/vinicius-nunes-293a8625a">Linkedin</a></li></h4>
            <h4><li><a href="https://github.com/ViniciusN1">GitHub</a></li></h4>
        </div>
        <div class="FinalResumo">
            <h1>Sobre mim</h1>
            <h4>Desde a infância, a curiosidade intelectual sempre esteve presente em minha trajetória, 
                motivando-me a buscar conhecimento e compreender a lógica por trás dos sistemas e processos. 
                Essa inclinação natural evoluiu para um interesse sólido pela área de tecnologia, 
                na qual encontrei minha verdadeira vocação. Durante uma experiência profissional em Portugal, 
                tive a oportunidade de ampliar significativamente minha visão técnica e prática, 
                o que reforçou minha decisão de aprofundar os estudos em programação. Tenho especial interesse 
                por desenvolvimento de sistemas, criação de soluções tecnológicas e engenharia reversa, 
                atuando com foco em aprimoramento contínuo, inovação e superação de desafios complexos.</h4>
        </div>
    </div>
    
</template>
<script>
export default {
  name: "homePortf"
};
</script>
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: 'Press Start 2P', cursive;
  background: linear-gradient(to top, #7ec0ee, #ffffff);
  background-image: url('https://i.imgur.com/2h3UG0P.png'); /* fundo com nuvens estilo Mario */
  background-repeat: repeat-x;
  background-position: bottom;
  animation: scroll-background 60s linear infinite;
  color: #333;
}

@keyframes scroll-background {
  0% {
    background-position-x: 0;
  }
  100% {
    background-position-x: 1000px;
  }
}

h1, h4, li {
  font-family: 'Press Start 2P', cursive;
  color: #d62828;
  margin: 10px 0;
}

a {
  color: #003049;
  text-decoration: none;
  transition: transform 0.2s ease;
}

a:hover {
  color: #f77f00;
  transform: scale(1.1);
}

.informacoes {
  background-color: rgba(255, 255, 255, 0.8);
  margin: 20px;
  padding: 20px;
  border: 4px solid #fcbf49;
  border-radius: 20px;
  animation: bounceIn 1s ease;
}

@keyframes bounceIn {
  0% {
    transform: scale(0.7);
    opacity: 0;
  }
  100% {
    transform: scale(1);
    opacity: 1;
  }
}

.resumoProfissional,
.academicoCursos,
.tecnicosFaculdade,
.cursosCertificados,
.informaticaTecnologia,
.idiomas,
.redesSociais,
.FinalResumo {
  background-color: rgba(255, 255, 255, 0.85);
  margin: 20px;
  padding: 20px;
  border: 4px dashed #f77f00;
  border-radius: 15px;
  animation: fadeInUp 1.2s ease;
}

@keyframes fadeInUp {
  from {
    opacity: 0;
    transform: translateY(50px);
  }
  to {
    opacity: 1;
    transform: translateY(0);
  }
}

.juntos {
  display: flex;
  gap: 20px;
  flex-wrap: wrap;
  margin: 10px 0;
}

.juntos a h4 {
  font-size: 10px;
  color: #003049;
}

.minhaIdade {
  font-size: 10px;
  margin-top: 10px;
}

li {
  list-style: none;
}

</style>