<template lang="html">
  <div class="cover h-screen grid grid-cols-1 grid-flow-row">
    <nav class="w-full">
      <div class="bg-white py-4 pl-40">
        <img src="~/assets/images/logo.png" alt="logo dolin" />
      </div>
    </nav>
    <div
      class=" xl:px-40 sm:px-20 px-10 pt-10 sm:pt-0 lg:row-span-3 grid grid-cols-1 grid-flow-row lg:grid-rows-1 lg:grid-flow-col"
    >
      <div class="flex flex-col">
        <div class="pt-4 flex flex-col justify-center">
          <h1 class="sm:text-5xl text-3xl content text-white font-bold">
            One Stop Traveling
          </h1>
          <h3 class="sm:text-2xl text-lg text-white content-child">
            solution right on your hand.
          </h3>
        </div>
        <div class="pt-4">
          <p class="xl:text-xl sm:text-lg text-base font-thin text-white content-child">
            Dolin give you flexibility to choose your get-lost-destination.<br />
            Bunch of hidden places you will never imagine to the popular<br />
            destination are here.
          </p>
        </div>
        <div class="pt-4 flex items-center">
          <img
            src="~/assets/images/comming_on.png"
            alt="link google play"
            class="playstore cursor-pointer"
          />
          <img
            src="~/assets/images/soon_on.png"
            alt="link apple store"
            class="appstore cursor-pointer"
          />

        </div>
        <div></div>
      </div>
      <div class="relative col-span-5">
        <img
          class="tangan"
          src="~/assets/images/tangan2.png"
          alt="mockup dolin"
        />
      </div>
    </div>
    <div class="awan"></div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.cover {
  width: 100%;
  background: linear-gradient(
    128deg,
    rgba(101, 56, 251, 1) 0%,
    rgba(56, 245, 251, 1) 100%
  );
  height: inherit;
  position: relative;
}
.awan {
  position: absolute;
  bottom: 0;
  width: 100%;
  height: 3rem;
  background-image: url("../assets/images/sekat.png");
  background-size: cover;
  background-repeat: no-repeat;
}

@media (max-width:600px) {
  .playstore{
    height: 50px;
    width: 100px;
  }

  .appstore{
    height: 50px;
    width: 100px;
  }
}

@media (min-width:1900px){
  .content{
    font-size: 7rem;
  }
  .content-child{
    font-size: 2rem;
  }
  .tangan{
    width: 400px;
  }
  .awan{
    height: 5rem;
  }
}

@media (min-width:4400px){
  .content{
    font-size: 10rem;
  }
  .content-child{
    font-size: 4rem;
  }
  .tangan{
    /* top: 400px; */
    width: 400px;
  }
  .awan{
    height: 20rem;
  }
}

@media (min-width: 984px) {
  .tangan {
    position: absolute;
    bottom: 2rem;
    right: 2vw;
    max-width: 20rem;
  }
  .cover {
    width: 100%;
    background: linear-gradient(
      128deg,
      rgba(101, 56, 251, 1) 0%,
      rgba(56, 245, 251, 1) 100%
    );
    height: 100vh;
    position: relative;
  }
}
@media (min-width: 1212px) {
  .tangan {
    position: absolute;
    bottom: 2rem;
    right: 2vw;
    max-width: 30rem;
    /* width:2000px */
  }
}
@media (min-width: 1024px) {
  .tangan {
    position: absolute;
    bottom: 1.2rem;
    right: 0.1vw;
    max-width: 23rem;
  }
}
</style>
