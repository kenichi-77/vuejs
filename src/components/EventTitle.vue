<template>
  <div>
    <label for="title">タイトル</label>
    <input type="text" id="title" :value="value" @input="$emit('input', $event.target.value)" />
    <pre>{{value}}</pre>
  </div>
</template>

<script>
export default {
  name: "EventTitle",
  props: ["value"],
};
</script>
