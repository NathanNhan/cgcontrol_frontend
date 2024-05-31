
<script>
    export let title = "";
    export let src = "";
    export let name = "";
</script>





<a href="bongda/1" class="hover:no-underline">
    <div class="p-2 sm:p-10 text-center">
        <h2 class="text-2xl font-bold leading-7 text-gray-900 sm:truncate sm:text-2xl sm:tracking-tight">{title}</h2>
        <div
            style="height: 200px;"
            class="flex justify-center items-center max-w-sm rounded overflow-hidden shadow-lg hover:bg-white bg-white"
        >
            <div class="space-y-10">
                <div class="px-6 py-4">
                    <div class="px-10 max-w-2xl">
                        <img
                            class="w-20 h-20 m-auto"
                            src={src}
                            alt="Liverpool"
                        />
                    </div>
                    <div class="space-y-5">
                        <div class="font-bold text-xl mb-2">
                            {name}
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</a>