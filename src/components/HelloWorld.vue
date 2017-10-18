<template>
  <div class="hello">
   
    <div v-for="(data, index) in msg">
      <h1> Ini umur {{ data.nama }} yang ke {{ data.umur }} di index {{ index }} </h1>
    </div>

    <button @click="buttonClick">Click Me</button>
    <button @click="unClick">UnClick</button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data: function () {
    return {
      msg: [
            {
              'nama':'asqo',
              'umur':'24'
            }
          ]
    }
  },
  methods: {
    buttonClick() {
      this.msg = [
        {
          'nama':'asqo',
          'umur':'24',
        },
        {
          'nama':'sumay',
          'umur':'24',
        },
        {
          'nama':'utun',
          'umur':'24',
        },
      ]
    },
    unClick(){
      this.msg = [{
              'nama':'asqo',
              'umur':'24'
            }]
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
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
