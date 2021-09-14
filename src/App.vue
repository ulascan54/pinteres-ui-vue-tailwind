<script setup>
// This starter template is using Vue 3 <script setup> SFCs
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup
import TopNav from "./TopNav.vue";
import Card from "./Card.vue";
</script>
<script>
export default {
  data() {
    return {
      cards: [
        {
          src: "https://s2.best-wallpaper.net/wallpaper/iphone/1809/Beautiful-girl-black-hair-summer_iphone_1080x1920.jpg",
          title: "Title 1",
          user: "user 1",
          recommended: "Travel",
        },
        {
          src: "https://www.intersinema.com/kisi/resimler/r/robitel_adam/6054_robitel_adam.jpg",
          title: "Title 2",
          user: "user 2",
          recommended: "Work",
        },
        {
          src: "https://cdn.shopify.com/s/files/1/0759/6943/files/IMG_5656_1024x1024.JPG?v=1495665213",
          title: "Title 3",
          user: "user 3",
          recommended: "Hangout",
        },
        {
          src: "https://femina.wwmindia.com/photogallery/2016/Aug/tap_dance_inside_1472639695_760x568.jpg",
          title: "Title 4",
          user: "user 4",
          recommended: "Party",
        },
        {
          src: "https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fksassets.timeincuk.net%2Fwp%2Fuploads%2Fsites%2F56%2F2018%2F06%2FPinterest-trends-1920x1152.jpg&f=1&nofb=1",
          title: "Title 1",
          user: "user 1",
          recommended: "Travel",
        },
        {
          src: "https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fwww.lovethispic.com%2Fuploaded_images%2F198960-Fall-Roadway.jpg&f=1&nofb=1",
          title: "Title 2",
          user: "user 2",
          recommended: "Work",
        },
        {
          src: "https://s2.best-wallpaper.net/wallpaper/iphone/1809/Beautiful-girl-black-hair-summer_iphone_1080x1920.jpg",
          title: "Title 3",
          user: "user 3",
          recommended: "Hangout",
        },
        {
          src: "https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.searchenginejournal.com%2Fwp-content%2Fuploads%2F2018%2F04%2FPushing_PInterest_Limits-copy-760x400.png&f=1&nofb=1",
          title: "Title 4",
          user: "user 4",
          recommended: "Party",
        },
        {
          src: "https://external-content.duckduckgo.com/iu/?u=http%3A%2F%2Fthebuzz.dianejameshome.com%2Fwp-content%2Fuploads%2F2015%2F02%2Fpinterest-spring-flowers-4.jpg&f=1&nofb=1",
          title: "Title 1",
          user: "user 1",
          recommended: "Travel",
        },
        {
          src: "https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.pinimg.com%2F736x%2Fe4%2F2f%2Ffd%2Fe42ffd2056618e81320498273130731a.jpg&f=1&nofb=1",
          title: "Title 2",
          user: "user 2",
          recommended: "Work",
        },
        {
          src: "https://s2.best-wallpaper.net/wallpaper/iphone/1809/Beautiful-girl-black-hair-summer_iphone_1080x1920.jpg",
          title: "Title 3",
          user: "user 3",
          recommended: "Hangout",
        },
        {
          src: "https://femina.wwmindia.com/photogallery/2016/Aug/tap_dance_inside_1472639695_760x568.jpg",
          title: "Title 4",
          user: "user 4",
          recommended: "Party",
        },
        {
          src: "https://s2.best-wallpaper.net/wallpaper/iphone/1809/Beautiful-girl-black-hair-summer_iphone_1080x1920.jpg",
          title: "Title 1",
          user: "user 1",
          recommended: "Travel",
        },
        {
          src: "https://www.intersinema.com/kisi/resimler/r/robitel_adam/6054_robitel_adam.jpg",
          title: "Title 2",
          user: "user 2",
          recommended: "Work",
        },
        {
          src: "https://cdn.shopify.com/s/files/1/0759/6943/files/IMG_5656_1024x1024.JPG?v=1495665213",
          title: "Title 3",
          user: "user 3",
          recommended: "Hangout",
        },
        {
          src: "https://femina.wwmindia.com/photogallery/2016/Aug/tap_dance_inside_1472639695_760x568.jpg",
          title: "Title 4",
          user: "user 4",
          recommended: "Party",
        },
        {
          src: "https://s2.best-wallpaper.net/wallpaper/iphone/1809/Beautiful-girl-black-hair-summer_iphone_1080x1920.jpg",
          title: "Title 1",
          user: "user 1",
          recommended: "Travel",
        },
        {
          src: "https://www.intersinema.com/kisi/resimler/r/robitel_adam/6054_robitel_adam.jpg",
          title: "Title 2",
          user: "user 2",
          recommended: "Work",
        },
        {
          src: "https://cdn.shopify.com/s/files/1/0759/6943/files/IMG_5656_1024x1024.JPG?v=1495665213",
          title: "Title 3",
          user: "user 3",
          recommended: "Hangout",
        },
        {
          src: "https://femina.wwmindia.com/photogallery/2016/Aug/tap_dance_inside_1472639695_760x568.jpg",
          title: "Title 4",
          user: "user 4",
          recommended: "Party",
        },
        {
          src: "https://s2.best-wallpaper.net/wallpaper/iphone/1809/Beautiful-girl-black-hair-summer_iphone_1080x1920.jpg",
          title: "Title 1",
          user: "user 1",
          recommended: "Travel",
        },
        {
          src: "https://www.intersinema.com/kisi/resimler/r/robitel_adam/6054_robitel_adam.jpg",
          title: "Title 2",
          user: "user 2",
          recommended: "Work",
        },
        {
          src: "https://cdn.shopify.com/s/files/1/0759/6943/files/IMG_5656_1024x1024.JPG?v=1495665213",
          title: "Title 3",
          user: "user 3",
          recommended: "Hangout",
        },
        {
          src: "https://femina.wwmindia.com/photogallery/2016/Aug/tap_dance_inside_1472639695_760x568.jpg",
          title: "Title 4",
          user: "user 4",
          recommended: "Party",
        },
      ],
    };
  },
  computed: {
    subArrays() {
      let length = Math.ceil(this.cards.length / 5);
      const result = new Array(length)
        .fill()
        .map((i) => this.cards.splice(0, length));

      return result;
    },
  },
};
</script>
<template>
  <TopNav />
  <div class="px-20 flex flex-wrap w-full">
    <div v-for="(arr, i) in subArrays" :key="i" class="w-1/5">
      <div v-for="(card, index) in arr" :key="index" class="w-full">
        <div class="w-full p-2">
          <Card
            :src="card.src"
            class="w-full h-full"
            :board="card.recommended"
          />
          <div class="text-sm leading-tight p-2">
            <p class="font-bold">{{ card.title }}</p>
            <p>{{ card.user }}</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
