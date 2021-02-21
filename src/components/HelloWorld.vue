<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      TEST1
    </p>
    <p>
      TEST2
    </p>
    <p>
      TEST3
    </p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>
