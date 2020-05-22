<template>
  <footer class="page-footer font-small cyan darken-3 bg-info">
    <!-- Footer Elements -->
    <div class="container">
      <!-- Grid row-->
      <div class="row">
        <!-- Grid column -->
        <div class="col-md-12 py-5">
          <div class="mb-5 flex-center">
            <div class="row">

              <div class="h2 col-1 offset-5" >
                <a href="http://oscarislasoliver.web.app" class="text-dark">
                  <b-icon href='' icon="tv" id="web"></b-icon>
                </a>
              </div>

              <div class="h2 col-1 ">
                <a href="mailto: oscar.islas@uabc.edu.mx" class="text-dark">
                  <b-icon icon="envelope" id="correo" ></b-icon>
                </a>
              </div>

              <div class="h2 col-1" >
                <a href="tel:+52 6645238750" class="text-dark">
                  <b-icon href='' icon="phone" id="tel"></b-icon>
                </a> 
              </div>

            </div>
          </div>
        </div>
        <!-- Grid column -->
      </div>
      <!-- Grid row-->
    </div>
    <!-- Footer Elements -->
    <!-- Copyright -->
    <div class="footer-copyright text-center page py-3 text-white">© 2020 Made by:
      <a href=""> Oscar Islas</a>
    </div>
    <!-- Copyright -->

    <!--pop over-->
      <b-popover
      target="web"
      placement="top"
      title="Web"
      triggers="hover focus"
      content="oscarislasoliver.web.app"
    ></b-popover>

    <b-popover
      target="correo"
      placement="top"
      title="Correo"
      triggers="hover focus"
      content="oscar.islas@uabc.edu.mx"
    ></b-popover>

    <b-popover
      target="tel"
      placement="top"
      title="Telefono"
      triggers="hover focus"
      content="664-5238750"
    ></b-popover>

  </footer>

</template>

<script>
export default {
    name: 'fotter'
}
</script>

<style lang="scss" scoped>
.page{
  background-color: #117382;
}
</style>>