<template>
  <div class="about">
    <h1>About</h1>
    <p>
      Have you heard about Bitcoin recently?
      <br />
      <br />
      Do you want to know how it is different from and superior to the rest of
      the other cryptocurrencies?
      <br />
      <br />
      Already deep in the rabbit hole, enjoying your discovery of this
      revolutionary technology?
      <br />
      <br />
      Whatever level of knowledge or interest you have in Bitcoin, you are
      welcome to join us.
      <br />
      <br />
      Come meet fellow Bitcoiners in the Shenandoah area — share, learn, and
      have fun!
      <br />
      <br />
      See you soon.
    </p>
    --------------------------------------------------------------------------------
    <p>
      Meeting occurring monthly at various locations around the Winchester, VA
      area.
    </p>
    <p>Run by Gary Krause, a software engineer and a bitcoin enthusiast.</p>
    <p>If you're interested in more information, please contact me.</p>
    <h3>Contact</h3>
    <ul>
      <li>
        <a href="mailto:gary@codechief.dev" class="ml-md-auto"
          >gary@codechief.dev</a
        >
      </li>
      <li>
        <a href="https://codechief.dev" target="_blank" class="ml-md-auto"
          >Code Chief LLC</a
        >
      </li>
      <li>
        <a
          href="https://www.linkedin.com/in/garyray-k/"
          target="_blank"
          class="ml-md-auto"
          >LinkedIn</a
        >
      </li>
      <li>
        <a
          href="https://twitter.com/garyKrause_"
          target="_blank"
          class="ml-md-auto"
          >Twitter:</a
        >
        @garyKrause_
      </li>
    </ul>
    <h4>
      <a
        href="https://github.com/CodeChiefDotDev/shenandoahbitcoinclub/issues"
        target="_blank"
        class="ml-md-auto"
      >
        See an Error on this site?</a
      >
    </h4>
  </div>
</template>
<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "About",
});
</script>
<style scoped>
h3 {
  margin: 40px 0 0;
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}

p {
  word-break: break-word;
  overflow-wrap: break-word;
  padding: 20px;
  align-self: center;
  align-content: center;
  max-width: 750px;
  margin: auto;
}
</style>
