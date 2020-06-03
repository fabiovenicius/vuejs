<template>
  <div class="pill">
    <span class="name"> {{ name}}  </span>
    <span class="amount"> {{ amount}}  </span>

  </div>
</template>

<script>
export default {
    props:['name','amount']
}
</script>

<style scoped>
    .pill{
        margin: 10px;
        height: 55px;
        border-radius: 30px;

        background-color: rgb(233, 29, 29);
        color: #ffffff;
        font-size: 1.3 rem;
        font-weight: bold;

        display:flex;
        align-items: center;

    }

    .pill .name{
      margin-left: 15px;      
    }

    .pill .amount{
        margin: 10px;
        padding: 5px;
        height: 35px;
        width: 35px;
        border-radius: 18px;

        background-color: #fff;
        color: #dc143c;
        display: flex;
        justify-content: center;
        align-items: center;

        font-size: 12px;
        

    }


</style>