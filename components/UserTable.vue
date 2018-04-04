<template>

  <table class="table table-striped table-dark table-hover">
    <thead>
    <tr>
      <th scope="col">#</th>
      <th scope="col">First</th>
      <th scope="col">Last</th>
      <th scope="col">Handle</th>
    </tr>
    </thead>
    <tbody>
    <tr v-for="(user, idx) in users">
      <td>{{idx}}</td>
      <td>{{user.fname}}</td>
      <td>{{user.lname}}</td>
      <td>{{user.handle}}</td>
    </tr>
    </tbody>
  </table>

</template>

<script>
  export default {
    data(){
      return {
        users: [{fname: 'joe', lname: 'smith', handle: 'jsmith'}, {fname: 'bill', lname: 'saunders', handle: 'bsaunders'}]
      }
    }
  }
</script>

<style scoped>
  .table{
    margin-top: 10px;
  }
</style>
