<template>
    <section class="py-16 bg-gray-900">
      <div class="max-w-4xl mx-auto text-center">
        <h2 class="text-3xl font-bold mb-8">Pengalaman Project</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-8">
          <PortfolioItem v-for="project in projects" :key="project.id" :project="project" />
        </div>
      </div>
    </section>
  </template>
  
  <script setup>
  import { reactive } from 'vue';
  import PortfolioItem from './PortofolioItem.vue';
  
  const projects = reactive([
    { id: 1, title: 'RESTful API – CRUD Menggunakan HapiJS ', description: 'RESTful API untuk sistem manajemen produk menggunakan NodeJS dan HapiJS, dan dirancang untuk mendukung operasi CRUD (Create, Read, Update, Delete)', link: 'https://github.com/muhamadrofii/belajarBackendKelasMenengahDicoding' },
    { id: 2, title: 'Wallet Ethereum Generator', description: '•	Membuat wallet Ethereum dan menampilkan Mnemonic Phrase, Private Key, dan Address.', link: 'https://github.com/muhamadrofii/multipleWallet-EtherJS' },
    { id: 3, title: 'RESTful API – Sistem Manajemen Bank Sampah - ExpressJS ', description: 'RESTful API untuk aplikasi bank sampah menggunakan ExpressJS. API ini mendukung pengelolaan data, dan transaksi bank sampah', link: 'https://github.com/muhamadrofii/backendBankSampah' }
  ]);
  </script>
  