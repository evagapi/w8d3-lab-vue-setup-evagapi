<!-- eslint-disable vue/multi-word-component-names -->
<template>
  <div>
    <h1>Hello World!</h1>
    <p>{{ aboutMe }}</p>
  </div>
</template>
<script>
const aboutMe = `
I ❤️ cheese, especially queso blue castello. 
Parmesan cheese slices caerphilly edam feta cheese 
and biscuits mascarpone cauliflower cheese.
Mozzarella cauliflower cheese fromage cow 
pecorino danish fontina pecorino stinking bishop. 
Cream cheese fondue manchego parmesan smelly cheese.
`;

export default {
  data() {
    return {
      aboutMe,
    };
  },
};
</script>
