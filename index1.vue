<template>
  <div>
    <QRcode :src = src :name="teacherName">
    </QRcode>
  </div>
</template>
<script type="text/ecmascript-6">
  export default {
    data() {
      return {
        teacherName: 'jiang',
        src: 'https://box.bdimg.com/static/fisp_static/common/img/searchbox/logo_news_276_88_1f9876a.png',
    components: {
      QRcode
    },
  }
</script>
