<script>
export default {
data(){
    return{
     items: [{
        stock: 'hellow',
        number: 25
     },
     {
        stock: 'mellow',
        number: 25
    }
]
  }
}
}
</script>
<template>
    <WelcomeItem>
      <template #icon>
      </template>
      <template #heading>Workshop 1 is happeningng</template>
          <table>
            <li v-for="item in items">
             {{ item.stock }} {{ item.number }}
            </li>
          </table>
    </WelcomeItem>
    </template>
       