<script>
  import { onMount, onDestroy } from "svelte";
  import products from "../../stores/products-store";
</script>

<h1>Hello</h1>
{#each $products as product}
  <h2>{product.title}</h2>
{/each}
