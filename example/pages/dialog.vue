<template>
    <div>
        <h2>提示框</h2>
        <div class="demo-block">
            <t-button type="success" v-on:click="showSuccess()">success</t-button>
            <t-button type="info" @click="showInfo()">info</t-button>
            <t-button type="warning" @click="showWarning()">warning</t-button>
            <t-button type="danger" @click="showDanger()">danger</t-button>
        </div>
        <Dialog></Dialog>
    </div>
</template>
<script>
import Dialog from '../documents/dialog/dialog.md'
export default {
  components: {
    Dialog
  },
  methods: {
    showSuccess () {
      this.$Dialog.success({
        showFooter: true
      })
    },
    showInfo () {
      this.$Dialog.info({
        showFooter: true
      })
    },
    showDanger () {
      this.$Dialog.danger({
        showFooter: true
      })
    },
    showWarning () {
      this.$Dialog.warning({
        showFooter: true
      })
    }
  }
}
</script>
