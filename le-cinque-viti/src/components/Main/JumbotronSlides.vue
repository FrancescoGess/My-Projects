<script>

export default {
  name: "JumbotronSlides",
  data() {
    return {
      list: [
        {
          image: 'src/assets/img/slider1.jpg',
          title: 'wine one'
        },
        {
          image: 'src/assets/img/slider2.jpg',
          title: 'wine two'
        },
        {
          image: 'src/assets/img/slider3.jpg',
          title: 'wine three'
        },
        {
          image: 'src/assets/img/slider4.jpg',
          title: 'wine four'
        }
      ],
      timer: null,
      currentIndex: 0
    };
  },
  mounted: function () {

  },
  methods: {

  }


}

</script>

<template>
  <div>
    <figure>
      <img id="wine-background" :src="list[0].image" alt="wine">
    </figure>
  </div>

</template>

<style lang="scss" scoped>
#wine-background {
  width: 100%;
}
</style>
