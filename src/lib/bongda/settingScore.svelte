<section class="clock_tsnho bg-white p-5 rounded mb-5">
  <div class="flex flex-wrap -mx-3 mb-6">
    <div class="flex flex-wrap justify-between px-3 mt-5 gap-3">
      <div class="flex items-center">
        <input
          id="email"
          name="notification-method"
          type="radio"
          checked
          class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"
        />
        <label
          for="email"
          class="ml-1 block text-sm font-medium leading-6 text-gray-900"
          >Hiệp 1</label
        >
      </div>
      <div class="flex items-center">
        <input
          id="sms"
          name="notification-method"
          type="radio"
          class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"
        />
        <label
          for="sms"
          class="ml-1 block text-sm font-medium leading-6 text-gray-900"
          >Hiệp 2</label
        >
      </div>
      <div class="flex items-center">
        <input
          id="push"
          name="notification-method"
          type="radio"
          class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"
        />
        <label
          for="push"
          class="ml-1 block text-sm font-medium leading-6 text-gray-900"
          >Hiệp 3</label
        >
      </div>

      <div class="flex items-center">
        <input
          id="email"
          name="notification-method"
          type="radio"
          checked
          class="h-4 w-4 border-gray-300 text-indigo-600 focus:ring-indigo-600"
        />
        <label
          for="email"
          class="ml-1 block text-sm font-medium leading-6 text-gray-900"
          >Hiệp 4</label
        >
      </div>
    </div>
  </div>

  <div class="flex flex-wrap -mx-3 mb-6 gap-1">
    <div class="flex flex-col px-3">
      <button
        type="button"
        class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
        >Bắt đầu</button
      >
    </div>

    <div class="flex flex-col px-3">
      <button
        type="button"
        class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
        >Kết thúc</button
      >
    </div>
  </div>

  <div class="flex flex-wrap -mx-3 mb-6 gap-3">
    <div class="flex flex-col items-center px-3">
      <label
        for="email"
        class="ml-1 block text-sm font-medium leading-6 text-gray-900"
        >Home</label
      >
      <input
        id="home_red_card"
        name="notification-method"
        type="number"
        checked
        class=" w-14 h-6 border-gray-300 text-indigo-600 focus:ring-indigo-600"
        value="0"
      />
    </div>

    <div class="flex flex-col items-center px-3">
      <label
        for="email"
        class="ml-1 block text-sm font-medium leading-6 text-gray-900"
        >Away</label
      >
      <input
        id="away_red_card"
        name="notification-method"
        type="number"
        checked
        class=" w-14 h-6 border-gray-300 text-indigo-600 focus:ring-indigo-600"
        value="0"
      />
    </div>

    <div class="relative flex items-end">
      <div class="flex h-6 items-center">
        <input
          id="offers"
          aria-describedby="offers-description"
          name="offers"
          type="checkbox"
          class="h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600"
        />
      </div>
      <div class="ml-3 text-sm leading-6">
        <label for="offers" class="font-medium text-gray-900"
          >Show Red Card</label
        >
      </div>
    </div>

    <div class="relative flex items-end px-3">
      <div class="flex h-6 items-center mr-3">
        <select name="" id="" class="w-32 h-10">
          <option value="" selected>Bù giờ</option>
          <option value="">+5</option>
          <option value="">+10</option>
          <option value="">+6</option>
        </select>
      </div>

      <div class="flex h-6 items-center">
        <input
          id="offers"
          aria-describedby="offers-description"
          name="offers"
          type="checkbox"
          class="h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600"
        />
      </div>
      <div class="ml-3 text-sm leading-6">
        <label for="offers" class="font-medium text-gray-900">Hiện bù giờ</label
        >
      </div>

      <div
        class="ml-3 w-12 h-12 flex flex-col items-center justify-center bg-slate-200 rounded-full shadow-lg hover:cursor-pointer hover:shadow-xl hover:bg-slate-300 hover:scale-105"
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

  <div class="flex flex-wrap -mx-3 mb-6 gap-3 px-3">
    <button
      type="button"
      class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
      >Tỉ số nhỏ</button
    >
    <div
      class="ml-3 w-12 h-12 flex flex-col items-center justify-center bg-slate-200 rounded-full shadow-lg hover:cursor-pointer hover:shadow-xl hover:bg-slate-300 hover:scale-105"
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



  <div class="flex flex-wrap -mx-3 mb-6 gap-3 px-3">
    <button
      type="button"
      class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-lg text-sm px-5 py-2.5 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800"
      >Kick off</button
    >
    <div
      class="ml-5 w-12 h-12 flex flex-col items-center justify-center bg-slate-200 rounded-full shadow-lg hover:cursor-pointer hover:shadow-xl hover:bg-slate-300 hover:scale-105"
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

  <div class="flex flex-wrap -mx-3 justify-center">
    <button class="bg-green-500 hover:bg-green-700 text-white font-bold py-2 px-4 rounded">
      BackGroundMatch
    </button>
  </div>
</section>
