<template>
  <div>
    <!-- change nullish to logical or
      because param id is always povided in optional param -->
    <h1>Selamat Datang {{ $route.params.id || 'User' }}</h1>
  </div>
</template>
