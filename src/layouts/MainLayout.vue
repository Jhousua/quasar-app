<template>
  <q-layout view="hHh lpR fFf">
    <q-header bordered class="nav-bar bg-black text-white flex justify-between">
      <div class="q-px-xl self-center">
        <q-toolbar class="">
          <q-toolbar-title class="">
            <q-avatar class="">
              <img
                src="https://cdn.quasar.dev/logo-v2/svg/logo-mono-white.svg"
              />
            </q-avatar>
            Jhous
          </q-toolbar-title>
        </q-toolbar>
      </div>
      <div class="self-center q-pr-xl">
        <q-btn-group class="q-gutter-xl q-pr-xl" flat>
          <q-btn label="Home" />
          <q-btn label="About" />
          <q-btn label="Portfolio" />
          <q-btn label="Contact" />
        </q-btn-group>
      </div>
    </q-header>

    <q-page-container>
      <router-view />

      <router-view name="about"></router-view>
    </q-page-container>
  </q-layout>
</template>
