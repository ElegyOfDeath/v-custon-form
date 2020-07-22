# v-custom-form

## 使用指南

### CustomFormFill

自定义表单填写器

**props**

| 参数          | 说明                     | 格式                |
| ------------- | ------------------------ | ------------------- |
| v-model       | 表单编辑获得的表单内容   | [{ id:"",value:" }] |
| componentList | 表单设计器生成的表单内容 | 参考表单生成器      |

### CustomFormDesign

自定义表单设计器

**props**

| 参数    | 说明                 | 格式                                    |
| ------- | -------------------- | --------------------------------------- |
| v-model | 表单生成器获得的表单 | [{ name:"",componentName:"",props:{} }] |
