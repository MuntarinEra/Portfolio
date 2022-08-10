<template>
<v-app  id="home" :style="{ background: $vuetify.theme.themes.dark.background }">
<NavBar />
<v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="1.jpg" contain max-height="400"></v-img>
        </v-col>
         <v-col cols="7">
          <h1 class="purple--text" >My name is MUN TARIN JANNAT ERA</h1>
          <p class="purple--text">
            I have completed my undergraduation from BRACU in 2022. <br />
            My CGPA is 3.84.
            <br />
            I have done my O'level and A'level from Maple Leaf International School.
          </p>
          <v-btn title color="#8B008B" dark>about me</v-btn>
          
         </v-col>
         <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1">
                  <v-icon color="#8B008B" x-large class="ml-3">mdi-shopping</v-icon>
                   <h3 class="purple--text ml-3 mt-4"> E-commerce Shopping</h3>
                  <p class="purple--text ml-3 mt-6">
                    The website was designed using MVC. <br />The website was designed using php.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2">
                  <v-icon color="#8B008B" x-large class="ml-3" dark
                    >mdi-apps</v-icon
                  >
                  <h3 class="purple--text ml-3 mt-4">App</h3>
                  <p class="purple--text ml-3 mt-6">
                  This application was built for thesis purposes.<br/> This
application used to predict what type of <br/> skin disease it is when an image was uploaded <br />The app was built using streamlit
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1">
                  <v-icon color="#8B008B" x-large class="ml-3"
                    >mdi-database</v-icon
                  >
                  <h3 class="purple--text ml-3 mt-4">Criminal Database</h3>
                  <p class="purple--text ml-3 mt-6">
                     This system was used to control role-based login.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
            </v-row>
          </div>
         </v-col>
         <v-col cols="8" >
          <div class="second">
            <div class="secondchild1" id="contact">
              <h1 class="black--text ml-3 mt-6">Below is the contact detail:</h1>
              <h2 class="black--text ml-3 mt-6">Phone Number: 01875491527 </h2>
              <h2 class="black--text ml-3 mt-6">Email: muntarinjannat@gmail.com </h2>
              <h2 class="black--text ml-3 mt-6">Git link: https://github.com/MuntarinEra </h2>
            
              
              
             
              
            </div>
          </div>
         </v-col>
      </v-row>
</v-container>
</v-app>
  
</template>

<script>
  import NavBar from '../components/NavBar'

  export default {
    name: 'HomeView',

    components: {
      NavBar,
    },
  }
</script>
<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
  text-align: center;
}
.first {
  margin-top: 300px;
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #E6E6FA,
    #E6E6FA 50%,
    #E6E6FA 50%,
   #E6E6FA  50%
  );
  text-align: center;
  padding: 2rem 2rem;
  padding-top: 100px;
}
.second {
  width: 100%;
  height: 400px;
  background: #E6E6FA;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: left;
  background-color: #E6E6FA;
 
  vertical-align: middle;
  text-align: left;
  font-size: 100;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #DA70D6 ;
}
.bgColor2 {
  background-color: #d39bcb ;
}
.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 70px;
  font-weight: bold;
}
</style>
