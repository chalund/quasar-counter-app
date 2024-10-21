<template>
  <q-page class="flex flex-center text-white">
    <div class="row">
     <q-input
     input-class="text-center text-h5 text-white"
     color="teal"
        filled
        placeholder="Counter" />
    </div>
    <div class="row full-width items-center">
      <div class="col text-center">
        <q-btn round icon="remove" size="xl" />
      </div>
      <div class="col text-center text-h2">23</div>
      <div class="col text-center">
        <q-btn round icon="add" size="xl" />
      </div>
    </div>
    <div class="row">
      <q-btn round icon="restart_alt" size="xl" />
    </div>
  </q-page>
</template>

<script setup></script>
