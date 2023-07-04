<script>
  import { goto } from "$app/navigation";

  const handleClick = () => {
    console.log("Placing your order");
    goto("/products")
  }
</script>

<h1>Welcome to Home!</h1>

<a href="/about">About</a>
<a href="/products">Product Page</a>
<button on:click={handleClick}>Place Order</button>

<style>
 button {
    background-color: #264653;
    color: #fff;
    padding: 8px 18px;
    border-radius: 5px;
    border: none;
    cursor: pointer;
    margin-left: 10px;
 }
 a {
   margin-left: 10px;
   color: #000;
    text-decoration: none;
    font-size: 20px;
    
 }

</style>

