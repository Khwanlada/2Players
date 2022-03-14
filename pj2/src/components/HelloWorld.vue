<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <br>
    <p>Please indicate which type of user you are</p>
    <br>
    <ul>
    <!-- 1 Customer -->
    <div class="d-flex justify-content-center align-items-center">
      <div class="btn-outline-white">
        <a
          href="https://khwanlada.github.io/C-Walk/form2.html"
          button
          type="button"
          class="btn btn-sm btn-outline-dark"
          > Customer </a>
        &nbsp; &nbsp; 
      <!-- </div>
    </div> -->
    <!-- <br> -->
    <!-- 2 Kitchen -->
    <!-- <div class="d-flex justify-content-center align-items-center"> -->
      <!-- <div class="btn-outline-dark"> -->
        <a
          href="https://khwanlada.github.io/C-Walk/form2.html"
          button
          type="button"
          class="btn btn-sm btn-outline-dark"
          > Kitchen </a
        >
      </div>
    </div>
    </ul>
    
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
      crossorigin="anonymous"
    />
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
