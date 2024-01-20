<template>
  <div class="home">
    <h1 class="header">Anna-Maria Eriksson</h1>
    <h2 class="tagline">Otroligt driven (webb)utvecklare!</h2>
    <div class="hero">
      <p>
        Jag heter Anna-Maria Eriksson och jag vill jobba med webben om jag får
        välja!
      </p>
      <p>
        Jag är extremt driven, nyfiken, hjälpsam, frågvis och helt underbar att
        jobba med. Det säger i alla fall de företag som gett mig en möjlighet
        att visa vad jag går för.
      </p>
      <p>
        Sidan här uppdateras allt eftersom. Jag har en del projekt, och vill du
        ha länk till dem, kontakta mig på
        <a href="https://linkedin.com/annamariaeriksson"> LinkedIn</a>.
      </p>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style>
.home {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
.header,
.tagline {
  grid-column: 1;
}
</style>
