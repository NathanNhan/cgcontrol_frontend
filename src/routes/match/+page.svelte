<script>
    import TagNavigation from "$lib/bongda/TagNavigation.svelte";
    import SettingScore from "$lib/bongda/settingScore.svelte";

    
</script>

<TagNavigation />

<section class="statistic_biggoal mb-5 mt-5">
    <div class="grid grid-cols-2 gap-3">
        <div>
            <table class="w-full">
                <thead>
                    <tr
                        class="text-md font-semibold tracking-wide text-left text-gray-900 bg-green-100 uppercase border-b border-gray-600"
                    >
                        <th class="px-4 py-3">Goal</th>
                        <th class="px-4 py-3">Time</th>
                    </tr>
                </thead>
                <tbody class="bg-white">
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Phạm Minh Thành (25)</p>
                                </div>
                            </div></td
                        >
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >2</td
                        >
                    </tr>
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Bùi Tấn Trường (10)</p>
                                </div>
                            </div>
                        </td>
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >5</td
                        >
                    </tr>
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Lê Quang Đức (6)</p>
                                </div>
                            </div>
                        </td>
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >1</td
                        >
                    </tr>
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Lê Quang Khải (15)</p>
                                </div>
                            </div>
                        </td>
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >30</td
                        >
                    </tr>
                </tbody>
            </table>
        </div>

        <div>
            <table class="w-full">
                <thead>
                    <tr
                        class="text-md font-semibold tracking-wide text-left text-gray-900 bg-red-100 uppercase border-b border-gray-600"
                    >
                        <th class="px-4 py-3">Goal</th>
                        <th class="px-4 py-3">Time</th>
                    </tr>
                </thead>
                <tbody class="bg-white">
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Bùi Tiến Dũng (7)</p>
                                </div>
                            </div></td
                        >
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >12</td
                        >
                    </tr>
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Công Phượng (9)</p>
                                </div>
                            </div>
                        </td>
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >15</td
                        >
                    </tr>
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Lê Quang Trường (16)</p>
                                </div>
                            </div>
                        </td>
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >2</td
                        >
                    </tr>
                    <tr class="text-gray-700">
                        <td class="px-4 py-3 border">
                            <div class="flex items-center text-sm">

                                <div>
                                    <p class="font-semibold text-black">Tuấn Khải (8)</p>
                                </div>
                            </div>
                        </td>
                        <td class="px-4 py-3 text-ms font-semibold border"
                            >3</td
                        >
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
</section>



<SettingScore />



<section class="statistic_match mt-5 bg-white p-3 py-5 rounded">
    <h4 class="text-xl font-bold dark:text-white pb-3">Thống kê trận đấu</h4>
    <div class="flex flex-col gap-5">
        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">STATS 1</button>
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">STATS 2</button>
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">STATS 3</button>
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">STATS 4</button>
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">STATS 5</button>
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <div
        class="w-12 h-12 flex flex-col items-center ml-5 justify-center bg-slate-200 rounded-full shadow-lg hover:cursor-pointer hover:shadow-xl hover:bg-slate-300 hover:scale-105"
      >
        <svg
          stroke="currentColor"
          fill="currentColor"
          stroke-width="0"
          viewBox="0 0 448 512"
          class="text-slate-500"
          height="1em"
          width="1em"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48z"
          >
          </path>
        </svg>
      </div>
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
        </div>

        <div class="flex gap-5 flex-wrap">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
            <input type="text" class="border border-gray-300 text-gray-900 text-sm rounded-lg">
            <input type="number" class="w-16 border border-gray-300 text-gray-900 text-sm rounded-lg" min="1">
        </div>

        <div class="flex flex-wrap gap-5">
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Load</button>
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Save</button>
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Reset</button>
            <button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">Thống kê chung</button>
            <div
        class="w-12 h-12 flex flex-col items-center justify-center bg-slate-200 rounded-full shadow-lg hover:cursor-pointer hover:shadow-xl hover:bg-slate-300 hover:scale-105"
      >
        <svg
          stroke="currentColor"
          fill="currentColor"
          stroke-width="0"
          viewBox="0 0 448 512"
          class="text-slate-500"
          height="1em"
          width="1em"
          xmlns="http://www.w3.org/2000/svg"
        >
          <path
            d="M400 32H48C21.5 32 0 53.5 0 80v352c0 26.5 21.5 48 48 48h352c26.5 0 48-21.5 48-48V80c0-26.5-21.5-48-48-48z"
          >
          </path>
        </svg>
      </div>
        </div>

    </div>
</section>


