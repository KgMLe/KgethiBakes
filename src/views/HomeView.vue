<template>
  <div class="container-fluid">
    <div class="row" id="landingpage">
      <div class="blockquote-wrapper">
  <div class="blockquote">
    <h1>
      Life's Short, Eat More Cake: 
      We're <br>Here to Sweeten Your Moments
     </h1>
  </div>
</div>
    </div>

    <div class="container-fluid">
<div class="row" id="landingcta">
  <div class="container">
  <P>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae recusandae veniam dicta iusto cumque, commodi, sapiente aperiam molestias id totam illo minus? Laborum accusantium ipsa veritatis inventore. Molestiae, ipsum odio?
  </P>
  </div>
  <div class="col-sm-6" id="col1">
      <h1>
        We Bake
      </h1>
      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aperiam ad consequuntur fugit amet. Optio error beatae reprehenderit ullam. Iure aperiam sint ipsum consectetur facere quis vero nostrum qui tempora sed.</p>
      <button class="btn">
        <router-link to="/gallery" class="btn links_nav text-white">Gallery</router-link>
    </button>
    </div>
    <div class="col-sm-6" id="col2">
      <h1>
        We Cook
      </h1>

      <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Illum hic reiciendis excepturi illo quaerat quasi! Sapiente sint nulla odit consequatur voluptate iusto corrupti non similique sit, assumenda magni quia recusandae?</p>
      <button class="btn">
        <router-link to="/kgethiskotas" class="btn links_nav text-white" style>Kgethi Bakes Kota</router-link>
    </button>
    </div>
</div>
</div> 
  </div>
</template>

<script>
</script>

<style scoped>
#landingpage{
background-image: url("https://www.foodandwine.com/thmb/d894lH2RTu6tJoR0N78hSkXXy2g=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/maria-cookies-icebox-cake-FT-RECIPE0521-4089012694154e40a90e368863e4fa08.jpg");
background-position: center;
/* background-repeat: no-repeat; */
background-size: cover;
background-attachment: fixed;
}

.btn{
  background-color: black;
  border: none;
  color: white;
  border-radius:10px
}

.col-sm-6{
  align-items: center;
  padding: 10px;
  border: 3px white;
}

.col-sm-6:hover{
  transform: scale(1.2);
  transition-duration: .8s;
  filter: grayscale(50%);
  opacity: .7;
}

#col1{
background-image: url("https://m.media-amazon.com/images/I/71hJGezj2OS._AC_UF1000,1000_QL80_.jpg");
background-position: center;
background-repeat: no-repeat;
background-size: cover;
border-radius: 10px;
padding: 5%;
}

#col2{
background-image: url("https://media.citizen.co.za/wp-content/uploads/2023/04/Flying-fish-neos-kota-1200x960-1.jpg");
background-position: center;
background-repeat: no-repeat;
background-size: cover;
border-radius: 10px;
padding: 5%;
}

.blockquote {
    position: relative;
    font-family: 'Montserrat', sans-serif;
    font-weight: 800;
    color: #44A1A0;
    padding: 7%;
    width: 100%;
    max-width: 500px;
    z-index: 1;
    margin: 80px auto;
    align-self: center;

    border-top: solid 3px;
    border-bottom: solid 3px;
}

/* Blockquote header */
.blockquote h1 {
    align-content: start !important;
    color: white;
    font-size: 40px;
    font-weight: 800;
    line-height: 1;
    margin: 0;
}

#landingcta{
  padding: 5%;

}
</style>
