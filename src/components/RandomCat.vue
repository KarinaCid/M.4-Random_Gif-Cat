<template>
  <div>
    <h1>{{ msg }}</h1>
    <form>
      <div class="form__input-container">
        <div class="row form-group">
          <div class="col-6 d-flex flex-column align-items-end">
            <label for="text">Titulo</label>
            <label for="text">Filtro</label>
            <label for="text">Color</label>
            <label for="text">Tamaño</label>
          </div>
          <div class="col-6 d-flex flex-column align-items-start">
            <input type="text" />
            <select name="" id=""></select>
            <select name="" id=""></select>
            <input type="text" name="" id="" />
          </div>
        </div>
      </div>

      <input type="submit" value="obtener mi gato" />
    </form>
  </div>
</template>

<script>
export default {
  name: "Random Gif Cat",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
h1 {
  font-size: 2em;
  font-weight: 700;
  text-align: center;
  padding: 2em 0 1em;
}
.form__input-container {
  background-color: lightcoral;
}
.form__input-group {
  margin: 1em;
  text-align: left;
}
</style>
