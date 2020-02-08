<template>
  <div id="app">
    <FirstPage />
    {{orders.title}}
  </div>
</template>

<script>
import FirstPage from './components/Pages.vue'

export default {
  name: 'app',
  data () {
    return {
      orders: null
    }
  },
  created(){
    fetch("./data.json")
            .then(response=>response.json())
            .then(response=>{
              this.orders=response;
            })
            // .then(function (info) {
            //   // eslint-disable-next-line no-console
            //   console.log(info.title);
            // })
            // eslint-disable-next-line no-console
            .catch(error=> console.error(error));

  },
  components: {
    FirstPage
  }
}
</script>

<style>
#app {
  font-family: DejaVu Sans;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

}
section{
 width: 100%;
  position: relative;
}
.landscape{
  max-width: 1122px !important;
  min-height: 794px !important;
}
.flex{
  display: flex;
}
.j-cc{
  justify-content: center;
}
.a-ic{
  align-items: center;
}
.text-ac{
  text-align: center;
}
.text-al{
  text-align: left;
}
.page{
  box-shadow: 0 0 0.5cm rgba(0, 0, 0, 0.5);
  min-height: 29.7cm;
  margin-bottom: 75px;
  padding: 10px 20px;
  max-width: 790px;
  margin:58px auto;
  box-sizing: border-box;
  outline-style: none;
}
.btn{
  background: #42b983;
  border: none;
  color: white;
  font-size: 15px;
  font-family: inherit;
  font-weight: bold;
  padding: 10px 20px;
  position: fixed;
  top: 0;
  cursor: pointer;
}
.btn:hover{
  color: gray;
}
p{
padding: 0;
  margin: 0;
}
  .cols{
    display: flex;
  }
  .col{
    flex: 1;
  }
span{
  display: block;
}
</style>
