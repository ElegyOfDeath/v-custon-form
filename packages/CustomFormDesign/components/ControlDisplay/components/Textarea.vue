<!--多行输入框-->
<template>
  <el-form ref="form" label-position="top" @submit.native.prevent>
    <el-form-item
      :show-message="false"
      :required="formProps.required"
      :label="formSettings.props.label"
    >
      <el-input
        v-model="value"
        :placeholder="formProps.placeholder"
        resize="none"
        type="textarea"
      />
    </el-form-item>
  </el-form>
</template>
<script lang="ts">
import { Component, Mixins } from "vue-property-decorator";
import BaseFormDisplay from "../BaseFormDisplay.vue";

@Component
export default class Textarea extends Mixins(BaseFormDisplay) {}
</script>
<style scoped lang="scss">
@import "../../../styles/formDisplay.scss";
</style>
