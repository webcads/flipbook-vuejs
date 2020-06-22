<template>
  <flipbook class="flipbook" :pages="pages" v-slot:flipbook>
  </flipbook>
</template>

<script>
import Flipbook from "flipbook-vue";
export default {
  name: "FlipBook",
  components: {
    Flipbook
  },
  data() {
    return {
      pages: [
        "https://i.dlpng.com/static/png/6974834_preview.png",
        "https://3.bp.blogspot.com/-eMBQjNR-7ns/VuE-h1pfZ2I/AAAAAAAArZY/zK9EU7A8lfU/s1600/mickey-mouse-cartoon-pictures-photos-14081-full-hd-wallpaper.jpg",
        "https://pluspng.com/img-png/animated-dog-png-hd-images-of-101-dalmatians-1040x1282-1040.png",
        "https://images-na.ssl-images-amazon.com/images/I/61psbvFeANL._SY450_.jpg",
        "https://images-na.ssl-images-amazon.com/images/I/81TGehzAuHL._AC_SL1500_.jpg",
        "https://i.pinimg.com/originals/cd/92/69/cd9269fdafffd5d11b58f2cacd2559e1.png",
        "https://wallpapercave.com/wp/wp2153319.jpg",
        "https://i.pinimg.com/originals/a9/a5/97/a9a5975ddb8b788043a3e362a0a2dd22.jpg",
        "https://lh3.googleusercontent.com/proxy/3IAAOvfZB9U_MzRHZddvOsubwm75m2g7sfYEHjJtV2kjABNmW0TjzVssCceTHoMP1rNKElteG8JyIiuUmpw_u52p2Aqwgim3tYtzZnW02dNC8wfZGrwpsm2m9Stpo4JX517G",
        "https://i.pinimg.com/originals/ee/fd/4d/eefd4d45c0cd9dd7f3d86b4b49e7fc72.png",
        "https://pluspng.com/img-png/cartoon-hd-png-collection-of-7-mickey-mouse-cartoons-hd-1024.png",
        "https://lh3.googleusercontent.com/proxy/OFRXYpn7_mhWv1z7m64t3BwS6zPh8s4pz2o0x-giZiEcmqoJln4gx3iqhfAZOi1bJVW0be1-30CEVti81T8wyFfCHDFDon9DmNI3Fx8NPbW4bs26fgBQRXT65Inww1gfXb0aFZJLclnN-x7OMn5RkClJ",
        "https://banner2.cleanpng.com/20180621/pof/kisspng-hefty-smurf-brainy-smurf-smurfette-clumsy-smurf-pa-5b2c56c1990c49.6412206815296324496269.jpg",
        "https://satheeshiyer.files.wordpress.com/2010/06/krishnaa.jpg",
        "https://www.clipartkey.com/mpngs/m/119-1192240_yellow-angry-bird-cartoon.png",
        "https://st2.depositphotos.com/1967477/12161/v/950/depositphotos_121614348-stock-illustration-cartoon-baby-elephant-spraying-water.jpg"
      ],
      singlePage: true,
      startPage: 1
    };
  }
};
</script>

<style>
.flipbook {
  width: 90vw;
  height: 90vh;
  padding: 5px;
}
.flipbook .viewport {
  width: 90vw;
  height: calc(100vh - 50px - 40px);
}
.flipbook .bounding-box {
  box-shadow: 0 0 20px #000;
  border-radius: 10px;
}

</style>