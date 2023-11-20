<script>
  //props
  export let initialCount;
  export let max;
let count=initialCount;
let string=""
$:{
  string=`the count is ${count}`
}

</script>
<button on:click={()=>{
    if(count<max) 
  count++
}}>
enzelnii </button>
<h1>{count}</h1>
<h2>{string}</h2>
<style>
  button{
    padding: 1%;
  }
</style>