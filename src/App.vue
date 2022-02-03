<template>
  <q-layout view="hHh lpR fFf">
    <Header />

    <q-page-container mt-3>
      <transition
        appear
        mode="out-in"
        enter-active-class="animate__animated animate__fadeIn"
        leave-active-class="animate__animated animate__fadeOut"
      >
        <router-view />
      </transition>
    </q-page-container>

    <Footer />
  </q-layout>
</template>
