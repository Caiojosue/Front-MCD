<template>
  <body class="bg-gray-100">

    <aside class="fixed top-0 left-0 h-full w-72 bg-yellow-400 border-r border-yellow-300 shadow-lg z-50">
      <div class="p-6">
        <h2 class="text-2xl font-extrabold text-black">Mercado Livre</h2>
      </div>

      <div class="px-4 pb-6">
        <form action="" class="flex gap-2">
          <input
            type="text"
            placeholder="Pesquisar"
            class="flex-1 px-3 py-2 border border-yellow-300 rounded-lg text-sm focus:outline-none focus:ring-2 focus:ring-yellow-600 text-black placeholder-gray-700 bg-white"
          />
          <button
            type="submit"
            class="bg-white hover:bg-gray-100 text-yellow-600 px-4 py-2 rounded-lg text-sm transition font-semibold border border-yellow-600"
          >
            Buscar
          </button>
        </form>
      </div>

      <nav class="px-4 space-y-2 text-black">
        <router-link
          to="/main"
          class="flex items-center gap-3 px-4 py-3 rounded-lg hover:bg-yellow-300 transition"
        >
          <svg
            class="w-5 h-5 text-black"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
              d="M3 9.75L12 4.5l9 5.25v7.5a2.25 2.25 0 01-2.25 2.25H5.25A2.25 2.25 0 013 17.25v-7.5z" />
          </svg>
          <span class="text-sm font-semibold">Produtos</span>
        </router-link>

        <a
          href="/categoria"
          class="flex items-center gap-3 px-4 py-3 rounded-lg hover:bg-yellow-300 transition"
        >
          <svg
            class="w-5 h-5 text-black"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
              d="M4.5 6.75h15m-15 4.5h15m-15 4.5h15" />
          </svg>
          <span class="text-sm font-semibold">Categorias</span>
        </a>

        <a
          href="#"
          class="flex items-center gap-3 px-4 py-3 rounded-lg hover:bg-yellow-300 transition"
        >
          <svg
            class="w-5 h-5 text-black"
            xmlns="http://www.w3.org/2000/svg"
            fill="none"
            viewBox="0 0 24 24"
            stroke="currentColor"
          >
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
              d="M12 4.5v15m7.5-7.5h-15" />
          </svg>
          <span class="text-sm font-semibold">Dashboard</span>
        </a>
      </nav>
    </aside>
  </body>
</template>
