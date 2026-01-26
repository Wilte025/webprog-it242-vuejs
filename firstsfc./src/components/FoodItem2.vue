<template>
  <div class="avocado">
    <h2>{{ name }}</h2>
    <p>{{ message }}</p>
  </div>
</template>

<script>
export default {
  data() {
    return {
      name: 'Avocado with Bear Brand & Ice Cube',
      message: 'I like avocado with bear brand & ice cube'
    }
  }
};
</script>

<style>
  .avocado {
    border: dashed black 1px;
    display: inline-block;
    margin: 10px;
    padding: 10px;
    background-color: #568203;
  }
  </style>