<!--This is the top part of the website, the header.-->
<header>
This is a header
</header>
<script>
let greeting = $state ("Hello"); //The greeting starts off as "Hello"
</script>

<div>
    <h1>{greeting}</h1>
    <h2>What do you want to write?</h2>
<!--The writing the user inputs shows on the H1-->
    <input type = "text" bind:value={greeting}>
    </div>

<!--This is the bottom part of the website, the footer.-->
<footer>This is a footer</footer>

<style>
/*The div is configured to show all elements in the center in a column*/
div{
    display: flex;
    align-items: center;
    flex-direction: column;
}
/*The text the user inputs is larger and in a different color from the h2*/
h1{
    color: rgb(51, 181, 221);
    font-size: 50px;
}
/*Both the header and the footer are as wide as the website and the text is aligned to be centered.*/
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