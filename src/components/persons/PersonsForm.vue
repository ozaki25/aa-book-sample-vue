<template>
  <form class="form-inline">
    <div class="form-group">
      <label for="input-id" class="label-control">ID</label>
      <input id="input-id" class="form-control" readonly />
    </div>
    <div class="form-group">
      <label for="input-name" class="label-control">名前</label>
      <input id="input-name" class="form-control" />
    </div>
    <div class="form-group">
      <label for="input-age" class="label-control">年齢</label>
      <input id="input-age" class="form-control" type="number" />
    </div>
    <div class="form-group">
      <label for="input-gender" class="label-control">性別</label>
      <select id="input-gender" class="form-control">
        <option value="" />
        <option value="男性">男性</option>
        <option value="女性">女性</option>
      </select>
    </div>
    <button id="button-register" type="button" class="btn btn-default">
      登録
    </button>
  </form>
</template>

<script>
export default {
  name: 'PersonsForm',
  props: {},
};
</script>
