<template lang="pug">
  .container
    .row
      .col-6.text-primary Hello Vue World with
      .col-6.text-primary Pug and Bootstrap 
</template>

<script>
//- Create a Markdown editor, like the above, that has the following components:

//- Input area
//- Compilation logic (you can use a library for this)
//- Preview panel (no need to do live preview, using a submit button is fine)
//- Also, you should try to have a good stylesheet for the output HTML (you can use something like Bootstrap, Bulma, etc.)

export default {
  name: "MarkDownEditor",
  props: {
    msg: String
  }
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
