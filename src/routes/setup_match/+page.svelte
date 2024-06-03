<script>
    import FormSetup from "$lib/setupMatch/formSetup.svelte";

</script>


<div class="grid md:grid-cols-2 gap-6 sm:grid-cols-12">

<FormSetup type="home" />
<FormSetup type="away"/>

</div>
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded mx-auto mt-5">
    Setup match
</button>
