<template>
  <div class="products">
    <h1>{{ msg }}</h1>

    <ul v-for="item in products">
      <li>{{ item.name }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      msg: 'Products',
      products: [
        {
          id: 5,
          name: 'Apple iPhone 7',
          description: 'Learn COBOL with this vintage programming book',
          price: 699
        },
        {
          id: 4,
          name: 'Apple iPhone 7 Plus',
          description: 'Learn COBOL with this vintage programming book',
          price: 799
        },
        {
          id: 3,
          name: 'Apple iPhone 6',
          description: 'Learn COBOL with this vintage programming book',
          price: 599
        },
        {
          id: 2,
          name: 'Apple iPhone 6 Plus',
          description: 'Learn COBOL with this vintage programming book',
          price: 699
        },
        {
          id: 1,
          name: 'Macbook Pro 13\'',
          description: 'Learn COBOL with this vintage programming book',
          price: 1699
        }
      ]
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
