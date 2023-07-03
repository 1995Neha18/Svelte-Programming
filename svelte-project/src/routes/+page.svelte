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

