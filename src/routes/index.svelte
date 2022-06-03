<script>

    //相対パス
    import ProductCard from "../components/ProductCard.svelte";

    const dataList = [

{

productTitle: "Product 1",
productLink: "Product 1",
productUrl: "Product 1",
color: "red"

},

{

productTitle: "Product 2",
productLink: "Product 2",
productUrl: "Product 2",
color: "blue"

},

{

productTitle: "Product 3",
productLink: "Product 3",
productUrl: "Product 3",
color: "green"

},

{

productTitle: "Product 4",
productLink: "Product 4",
productUrl: "Product 4",
color: "yellow"

},

{

productTitle: "Product 5",
productLink: "Product 5",
productUrl: "Product 5",
color: "gray"

},

]

</script>

<title>profile</title>
<div class="text-center mt-10 bg-slate-00" >
    <h1 class="text-3xl bg-black text-lime-400">かかって来いって</h1>
    <p class="pt-3 bg-stone-400">
        20才 専門学生<br>
        毎日必死に生きてます
    </p>

    {#each dataList as data}
    <ProductCard
    productTitle = {data.productTitle} 
    productLink = {data.productLink} 
    productUrl = {data.productUrl} 
    color ={data.color}
    />
    {/each}
    <!--
    <ProductCard 
    productTitle="シーザーサラダ" 
    productLink = "レシピ" 
    productUrl = "https://park.ajinomoto.co.jp/recipe/card/706494/" 
    color = "green"
    />
    <ProductCard
    productTitle="チョレギサラダ" 
    productLink = "レシピ" 
    productUrl = "https://cookpad.com/recipe/5646339" 
    color = "slate"
    />
    -->
</div>


<a href="https://www.disneyplus.com/ja-jp/home" target="_blank" >新井</a><br>
<a href="/page2" class="text-red-600">Page2</a>

