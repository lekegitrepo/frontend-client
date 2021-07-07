<template>
  <div id="contacts">
    <div v-for="contact in contacts" :key="contact.id">
      <p>{{ contact.name }} is my {{ contact.relationship }}</p>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped></style>
