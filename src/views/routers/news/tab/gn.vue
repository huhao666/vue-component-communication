<template>
 <div>
    国内新闻信息：<br/>
     <ul >
       <li v-for="(result, index) in list" :key="index">{{result.name}}{{index}}</li>
     </ul>
 </div>
</template>
<script>
 export default {
  data(){
   return {
     list: [
      {name:'国内新闻信息'},
      {name:'国内新闻信息'}
     ]
   }
  }
 }
</script>