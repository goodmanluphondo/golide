<template>
  <div class="title">{{ title }}</div>
</template>
<style>
.title {
  width: 100%;
  height: 150px;
  background: green;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  font-size: 2.8rem;
}
</style>
<script>
export default {
  props: {
    title: String
  }
};
</script>
