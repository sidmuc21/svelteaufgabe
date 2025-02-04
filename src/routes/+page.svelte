<header>
This is a header
</header>
<script>
let greeting = $state ("Hello");
</script>

<div>
    <h1>{greeting}</h1>
    <h2>What do you want to write?</h2>
    <input type = "text" bind:value={greeting}>
    </div>

<footer>This is a footer</footer>

<style>
div{
    display: flex;
    align-items: center;
    flex-direction: column;
}
h1{
    color: rgb(51, 181, 221);
    font-size: 50px;
}
header, footer{
    width: 100vw;
    background-color: rgb(115, 115, 194);
    padding-top: 50px;
    padding-bottom: 50px;
    font-size: 30px;
    text-align: center;
    color: rgb(235, 237, 255);
}

footer{
  position: fixed;
  left: 0;
  bottom: 0;
}
</style>