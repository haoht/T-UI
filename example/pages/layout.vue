<template>
  <div>
    <h2>layout</h2>
    <div class="demo-block">
      <t-row>
        <t-col :span="24"><div class="grid-content bg-black"></div></t-col>
      </t-row>
      <t-row>
        <t-col :span="12"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="12"><div class="grid-content bg-gray-light"></div></t-col>
      </t-row>
      <t-row>
        <t-col :span="8"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="8"><div class="grid-content bg-gray-light"></div></t-col>
        <t-col :span="8"><div class="grid-content bg-gray"></div></t-col>
      </t-row>
      <t-row>
        <t-col :span="6"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="6"><div class="grid-content bg-gray-light"></div></t-col>
        <t-col :span="6"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="6"><div class="grid-content bg-gray-light"></div></t-col>
      </t-row>
      <t-row>
        <t-col :span="4"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="4"><div class="grid-content bg-gray-light"></div></t-col>
        <t-col :span="4"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="4"><div class="grid-content bg-gray-light"></div></t-col>
        <t-col :span="4"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="4"><div class="grid-content bg-gray-light"></div></t-col>
      </t-row>
    </div>
    <layout></layout>
    <h2>layout-gutter</h2>
    <div class="demo-block">
      <t-row :gutter="20">
        <t-col :span="6"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="6"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="6"><div class="grid-content bg-gray"></div></t-col>
        <t-col :span="6"><div class="grid-content bg-gray"></div></t-col>
      </t-row>
    </div>
    <layout-gutter></layout-gutter>
  </div>
</template>
<script>
import Layout from '../documents/layout/layout.md'
import layoutGutter from '../documents/layout/layoutGutter.md'
export default {
  components: {
    Layout,
    layoutGutter
  }
}
</script>
