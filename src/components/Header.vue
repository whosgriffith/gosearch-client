<template>
<header class="ml-32 mt-3">
<div class="flex justify-start pt-8">
  <h1 class="text-3xl font-bold text-neutral-50">
    GoSearch
  </h1>
  <div class="mb-3 xl:w-96 pl-12">
    <div class="relative mb-4 flex w-full flex-wrap items-stretch">
      <input
          type="search"
          class="relative m-0 -mr-px block w-[1%] min-w-0 flex-auto rounded-l border border-solid border-slate-700 bg-slate-800 bg-clip-padding px-3 py-1.5 text-base font-normal text-neutral-50 outline-none transition duration-300 ease-in-out focus:border-primary focus:text-slate-600 focus:shadow-te-primary focus:outline-none focus:bg-gray-200 placeholder:text-neutral-400"
          placeholder="Search"
          aria-label="Search"
          aria-describedby="button-addon1" />
      <button
          class="relative z-[2] flex items-center rounded-r bg-slate-600 hover:bg-slate-300 px-6 py-2.5 text-xs font-medium uppercase leading-tight text-white shadow-md transition duration-150 ease-in-out"
          type="button"
          id="button-addon1"
          data-te-ripple-init
          data-te-ripple-color="light">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20" fill="black" class="h-5 w-5">
          <path fill-rule="evenodd" d="M9 3.5a5.5 5.5 0 100 11 5.5 5.5 0 000-11zM2 9a7 7 0 1112.452 4.391l3.328 3.329a.75.75 0 11-1.06 1.06l-3.329-3.328A7 7 0 012 9z" clip-rule="evenodd" />
        </svg>
      </button>
    </div>
  </div>
</div>
</header>
</template>
