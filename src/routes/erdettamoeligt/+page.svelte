<script>
    let alfons = 1

</script>
<button 
    class="knapp1"
    on:click={() => {
        alfons = alfons* 2;
        if (alfons > 1000){
            window.open(
                "https://www.youtube.com/watch?v=dQw4w9WgXcQ", "_blank");
        } 
        

    }}


>
</button>

<p>{alfons}</p>

<style>
    p {
        color:brown;
    }

    .knapp1{
        width: 20%;
        height: 100px;
        background-color: green;
    }


</style>