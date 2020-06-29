<template>
  <div id="app">
    <employee-table />
  </div>
</template>

<script>
import EmployeeTable from '@/components/EmployeeTable'

export default {
  name: 'App',
  components: {
    EmployeeTable
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>
