<template>
  <div>
    <!--Here we define the components that we divide into subsections in the sidebar. in this way, it becomes a whole.-->
    <ul
      class="navbar-nav bg-gradient-primary sidebar sidebar-dark accordion"
      id="accordionSidebar"
    >
      <SidebarBrand />
      <NavitemDashboard />
      <NavMenu />
      <NavMenuUtilities />
      <NavCollapse />
      <NavCharts />
      <NavTables />

    </ul>
    
  </div>
</template>

<script>
//Here we define the components that we divide into subsections in the sidebar. in this way, it becomes a whole.
import SidebarBrand from "./SidebarBrand.vue";
import NavitemDashboard from "./NavitemDashboard.vue";
import NavMenu from "./NavMenu.vue";
import NavMenuUtilities from "./NavMenuUtilities.vue";
import NavCollapse from "./NavCollapse.vue";
import NavCharts from './NavCharts.vue';
import NavTables from './NavTables.vue';

export default {
  name: "SideBar",
  components: {
    SidebarBrand,
    NavitemDashboard,
    NavMenu,
    NavMenuUtilities,
    NavCollapse,
    NavCharts,
    NavTables
  }
};
</script>

<style scoped>
</style>
