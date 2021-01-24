<template>
  <div id="app">
    <div class="Student-Front">
      <center>
        <h1>Information Me & Friends</h1>
      </center>
  </div>
  <StudentProperty v-bind:StudentIndex="StudentProperty" />
  </div>
</template>

<script>
import StudentProperty from "./components/StudentProperty.vue";

export default {
  name: "App",
  components: {
    StudentProperty,
  },
  data(){
    return{
      StudentProperty:[
        {
          studentName: "KAH",
          studentId: "61234010",
          FirstName: "Nur-ateekah",
          LastName: "Salaeh",
          weight: 70,
          height: 152,
          picture: 
            "https://raw.githubusercontent.com/Sanura015/IMG/main/Kah.jpg",
        },
        {
          studentName: "NURA",
          studentId: "61234015",
          FirstName: "Sanura",
          LastName: "Chengoh",
          weight: 65,
          height: 158,
          picture: 
            "https://raw.githubusercontent.com/Sanura015/IMG/main/Nura.jpg",
        },
        {
          studentName: "GUN",
          studentId: "61234012",
          FirstName: "Naspat",
          LastName: "Stiramitakon",
          weight: 63,
          height: 162,
          picture: 
            "https://raw.githubusercontent.com/Sanura015/IMG/main/Gun.jpg",
        },
        {
          studentName: "YUI",
          studentId: "61234007",
          FirstName: "Suphakin",
          LastName: "Jaroenmak",
          weight: 55,
          height: 163,
          picture: 
            "https://raw.githubusercontent.com/Sanura015/IMG/main/Yui.png",
        },
        {
          studentName: "Pari",
          studentId: "61234013",
          FirstName: "Priyaphat",
          LastName: "Jaroerit",
          weight: 65,
          height: 160,
          picture: 
            "https://raw.githubusercontent.com/Sanura015/IMG/main/Pari.jpg",
        },
      ],
    };
  },
};
</script>

<style>
#app {
  font-family: "Sedgwick Ave Display", cursive;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 30px;
  font-size: 20px;
  padding: 20px 0px 0px 100px;
  background: rgb(158, 202, 228) ;
}

.Student-Front{
  font: size 50px;
  
}
</style>