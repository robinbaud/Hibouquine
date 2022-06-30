<template>
  <div id="AddVue">
    <ul>
      <li v-for="data in image" :key="data.id">
        <img :src="data.url" />
      </li>
    </ul>
  </div>
</template>

<script>
import PostData from "../../json/post.json";

export default {
  name: "AddVue",
  data() {
    return {
      image: PostData,
    };
  },
  mounted() {
    console.log("coucou");
    console.log(PostData);
  },
  methods: {},
};
</script>

<style scoped>
#AddVue {
  height: 100vh;
}
@import "~bootstrap/dist/css/bootstrap.css";
</style>
