<template>
  <div class="flex min-h-screen bg-gray-100 dark:bg-gray-800">

    <aside class="w-80 bg-white dark:bg-gray-800 shadow-md">
      <div class="p-6 text-lg font-bold text-gray-700 dark:text-gray-200">
        SideBar 
      </div>
    </aside>

    <main class="flex-1 p-10">
      <div class="overflow-x-auto rounded-lg shadow-md">
        <table class="w-full text-sm text-left rtl:text-gray-700 dark:text-gray-300">
          <thead class="text-xs text-white uppercase bg-blue-600 dark:bg-blue-800">
            <tr>
              <th scope="col" class="px-10 py-5 border-r border-blue-400 dark:border-blue-700 py-5">ID</th>
              <th scope="col" class="px-10 py-5 border-r border-blue-400 dark:border-blue-700 py-5">Nome</th>
              <th scope="col" class="px-10 py-5 border-r border-blue-400 dark:border-blue-700 py-5">Preço</th>
              <th scope="col" class="px-10 py-5 border-r border-blue-400 dark:border-blue-700 py-5">Categoria</th>
              <th scope="col" class="px-10 py-5 border-r border-blue-400 dark:border-blue-700 py-5">Quantidade Venda</th>
            </tr>
          </thead>
        </table>
      </div>
    </main>
  </div>
</template>
