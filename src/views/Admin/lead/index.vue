<template>
  <div>
    <b-navbar toggleable="sm" type="dark" variant="info" >
      <b-navbar-brand href="#">
        <img src="@/assets/img/logo.gif" width="150px" alt="">
      </b-navbar-brand>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>

        <!-- Right aligned nav items -->
        <b-navbar-nav class="ml-auto">

          <b-nav-form>
            <b-button size="sm" class="my-2 my-sm-0" type="submit">Salir</b-button>
          </b-nav-form>
          
          <b-nav-item-dropdown text="Lang" right>
            <b-dropdown-item href="#">EN</b-dropdown-item>
            <b-dropdown-item href="#">ES</b-dropdown-item>

          </b-nav-item-dropdown>

        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
export default {
    name: 'lead'
}
</script>>