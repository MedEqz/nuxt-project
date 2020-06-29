<template>
  <!-- <img class="EqzLogo" width="245" height="180" src="~/assets/baby_zebra.png" /> -->
  <div class="md:flex-shrink-0">
    <img
      class="EqzLogo rounded-lg md:w-56"
      src="~/assets/baby_zebra.png"
      alt="Baby Zebra"
    />
  </div>
</template>
<style>
.EqzLogo {
  animation: 1s appear;
  margin: 0;
}

@keyframes appear {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
</style>
