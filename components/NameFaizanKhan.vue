<template>
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
</template>
<script>
export default {
  name: "NameFaizanKhan",
  data() {
    return {};
  },
};
</script>
