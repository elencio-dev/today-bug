<div class="max-w-2xl mx-auto p-2 space-y-4">
    <h1 class="text-3xl font-bold underline mt">TodayBug</h1>
    <strong class="mt-2">
        Compartilha seus bugs diários de codigo, se tiver resolvido mostra como resolveu o erro e qual foi a sensação!!
    </strong
 >

 <form action="" class="flex flex-col space-y-4">
    <input 
    type="text" 
    placeholder="write something about bug and share your daily stress"
    class="p-2 rounded border border-gray-500 focus:border-gray-400 mt-2"
    >
    <div class="flex flex-col gap-2">
        <!-- svelte-ignore a11y_label_has_associated_control -->
        <label >Faça upload da sua imagem</label>
        <input 
        type="file" 
        alt="Image of the interface error"
        />
    </div>
    

    <input  
    type="text" 
    placeholder="Write the code error here!!" 
    class="p-2 rounded border border-gray-500 focus:border-gray-400"
    />
    <button class="p-4 bg-yellow-500 text-gray-900 font-bold">
        submit
    </button>
 </form> 
</div>


<style lang="postcss">
    :global(html) {
        background-color: theme(colors.gray.100);
        font-family: "Open Sans", sans-serif;
    }
</style>
