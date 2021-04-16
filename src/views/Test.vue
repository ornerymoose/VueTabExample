<template>
  <div class="test">
    <h1>This is a test page</h1>
    <tabs>
      <tab name="Services" :selected="true">
        <h1>What we do</h1>
      </tab>
      <tab name="Pricing">
        <h1>How much we do it for</h1>
      </tab>
      <tab name="About Us">
        <h1>Why we do it</h1>
      </tab>
    </tabs>
  </div>
</template>

<script>
import Tabs from '../components/Tabs.vue';
import Tab from '../components/Tab.vue';

export default {
  name: 'Test',
  components: {
    tabs: Tabs,
    tab: Tab,
  },
  data() {
    return {};
  },
};
</script>
