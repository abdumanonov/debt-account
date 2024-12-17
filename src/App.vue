
<template>
  <div>
  <debtor-list>    </debtor-list>
  </div>
  </template>

<script >
import DebtorList from './components/DebtorList.vue'
export default {
  components: {DebtorList},

}
</script>
<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
