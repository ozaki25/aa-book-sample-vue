<template>
  <table class="persons-table table table-bordered table-striped">
    <thead>
      <tr>
        <th>ID</th>
        <th>名前</th>
        <th>年齢</th>
        <th>性別</th>
        <th></th>
        <th></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td>1</td>
        <td>ozaki</td>
        <td>28</td>
        <td>男性</td>
        <td><button class="btn btn-xs btn-default">編集</button></td>
        <td><button class="btn btn-xs btn-default">削除</button></td>
      </tr>
    </tbody>
  </table>
</template>

<script>
export default {
  name: 'PersonsTable',
  props: {},
};
</script>
