<template>
  <br>
  <div class="bg-white-200">
    <div class="grid grid-cols-4 gap-3">
      <div v-for="product in products" :key="product.id" class="flex flex-containe">
        
  <a href="#" class=" m-5 block max-w-sm p-6 bg-white border border-gray-200 rounded-lg shadow hover:bg-gray-100 dark:bg-gray-800 dark:border-gray-700 dark:hover:bg-gray-700">
    <span class="text-gray-600">#{{ product.id }}</span>
    <img class=" rounded-t-lg" :src="product.imageSrc" alt="product image" />
      <p class="mb-2 text-xl text-center font-bold tracking-tight text-red-600 dark:text-white">{{ product.name }}</p>
     <center><div class="flex">
        <button type="button" class="focus:outline-none text-white bg-green-700 hover:bg-green-800 focus:ring-4 focus:ring-green-300 font-medium rounded-lg text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-green-600 dark:hover:bg-green-700 dark:focus:ring-green-800">Green</button>
      <button type="button" class="focus:outline-none text-white bg-purple-700 hover:bg-purple-800 focus:ring-4 focus:ring-purple-300 font-medium rounded-lg text-sm px-5 py-2.5 mb-2 dark:bg-purple-600 dark:hover:bg-purple-700 dark:focus:ring-purple-900">Purple</button>
      </div></center> 
  </a>
  
      </div>
    </div>
  </div>
  
  
  </template>
  
  <script setup>
  const products = [
      {
        id: 1,
        name: 'Bulbasaurus',
        imageSrc: 'https://archives.bulbagarden.net/media/upload/f/fb/0001Bulbasaur.png',
      },
      {
        id: 2,
        name: 'Ivysaurus',
        imageSrc: 'https://id.portal-pokemon.com/play/resources/pokedex/img/pm/3245e4f8c04aa0619cb31884dbf123c6918b3700.png',
      },
      {
        id: 3,
        name: 'Venusaurus',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/003.png',
      },
      {
        id: 4,
        name: 'Charmander',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/004.png',
      },
      {
        id: 5,
        name: 'Bulbasaurus',
        imageSrc: 'https://archives.bulbagarden.net/media/upload/f/fb/0001Bulbasaur.png',
      },
      {
        id: 6,
        name: 'Ivysaurus',
        imageSrc: 'https://id.portal-pokemon.com/play/resources/pokedex/img/pm/3245e4f8c04aa0619cb31884dbf123c6918b3700.png',
      },
      {
        id: 7,
        name: 'Venusaurus',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/003.png',
      },
      {
        id: 8,
        name: 'Charmander',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/004.png',
      },
      {
        id: 9,
        name: 'Bulbasaurus',
        imageSrc: 'https://archives.bulbagarden.net/media/upload/f/fb/0001Bulbasaur.png',
      },
      {
        id: 10,
        name: 'Ivysaurus',
        imageSrc: 'https://id.portal-pokemon.com/play/resources/pokedex/img/pm/3245e4f8c04aa0619cb31884dbf123c6918b3700.png',
      },
      {
        id: 11,
        name: 'Venusaurus',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/003.png',
      },
      {
        id: 12,
        name: 'Charmander',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/004.png',
      },
      {
        id: 13,
        name: 'Charmander',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/004.png',
      },
      {
        id: 14,
        name: 'Charmander',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/004.png',
      },
      {
        id: 15,
        name: 'Charmander',
        imageSrc: 'https://assets.pokemon.com/assets/cms2/img/pokedex/full/004.png',
      },
      
      // More products...
    ]
  </script>