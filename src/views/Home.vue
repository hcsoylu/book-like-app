<template>
  <AppHeader />
  <div class="flex flex-row">
    <Sidebar />

    <AppBookmarkList />
  </div>
</template>

<script>
import Sidebar from "@/components/Home/Sidebar";

export default {
  components: {
    Sidebar,
  },
};
</script>
