<template>
  <div>
  <table>
    <tr>
      <th>商品番号</th>
      <th>商品名</th>
      <th>詳細</th>
      <th>編集</th>
    </tr>
    <tr>
      <td>1</td>
      <td>テスト1</td>
      <td><NuxtLink to=/products/1/showProduct>詳細</NuxtLink></td>
      <td><NuxtLink to=/products/1/editProduct>編集</NuxtLink></td>
    </tr>
    <tr>
      <td>2</td>
      <td>テスト2</td>
      <td><NuxtLink to=products/2/showProduct>詳細</NuxtLink></td>
      <td><NuxtLink to=products/2/editProduct>編集</NuxtLink></td>
    </tr>
    <tr>
    <td>3</td>
      <td>テスト3</td>
      <td><NuxtLink to=products/3/showProduct>詳細</NuxtLink></td>
      <td><NuxtLink to=products/3/editProduct>編集</NuxtLink></td>
    </tr>
 </table>
  </div>


</template>

<script>
export default {

}
</script>

<style>

</style>