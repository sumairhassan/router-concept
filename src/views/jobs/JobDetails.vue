<template>
  <h1>Job Details Page</h1>
  <p>The job id is {{ id }}</p>
</template>

<script>
export default {
    props: ['id'],
    // use props or data function, both are same in this case.
    //data(){
     //   return{
       //     id: this.$route.params.id
        //}
    // }

}
</script>

<style>

</style>