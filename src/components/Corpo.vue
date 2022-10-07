<template>
  <div class="container text-center">
    <div class="row">
      <div class="col-sm-3">
        <div class="row align-items-left" style="height: 100%; width: 27vw;">
          <div class="col-md-12">
            <figure class="figure">
              <img
                src="../components/img/bnd.png"
                class="figure-img img-fluid rounded"
                alt="..."
                style="height: 200px; width: 200px"
              />
            </figure>
            <div class="colortxt">
              <h1>Bernardo Stocco</h1>
              <h6>Front-end Developer</h6>
            </div>
            <div class="fts">
              <h1>Skills</h1>
              <img
                src="../components/img/react-svgrepo-com.svg"
                class="border-dark"
                alt="..."
                style="height: 50px; "
              />
              <div/>
              <img
                src="../components/img/bootstrap-svgrepo-com.svg"
                class="border-dark"
                alt="..."
                style="height: 50px; "
              />
              <div/>
              <img
                src="../components/img/vue-svgrepo-com.svg"
                class="border-dark"
                alt="..."
                style="width: 50px;"
              />
              <div/>
              <img
                src="../components/img/js-svgrepo-com.svg"
                class="border-dark"
                alt="..."
                style="width: 50px;"
              />
              <div/>
              <img
                src="../components/img/git-icon-svgrepo-com.svg"
                class="border-dark"
                alt="..."
                style="width: 50px;"
              />
              <div/>
              <img
                src="../components/img/figma-1-logo-svgrepo-com.svg"
                class="border-dark"
                alt="..."
                style="width: 50px;"
              />
            </div>
          </div>
        </div>
      </div>
      <div class="col-3 col-sm-6">
        <img
          src="../components/img/CERTIFICADOS.svg"
          class="rounded "
          alt="..."
        />
        <p>
          UI Design Avançado, UX Design Heurísticas, Bootstrap 4, Formação
          JavaScript Developer, Scrum Certification, Dominando Git e GitHub,
          iniciante ao expert, CSS com SASS e Formação React Developer
        </p>
        <img
          src="../components/img/EXPERIÊNCIA.svg"
          class="rounded "
          alt="..."
        />
        <p>Estagiário Tribunal de Justiça do RS - 2 anos</p>
        <p>Soldado Exército Brasileiro - 10 meses</p>
        <p>
          Auxiliar administrativo REITERLOG - 5 meses
        </p>
        <p>
          Auxiliar administrativo Cooperativa Santa Clara - 5 meses
        </p>

        <img src="../components/img/FORMAÇÃO.svg" class="rounded " alt="..." />
        <p>
          IFSUL - Instituto Federal Sul-rio-grandense | Ciência da Computação | Mar 2022 - Jul 2022
        </p>
        <p>
          UNOPAR - Universidade Norte do Paraná | Análise e Desenvolvimento de Sistemas | Jul 2022 - Jul 2024
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Corpo",
};
</script>

<style>
.text {
  margin-top: 15px;
}
.figure {
  margin-top: 15px;
  border-radius: 20px;
}

.col-md-12 {
  background-color: rgb(52, 52, 52);
}

.colortxt {
  color: white;
}

.col-3 {
  margin-left: 120px;
}

p {
  font-family: Arial, Helvetica, sans-serif;
}

.border-dark{
  margin-top: 4px;
}


</style>
