<template>
    <div>
      <el-date-picker v-model="formTwoDate"
                      type="date"
                      :clearable="false"
                      :editable="false"
                      value-format="yyyy-MM-dd"
                      :picker-options="pickerOptions">
      </el-date-picker>
    </div>
</template>

<script>
    export default {
        name: "test",

        data() {
          return {
            formTwoDate: '',
          }
      }
    }
</script>

<style scoped>

</style>
