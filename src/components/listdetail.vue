<template>
  <div class="container">
   
    <router-link to="/product">뒤로가기</router-link>
    <h2>listdetail</h2>
      <div >
          <h3>{{listData[$route.params.id].title}}</h3>
          <p>{{listData[$route.params.id].content}}</p>
      </div>
  </div>
</template>

<script>
export default {
    name:'detail',
    props:['listData']
}
</script>

<style>

</style>