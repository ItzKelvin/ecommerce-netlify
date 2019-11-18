<template>
  <section>
    <ul>
      <li>About you;</li>
      <li>Companie.</li>
      <li>Locatyons</li>
      <li>Kontakt</li>
      <li>Hoers</li>
    </ul>
    <ul>
      <li>Twytter</li>
      <li>Fakebook</li>
      <li>InstaKilo</li>
      <li>LinkedUt</li>
    </ul>
    <ul>
      <h4>Newsletter:</h4>
      <input type="text" />
    </ul>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
section {
  width: 80%;
  margin-left: 10%;
  padding: 40px 0;
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}

ul {
  list-style: none;
  padding-left: 0;
}

input {
  width: 100%;
}

@media screen and (min-width: 850px) {
  section {
    padding: 40px !important;
  }
}
</style>