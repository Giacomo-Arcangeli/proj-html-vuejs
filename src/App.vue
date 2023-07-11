<script>
import PageHeader from './components/PageHeader.vue';
import PageMain from './components/PageMain.vue';
import PageFooter from './components/PageFooter.vue';

export default {
  components: { PageHeader, PageMain, PageFooter },
  data() {
    return {
      navbarLinks: [
        {
          text: 'HOME',
          url: '#'
        },
        {
          text: 'BLOG',
          url: '#',
        },
        {
          text: 'PAGES',
          url: '#'
        },
        {
          text: 'ABOUT',
          url: '#'
        },
        {
          text: 'CONTACTS',
          url: '#'
        },
        {
          text: 'GALLERY',
          url: '#'
        },
        {
          text: 'SHOP',
          url: '#'
        }
      ]
    }
  }
}
</script>



<template>
  <PageHeader :navbar-links="navbarLinks" />
  <PageMain />
  <PageFooter />
</template>



<style lang="scss">
.bor {
  border: 1px dashed red;
}

ul {
  list-style-type: none;
  padding: 0;
}

a {
  text-decoration: none;
}

.button-style {
  color: black;
  padding: 12px 35px;
  background-color: #fff;
  font-size: 0.8rem;
  font-weight: bold;
}
</style>