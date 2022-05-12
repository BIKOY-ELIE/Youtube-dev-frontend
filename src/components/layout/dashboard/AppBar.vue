<template>
  <div action="" class="grid grid-cols-12 px-2 mt-5 gap-5">
    <div class="col-span-8"><Form></Form></div>
    <div class="col-span-4">
      <IconsProfil></IconsProfil>
    </div>
  </div>
</template>

<script>
import IconsProfil from '../IconsProfil.vue';
import Form from '../Form.vue';
export default {
  components: {
    IconsProfil,
    Form
  }
};
</script>

<style>
.border-r-1 {
  border-right-width: 1px;
}
.border-1 {
  border-width: 1px;
}
.form,
.input,
.form div div select {
  background-color: #e5e5e5;
}
</style>