<template>
  <div id="app">
    <div class="main-wrapper">
      <div class="container px-4">
        <article class="resume-wrapper mx-auto theme-bg-light p-5 mb-5 my-5 shadow-lg">
          <ResumeHeader />
          <hr>
          <ResumeBody />
        </article>
      </div>
      <Footer />
    </div>
  </div>
</template>

<script>
import ResumeHeader from './components/TheResumeHeader.vue';
import ResumeBody from './components/TheResumeBody.vue';
import Footer from './components/TheFooter.vue';

export default {
  name: 'App',
  components: {
    ResumeHeader,
    ResumeBody,
    Footer,
  },
};
</script>
<style lang="scss" src="@/assets/devresume.scss"></style>
