<template>
  <div class="flex flex-col md:basis-[45%] lg:basis-[45%] justify-evenly">
    <div class="flex flex-wrap flex-row">
      <button
        style="background-color: var(--color-primary)"
        class="w-36 h-8 rounded-full mr-4 mb-4"
      >
        SHOP NOW
      </button>
      <button
        style="background-color: var(--color-secondary); color: darkblue"
        class="w-36 h-8 blue bg-yellow-200 rounded-full mr-4 mb-4"
      >
        SHOP NOW
      </button>
      <button
        style="background-color: var(--color-secondary-one); color: darkblue"
        class="w-36 h-8 bg-pink-300 rounded-full mr-4 mb-4"
      >
        SHOP NOW
      </button>
      <button
        style="background-color: var(--color-secondary-two)"
        class="w-36 h-8 bg-teal-500 rounded-full mr-4 mb-4"
      >
        SHOP NOW
      </button>
    </div>
    <h1
      class="text-sky-400 font-extrabold max-w-screen-sm mb-3 text-lg text-gray-500 md:text-xl dark:text-gray-400"
    >
      vs
    </h1>

    <div class="flex flex-wrap">
      <div class="mb-4 mr-8">
        <label
          class="block text-gray-700 text-sm font-bold mb-2"
          for="username"
        >
          Email
        </label>
        <div class="flex flex-row">
          <input
            class="shadow appearance-none border rounded w-full py-2 px-3 text-gray-700 leading-tight focus:outline-none focus:shadow-outline"
            id="username"
            type="text"
            placeholder="Your email here"
          />
          <button
            style="background-color: var(--color-primary)"
            class="w-32 h-10 rounded-md mr-4"
          >
            subscribe
          </button>
        </div>
      </div>
      <div class="mb-6">
        <label class="block text-gray-700 text-sm font-bold mb-2" for="message">
          Message
        </label>
        <input
          class="shadow appearance-none border border-red-500 rounded w-full py-2 px-3 text-gray-700 mb-3 leading-tight focus:outline-none focus:shadow-outline"
          id="message"
          type="text"
          placeholder="your message here"
        />
      </div>
    </div>
  </div>
</template>
