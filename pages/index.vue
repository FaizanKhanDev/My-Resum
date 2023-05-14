<template>
  <div class="container">
    <section class="section_left">
      <center>
        <img
          :src="require('~/assets/images/MyPics.jpeg')"
          alt="AUTHOR"
          class="author__picture"
        />
        <h1 class="title">Faizan Khan</h1>
      </center>
      <h5 class="sub-title">Contact</h5>
      <ul>
        <li>
          <span class="mdi mdi-phone"></span>
          +92 316-2177746
        </li>
        <li>
          <span class="mdi mdi-email-check-outline"></span>
          faizan480khan@gmail.com
        </li>
        <li>
          <span class="mdi mdi-search-web"></span>
          <a href="https://faizankhandev.netlify.app/" class="portfolio"
            >Visit to My Portfolio</a
          >
        </li>
      </ul>
      <h5 class="sub-title">Education</h5>
      <em>Average</em>
      <p>Matric, 2018 - 2020</p>
      <em>Higher</em>
      <p>Intermediate, 2020 - 2023 (Appeared)</p>

      <h5 class="sub-title">languages</h5>
      <label>Urdu</label>
      <div class="progress_container">
        <div class="progress_bar" style="width: 80%"></div>
      </div>
      <label>Pashto</label>
      <div class="progress_container">
        <div class="progress_bar" style="width: 80%"></div>
      </div>
      <label>English</label>
      <div class="progress_container">
        <div class="progress_bar" style="width: 30%"></div>
      </div>
    </section>
    <section class="section_right">
      <h1 class="title">About Me</h1>
      <p>Hi, I am Faizan</p>
      <p>Web Developer</p>
      <p>
        High level experience in web design and development knowledge, producing
        quality work.
      </p>
      <p>
        Web developer, with extensive knowledge and years of experience, working
        in web technologies and delivering quality work.
      </p>
      <h1 class="title">Experience</h1>
      <h5 class="sub-title">Development</h5>
      <p>01+ Year Experience in Web Development.</p>
      <!-- <em style="float: right">сентябрь, 2022</em>
      <h5 class="sub-title">Учитель начальных классов</h5> -->
      <!-- <p>МОУ «СОШ №38»</p>
      <em style="float: right">январь, 2023</em> -->

      <h1 class="title">Professional skills</h1>
      <table>
        <tr>
          <td>HTML 5 & CSS 3 / BootStrap</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 70%"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>JavaScript</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 60%"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>Vue/Nuxt Js</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 45%"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>Vuetify</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 40%"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>Node/Express Js</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 30%"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>Python/Django</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 43%"></div>
            </div>
          </td>
        </tr>
        <tr>
          <td>Git/GitHub</td>
          <td>
            <div class="progress_container">
              <div class="progress_bar" style="width: 35%"></div>
            </div>
          </td>
        </tr>
      </table>
    </section>
  </div>
</template>
<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Lato&family=Roboto&display=swap");
* {
  font-family: "Lato", sans-serif;
  /* font-family: 'Roboto', sans-serif; */
}
*,
html {
  scroll-behavior: smooth;
}
*,
*:after,
*:before {
  -webkit-box-sizing: border-box;
  -moz-box-sizing: border-box;
  box-sizing: border-box;
}
:root {
  scrollbar-color: rgb(210, 210, 210) rgb(46, 54, 69) !important;
  scrollbar-width: thin !important;
}
::-webkit-scrollbar {
  height: 12px;
  width: 8px;
  background: #000;
}
::-webkit-scrollbar-thumb {
  background: gray;
  -webkit-box-shadow: 0px 1px 2px rgba(0, 0, 0, 0.75);
}
::-webkit-scrollbar-corner {
  background: #000;
}

/*DEFAULT*/
body {
  margin: 0;
}
.author__picture {
  width: 270px !important;
  height: 270px !important;
}
.portfolio {
  color: #fff !important;
}
a {
  text-decoration: none;
}
ul {
  position: relative;
  left: -40px;
  width: 100%;
}
i {
  color: #3399ff;
  margin: 0 5px;
}
li {
  list-style: none;
  margin: 20px 0;
  width: 100%;
  line-height: 1.4em;
}
a,
li,
button {
  transition: 0.5s;
}
a {
  cursor: pointer;
}
b,
strong {
  font-weight: 700;
}
p,
li {
  line-height: 1.4em;
  letter-spacing: 0.08em;
}
em {
  color: #3399ff;
  font-weight: 700;
  font-size: 0.8em;
  display: block;
  font-style: normal;
}
label {
  color: #3399ff;
  font-weight: 700;
  font-size: 0.8em;
  display: block;
  margin: 10px 0;
}
img {
  width: 90%;
  height: 90%;
  margin: auto;
}
.title {
  font-size: 2em;
  /* font-family: "Ubuntu", sans-serif; */
  font-weight: 700;
}
.sub-title {
  font-size: 1em;
  font-weight: 400;
  color: gray;
  line-height: 1em;
}

/*CONTAINER*/
.container {
  width: 100%;
  position: relative;
}

.container .section_left {
  width: 25%;
  padding: 20px;
  background: #1b2631;
  color: #fff;
}

.container .section_left img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin: auto;
}

.container .progress_container {
  width: 90%;
  height: 10px;
  border-radius: 20px;
  background: #1e1e1e;
}

.container .progress_container .progress_bar {
  background: #3399ff;
  border-radius: 20px;
  height: 10px;
}

.container .section_right {
  padding: 30px;
  width: 75%;
  float: right;
  position: absolute;
  top: 0;
  right: 0;
}

.container .section_right table {
  width: 100%;
}

.container .section_right table td {
  padding: 10px;
}

.container .section_right table td:nth-child(1) {
  width: 20%;
  font-weight: bold;
}

@media (max-width: 920px) {
  .container .section_left {
    width: 100%;
    display: block;
  }
  .container .section_right {
    width: 100%;
    position: static;
    display: block;
  }
}
</style>
<script>
export default {
  name: "IndexPage",
};
</script>
