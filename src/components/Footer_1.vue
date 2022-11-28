<template>
  <footer>
    <div class="container">
      <div class="link-footer">
        <ul
          v-for="obj in arrLink"
          :key="obj.title"
        >
          <li><h2>{{ obj.title }}</h2></li>
          <li
            v-for="el in obj.links"
            :key="el.text"
          >
            <a :href="el.url">{{ el.text }}</a>
          </li>
        </ul>
      </div>
      <img
        src="@/assets/dc-logo-bg.png"
        alt=""
      >
    </div>
  </footer>
</template>

<script>
export default {
  name: 'FooterPage',
  data() {
    return {
      arrLink: [
        {
          title: 'dc comics',
          links: [
            {
              url: '#Characters',
              text: 'Characters',
            },
            {
              url: '#Comics',
              text: 'Comics',
            },
            {
              url: '#Movies',
              text: 'Movies',
            },
            {
              url: '#TV',
              text: 'TV',
            },
            {
              url: '#Games',
              text: 'Games',
            },
            {
              url: '#Videos',
              text: 'Videos',
            },
            {
              url: '#News',
              text: 'News',
            },
          ],
        },
        {
          title: 'shop',
          links: [
            {
              url: '#ShopDC',
              text: 'Shop DC',
            },
            {
              url: '#ShopDCCollectibles',
              text: 'Shop DC Collectibles',
            },
          ],
        },
        {
          title: 'DC',
          links: [
            {
              url: '#TermsOfUse',
              text: 'Term Of Use',
            },
            {
              url: '#PrivacyPolicy',
              text: 'Privacy Policy (new)',
            },
            {
              url: '#adChoice',
              text: 'Ad Choice',
            },
            {
              url: '#advertising',
              text: 'Advertising',
            },
            {
              url: '#jobs',
              text: 'Jobs',
            },
            {
              url: '#subscription',
              text: 'Subscription',
            },
            {
              url: '#talent',
              text: 'Talent',
            },
            {
              url: '#workshop',
              text: 'Workshop',
            },
            {
              url: '#CPSC',
              text: 'CPSC',
            },
            {
              url: '#certificates',
              text: 'Certificates',
            },
            {
              url: '#rating',
              text: 'Rating',
            },
            {
              url: '#showHelp',
              text: 'Show Help',
            },
            {
              url: '#contactUs',
              text: 'Contact Us',
            },
          ],
        },
        {
          title: 'sites',
          links: [
            {
              url: '#DC',
              text: 'DC',
            },
            {
              url: '#MAD',
              text: 'MAD',
            },
            {
              url: '#magazine',
              text: 'Magazine',
            },
            {
              url: '#DCKids',
              text: 'DC Kids',
            },
            {
              url: '#DCUniverse',
              text: 'DC Universe',
            },
            {
              url: '#DCPower',
              text: 'DC Power',
            },
            {
              url: '#visa',
              text: 'Visa',
            },
          ],
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
  footer{
    background-image: url(@/assets/footer-bg.jpg);
    background-position: center;
    background-size: cover;
    width: 100%;
    height: 30rem;
    display: flex;
    justify-content: center;
  }

  h2{
    color: white;
    text-transform: uppercase;
    font-size: 20px;
  }

  ul{
    list-style: none;
    width: 120px;
  }

  a{
    text-decoration: none;
    color: gray;
    font-size: 20px;
  }

  .container{
    width: 1200px;
    height: 100%;
    display: flex;
    overflow: hidden;
    align-items: center;
  }

  .link-footer{
    width: 600px;
    height: 100%;
    display: flex;
    flex-direction: column;
    flex-wrap: wrap;
    padding: 2rem;
  }

  img{
    width: 600px;
  }

</style>
