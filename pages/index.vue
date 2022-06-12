<template>
  <!-- <Tutorial /> -->
  <!-- <div>
  <NuxtLink to="/about">about</NuxtLink>
  </div> -->
  <table>
  <tr>
  <td>1</td>
  <td>テスト</td>
  <td><NuxtLink to=“/products/1/show”>詳細</NuxtLink></td>
  <td><NuxtLink to=“/products/1/edit”>編集</NuxtLink></td>
  </tr>
  </table>


</template>

<script>
export default {
  name: 'IndexPage',
}
</script>
