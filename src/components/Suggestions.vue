<template>
  <div class="suggestions">
      <h1>Looking for music?</h1>
      <span>Pick up your recently played right where you left off.</span>
      <button type="button" class="btn sug__btn">launch web player</button>
  </div>
</template>

<script>
export default {
    name: 'Suggestions'
}
</script>

<style>
    .suggestions {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        margin-top: 80px;
    }
    .suggestions>h1 {
        font-size: 3em;
    }
    .suggestions>span {
        margin-top: 10px;
    }
    .sug__btn
    {
        background-color: #fff;
        color:#616467;
        /* border: none; */
        border: 2px solid #616467;
        width: 20%;
        padding: 15px;
        font-size: 15px;
        margin-bottom: 50px;
    }
    .sug__btn:hover{
        background-color: #616467;
        color: #fff;
    }
</style>