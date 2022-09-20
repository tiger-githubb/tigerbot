<template>
  <div class="home">
    <Chat/>
  </div>
</template>

<script>
// @ is an alias to /src
import Chat from '@/components/Chat.vue';

export default {
  name: 'HomeView',
  components: {
    Chat
}
}
</script>
