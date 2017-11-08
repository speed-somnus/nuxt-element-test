<template>
  <div>
  </div>
</template>

<script>
export default {
  fetch ({ route, redirect }) {
    if (route.name === 'index') {
      redirect('/home')
      console.log('route.name',route.name)
    }
  }
}
</script>

