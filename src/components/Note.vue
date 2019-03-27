<template>
  <div class="item">
    <div class="meta">{{'updated'}}</div>
    <div class="content">
      <div class="header">{{ 'header' ||"新建笔记"}}</div>
      <div class="extra">
        <editor></editor>
        <span>共 {{'words'}} 字 .</span>
        <i class="right floated trash alternate outline icon"></i>
      </div>
    </div>
  </div>
</template>
<script>
import Editor from './Editor'
export default {
  components: {
    Editor
  }
}
</script>
