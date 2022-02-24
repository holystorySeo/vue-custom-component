<template>
  <main>
    <section class="wrap">
      <h2>Vue-custom-component</h2>
      <TabSection @tabIndex="setTabIndex"/>
    </section>
  </main>
</template>

<script>
import TabSection from './components/TabSection.vue';

export default {
  name: 'App',
  components: {
    TabSection
  },
}
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  list-style: none;
}
main {
  width: 100%;
  height: 100%;
  min-height: 100vh;
  background-color: #e5e5e5;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}
.wrap {
  width: 360px;
  height: 100vh;
  padding: 15px;
  background-color: #fff;
}
</style>
