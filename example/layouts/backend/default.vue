<template>
  <div>
    <strong>Override backend layout</strong>
    <ce-renderer :content="content.colPos0" />
  </div>
</template>
<script>
import BeDefault from '~typo3/layouts/backend/BeDefault'
export default {
  name: 'BeDefault',
  functional: false,
  extends: BeDefault
}
</script>
