<template>
    <div class="flex-wrapper">


     <UtilsNavbar />


    <main id="main">

        <Nuxt />
        
    </main><!-- End #main -->

    <!-- ======= Footer ======= -->
    <UtilsFooter  class="footer"/>
    </div>
</template>

<style>
.flex-wrapper {
  display: flex;
  min-height: 100vh;
  flex-direction: column;
  justify-content: flex-start;
}

.footer {
  margin-top: auto;
}
</style>