<script>
export default {
  name: "hero-section"
}
</script>

<template>
  <section class="hero">
    <div class="container">
      <div class="hero-inner">
        <div class="hero-copy">
          <h1 class="hero-title mt-0">Simplify your fleet management</h1>
          <p class="hero-paragraph">
            Struggling with vehicle breakdowns, missed trips, unhappy clients, or tracking driver locations?
          </p>
          <p class="hero-paragraph">
            Dereva Fleet Solutions takes care of all these challenges for you, allowing you to focus on expanding your
            business. Sign up now and experience seamless fleet management!
          </p>

          <div class="hero-form field field-grouped">
            <div class="control control-expanded">
              <input class="input" type="email" name="email" placeholder="Your email&hellip;">
            </div>
            <div class="control">
              <a class="button button-primary button-block">Early access</a>
            </div>
          </div>
        </div>
        <div class="hero-illustration">

          <img height="1988" width="3584" src="@/assets/images/hero-dashboard.png" alt="The dashboard view of dereva">


        </div>
      </div>
    </div>
  </section>
</template>

<style scoped lang="less">

</style>