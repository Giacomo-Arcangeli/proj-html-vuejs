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
      ],
      informationLinks: [
        {
          text: 'Product Support',
          url: '#'
        },
        {
          text: 'Checkout',
          url: '#',
        },
        {
          text: 'Report Abuse',
          url: '#'
        },
        {
          text: 'Redeem Voucher',
          url: '#'
        },
        {
          text: 'Order Status',
          url: '#'
        }
      ],
      usefulLinks: [
        {
          text: 'Policies & Rules',
          url: '#'
        },
        {
          text: 'Privacy Policy',
          url: '#',
        },
        {
          text: 'License Policy',
          url: '#'
        },
        {
          text: 'My Account',
          url: '#'
        },
        {
          text: 'Locality',
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
  <PageFooter :information-links="informationLinks" :useful-links="usefulLinks" />
</template>



<style lang="scss">
.bor {
  border: 2px dashed red;
}

// GENERICS

* {
  line-height: 2;
}

ul {
  list-style-type: none;
  padding: 0;
}

a {
  text-decoration: none;
}


// UTILITIES
.button-style {
  color: #111111;
  padding: 12px 35px;
  background-color: #fff;
  font-size: 0.9rem;
  font-weight: bold;
}

.card-box {
  max-width: 420px;
}

// FONT

h2 {
  margin-top: 15px;
  margin-bottom: 35px;
}

h6 {
  margin-top: 20px;
  margin-bottom: 10px;
}

.small {
  font-size: 0.9rem;
}

// PALETTE
.black {
  color: #111111;
}

.white {
  color: #ffffff;
}

.grey {
  color: #666666;
}

.light-grey {
  color: #f2f2f2;
}
</style>