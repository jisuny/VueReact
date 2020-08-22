<template>
  <div class="container">
    <!-- 헤더뷰 -->
    <header-comp></header-comp>

    <div class="row">
      <!-- 여기 컨텐츠 -->
      <section id="page1" data-role="page">
        <div class="content" data-role="content">컨텐츠</div>
      </section>
    </div>
    <!-- 푸터뷰 -->
    <footer-comp></footer-comp>
  </div>
</template>

<script>
import Header from "./Header.vue";
import Footer from "./Footer.vue";

export default {
  data() {
    return {
      msg: "Hello VueJS",
    };
  },
  components: {
    "header-comp": Header,
    "footer-comp": Footer,
  },
};
</script>
