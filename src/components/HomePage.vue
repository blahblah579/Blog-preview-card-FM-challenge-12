<template>
  <v-container>
    <v-row class="body mx-auto d-flex flex-column text-black pa-5">
      <v-col class="d-flex justify-center pa-0">
        <img class="img" src="/src/assets/illustration-article.svg" alt="" />
      </v-col>

      <v-col class="pa-0 d-flex align-center mt-4">
        <span class="learning pa-1 px-2">Learning</span>
      </v-col>
      <v-col class="pa-0 d-flex flex-column justify-space-between">
        <span class="pub">Published 23 Sept 2024</span>
        <div class="heading my-2 mb-3">HTML & CSS foundations</div></v-col
      >
      <v-col class="pa-0"
        ><div class="text">
          These languages are the backbone of every website, defining structure,
          content and presentation.
        </div></v-col
      >
      <v-col class="pa-0 d-flex align-center mt-4">
        <v-avatar>
          <v-img class="" alt="" src="/src/assets/1.jpg"></v-img>
        </v-avatar>
        <div class="name ml-3">Abhishek Negi</div>
      </v-col>
    </v-row>
  </v-container>
</template>
  
  <script setup>
</script>
  
  <style scoped>
@font-face {
  font-family: f1;
  src: url(/src/assets/Figtree-ExtraBold.ttf);
}
@font-face {
  font-family: f2;
  src: url(/src/assets/Figtree-SemiBold.ttf);
}
.body {
  width: 338px;
  height: 470px;
  background-color: hsl(0, 0%, 100%); /* White card */
  border-radius: 20px;
  border: 1.5px solid black;
  position: relative; /* Ensure the shadow is positioned relative to the card */
  box-shadow: 8px 8px 0px 0px rgba(0, 0, 0, 1); /* Strong black shadow */
}
.img {
  width: 100%;
  border-radius: 10px;
}
.learning {
  font-family: f1;
  background-color: hsl(47, 87%, 64%);
  border-radius: 4px;
  font-size: 12px;
}
.pub {
  font-size: 12px;
  font-family: f2;
}
.heading {
  /* color: hsl(47, 89%, 63%); */
  color: black;
  font-family: f1;
  font-size: 24px;
}
.heading:hover {
  color: hsl(47, 89%, 63%);
  cursor: pointer;
}
.text {
  color: hsl(0, 0%, 47%);
  font-size: 14px;
}
.name {
  font-family: f1;
  font-size: 14px;
}

@media (max-width: 600px) {
  .body {
    width: 330px;
    height: 490px;
  }
}
</style>
  