<template>
    <v-footer padless class="font-weight-medium">
      <v-col class="text-center" cols="12">
        {{ new Date().getFullYear() }} — <strong>Laravel Forum</strong>
      </v-col>
    </v-footer>
</template>

<script>
export default {
    name: 'AppFooter'
}
</script>