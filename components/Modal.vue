<template>
  <div
    id="notificationContainer"
    class="flex justify-center fixed top-0 left-0 right-0 bottom-0 items-center z-20 bg-black bg-opacity-50"
  >
    <div
      class="notification content mt-12 p-8 bg-gray-700 text-gray-200 rounded relative z-10 mx-4 max-w-md whitespace-pre-line"
      v-html="content"
    ></div>
  </div>
</template>

<script>
export default {
  props: ['content'],
}
</script>
