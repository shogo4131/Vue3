<script lang="tsx">
import { defineComponent } from 'vue';
import HelloWorld from './components/HelloWorld.vue';

export default defineComponent({
  name: 'App',
  setup() {
    return () => (
      <>
        <HelloWorld msg="Hello Vue 3 + TypeScript + Vite" />
      </>
    );
  },
});
</script>
