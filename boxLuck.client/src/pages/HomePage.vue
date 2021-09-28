<template>
  <div class="container-fluid">
    <div class="row mt-3">
      <div class="col-3">
        <div class="home-card bg-white rounded elevation-3 d-flex flex-column align-items-center py-4">
          <img class="Img elevation-2" src="../assets/img/BO3.jpg" alt="Black Ops 3 Image">
          <div class="col-11 bg-white text-dark text-center pt-3">
            <h4>COD: Black Ops 3</h4>
          </div>
        </div>
      </div>
      <div class="col-3">
        <div class="home-card bg-white rounded elevation-3 d-flex flex-column align-items-center py-4">
          <img class="Img elevation-2" src="../assets/img/BO4.jpg" alt="Black Ops 3 Image">
          <div class="col-11 bg-white text-dark text-center pt-3">
            <h4>COD: Black Ops 4</h4>
          </div>
        </div>
      </div>
      <div class="col-3">
        <div class="home-card bg-white rounded elevation-3 d-flex flex-column align-items-center py-4">
          <img class="Img elevation-2" src="../assets/img/BO5.png" alt="Black Ops Cold War Image">
          <div class="col-11 bg-white text-dark text-center pt-3">
            <h4>COD: Black Ops Cold War</h4>
          </div>
        </div>
      </div>
      <div class="col-3">
        <div class="home-card bg-white rounded elevation-3 d-flex flex-column align-items-center py-4">
          <img class="Img elevation-2" src="../assets/img/BOV.png" alt="Black Ops Vanguard Image">
          <div class="col-11 bg-white text-dark text-center pt-3">
            <h4>COD: Vanguard</h4>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Home'
}
</script>

<style scoped lang="scss">
.home{
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;
  .home-card{
    width: 50vw;
    > img{
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
.Img{
  max-width: 200px;
  width: 100%;
  object-fit: contain;
  object-position: center;
}
</style>
