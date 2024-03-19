<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
const {
  layer1,
  layer2,
  layer3,
  layer4,
  layer5,
  layer6,
  layer7,
  layer8,
  layer9,
  layer10,
  layer11,
  layerApp
} = useAppConfig();

console.log(layer1.sayHi);
console.log(layer2.sayHi);
console.log(layer3.sayHi);
console.log(layer4.sayHi);
console.log(layer5.sayHi);
console.log(layer6.sayHi);
console.log(layer7.sayHi);
console.log(layer8.sayHi);
console.log(layer9.sayHi);
console.log(layer10.sayHi);
console.log(layer11.sayHi);
// console.log(layerApp.sayHi);

</script>
