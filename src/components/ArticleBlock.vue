<script>
export default {};
</script>
<template>
  <Article class="bloco-resultado">
    <div class="resultado">Resultado</div>
    <div class="nota">
      <div class="nota-titulo">Você tirou</div>
      <p>você combina com um estilo atual, de preferência com referências de cultura pop e internet. Você não vê
        problema nenhum em usar o que está na moda, muito pelo contrário: esse tipo de look casa muito bem sua
        personalidade e as pessoas já esperam ver você usando tudo o que for hype no momento.</p>
    </div>
    <div class="botoes">
      <button>Refazer</button>
      <button>Exemplo</button>
    </div>

  </Article>
</template>

<style>
.bloco-resultado {
  width: 500px;
  /* height: 300px; */
  border: 1px solid rgb(0, 0, 0);
  border-radius: 15px;
  padding: 20px;
  margin: 10px;

  display: flex;
  flex-direction: column;
  align-items: center;
}

.bloco-resultado .resultado {
  background-color: #c4c4c4;
  border-radius: 50px;
  width: 60%;
  padding: 15px;
  font-weight: bolder;
  text-align: center;
}

.bloco-resultado .nota {
  background-color: #c4c4c4;
  border-radius: 10px;
  width: 80%;
  padding: 15px;
  margin: 30px 0;
}

.nota-titulo {
  text-align: center;
  font-weight: bolder;
}

.bloco-resultado .botoes {
  display: flex;
  justify-content: space-between;
  background-color: #c4c4c4;
  border-radius: 10px;
  padding-top: 8px;
  padding-bottom: 8px;
  padding-left: 20px;
  width: 60%;
}

.botoes button {
  background-color: black;
  color: white;
  font-weight: bold;
  font-size: 1.2em;
  border-radius: 10px;
}
</style>
