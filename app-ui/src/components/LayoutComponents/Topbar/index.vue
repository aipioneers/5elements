<template>
  <div :class="$style.topbar">
    <div class="mr-4">
    </div>
    <!--
    <div class="mr-4">
      <cui-issues-history />
    </div>
    <div class="mr-4">
      <cui-project-management />
    </div>
    -->
    <div class="mr-auto">
      <cui-live-search />
    </div>
    <div class="mr-4">
      <cui-language-selector />
    </div>
    <div class="mr-4">
      <cui-home-menu />
    </div>
    <cui-profile-menu />
  </div>
</template>

<script>
import CuiIssuesHistory from '@/components/LayoutComponents/Topbar/IssuesHistory'
import CuiProjectManagement from '@/components/LayoutComponents/Topbar/ProjectManagement'
import CuiLiveSearch from '@/components/LayoutComponents/Topbar/LiveSearch'
import CuiLanguageSelector from '@/components/LayoutComponents/Topbar/LanguageSelector'
import CuiHomeMenu from '@/components/LayoutComponents/Topbar/HomeMenu'
import CuiProfileMenu from '@/components/LayoutComponents/Topbar/ProfileMenu'

export default {
  components: {
    CuiIssuesHistory,
    CuiProjectManagement,
    CuiLiveSearch,
    CuiLanguageSelector,
    CuiHomeMenu,
    CuiProfileMenu,
  },
}
</script>

<style lang="scss" module>
@import "./style.module.scss";
</style>
