<template>
  <FormulateForm
    v-model="formValues"
  >
    <FormulateInput
      type="text"
      name="name"
      label="Your name"
      autocomplete="no"
    />
    <FormulateInput
      type="email"
      name="email"
      label="Your email"
      autocomplete="no"
    />
    <FormulateInput
      type="submit"
      label="Save account"
    />
  </FormulateForm>
</template>

<script>
export default {
  data () {
    return {
      formValues: {
        name: 'Jenny Taylor',
        email: 'jenny.taylor@example.com'
      }
    }
  }
}
</script>
