<script>
	import Product from './Product.svelte';
</script>

<Product
	productTitle="A Book"
 on:add-to-cart={() => alert('Add to Cart')}
 on:delete={() => alert('Delete')}
 />


