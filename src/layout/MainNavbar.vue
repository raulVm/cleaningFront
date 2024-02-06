<template>
  <navbar
    position="fixed"
    type="info"
    :transparent="transparent"
    :color-on-scroll="colorOnScroll"
    menu-classes="ml-auto"
  >
    <template>
      <router-link v-popover:popover1 class="navbar-brand" to="/">
        Inicio
      </router-link>
      <el-popover
        ref="popover1"
        popper-class="popover"
        placement="bottom"
        width="200"
        trigger="hover"
      >
        <div class="popover-body">
          Designed by Invision. Coded by Creative Tim
        </div>
      </el-popover>
    </template>
    <template slot="navbar-menu">
      <li class="nav-item">
        <router-link to="/nosotros">
          <a
            class="nav-link"
          >
            <i class="now-ui-icons business_bank"></i>
            <p>Nosotros</p>
          </a>
        </router-link>
      </li>
      <li class="nav-item">
        <router-link to="/servicios">
          <a
            class="nav-link"
          >
            <i class="now-ui-icons design_vector"></i>
            <p>Servicios</p>
          </a>
        </router-link>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          href="https://www.creative-tim.com/product/vue-now-ui-kit"
          target="_blank"
        >
          <i class="now-ui-icons arrows-1_refresh-69"></i>
          <p>Proceso</p>
        </a>
      </li>
      <!-- <drop-down
        tag="li"
        title="Components"
        icon="now-ui-icons design_app"
        class="nav-item"
      >
        <nav-link to="/">
          <i class="now-ui-icons business_chart-pie-36"></i> Servicios
        </nav-link>
        <a
          href="https://demos.creative-tim.com/vue-now-ui-kit/documentation"
          target="_blank"
          class="dropdown-item"
        >
          <i class="now-ui-icons design_bullet-list-67"></i> Documentation
        </a>
      </drop-down> -->
      <li class="nav-item">
        <router-link to="/contacto">
          <a
            class="nav-link"
          >
            <i class="now-ui-icons design_vector"></i>
            <p>CONTACTO</p>
          </a>
        </router-link>
      </li>

      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Follow us on Twitter"
          data-placement="bottom"
          href="https://twitter.com/CreativeTim"
          target="_blank"
        >
          <i class="fab fa-twitter"></i>
          <p class="d-lg-none d-xl-none">Twitter</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Siguenos en Facebook"
          data-placement="bottom"
          href="https://www.facebook.com/p/Innova-Crea-Construye-100063493114938/?paipv=0&eav=AfZVNfUoWQL4PuwXeYttEBVjY_rUUSKC7kypGqQZ0pA_tlAGa48IuzFYsU3Bv4v92O4&_rdr"
          target="_blank"
        >
          <i class="fab fa-facebook-square"></i>
          <p class="d-lg-none d-xl-none">Facebook</p>
        </a>
      </li>
      <li class="nav-item">
        <a
          class="nav-link"
          rel="tooltip"
          title="Siguenos en Instagram"
          data-placement="bottom"
          href="https://www.instagram.com/constructorabautista_/"
          target="_blank"
        >
          <i class="fab fa-instagram"></i>
          <p class="d-lg-none d-xl-none">Instagram</p>
        </a>
      </li>
    </template>
  </navbar>
</template>

<script>
import { DropDown, Navbar, NavLink } from '@/components';
import { Popover } from 'element-ui';
export default {
  name: 'main-navbar',
  props: {
    transparent: Boolean,
    colorOnScroll: Number
  },
  components: {
    // DropDown,
    Navbar,
    // NavLink,
    [Popover.name]: Popover
  }
};
</script>

<style scoped></style>
