<script lang="ts">
    //引数→props
    export let productTitle:string;
    export let productLink:string;
    export let productUrl:string;
    export let color:string; 
</script>

<div class={`bg-${color}-200 m-1 py-2`}>
    <h1>{productTitle}</h1>
    <a href="{productUrl}">{productLink}</a>
</div>