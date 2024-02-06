<template>
    <div>
      <div class="page-header page-header-small">
        <parallax
          class="page-header-image"
          style="background-image: url('img/contacto.png')"
        >
        </parallax>
        <div class="content-center">
          <div class="container">
            <h1 class="title">CONTACTO</h1><br><br><br>
          </div>
        </div>
      </div>
      <div class="section section-about-us">
        <div class="container">
          <div class="row">
            <div class="col-md-6 text-center">
              <h2 style="background-color:#02945d; text-align:center;" class="text-white">TELÉFONOS</h2>
            </div>
            <div  class="col-md-6 text-center">
              <h2 style="background-color:#02945d; text-align:center;" class="text-white">CORREO</h2>
            </div>
          </div>
          <div class="button-container row">
            <card class="col-md-6">
                <div style="text-align:center;">
                    <h3 class="category"><i style="color:#0a0a0a;" class="fas fa-phone"></i> (722) 759-7609</h3>
                    <h3 class="category"><i style="color:#0a0a0a;" class="fas fa-phone"></i> (225) 101-7864</h3>
                </div>
            </card>
            <card class="col-md-6">
              <div >
                <h3 class="title"><i style="color:#026fe3;" class="fas fa-solid fa-envelope"></i> servasesoriacontable4.0@gmail.com</h3>
              </div>
            </card>
          </div>
          <div class="row">
            <div  class="col-md-12 text-center ">
              <h2 style="background-color:#02945d; text-align:center;" class="text-white">REDES SOCIALES</h2>
            </div>
          </div>
          <div class="button-container row">
            <card class="col-md-12 row">
                <div class="col-md-4 text-center ">
                  <a
                    class="nav-link"
                    rel="tooltip"
                    data-placement="bottom"
                    href="https://www.facebook.com/p/Innova-Crea-Construye-100063493114938/?paipv=0&eav=AfZVNfUoWQL4PuwXeYttEBVjY_rUUSKC7kypGqQZ0pA_tlAGa48IuzFYsU3Bv4v92O4&_rdr"
                    target="_blank"
                  >
                    <h3 class="category"><i style="color:#021894;" class="fab fa-brands fa-facebook"></i> FACEBOOK</h3>
                  </a>
                </div>
                <div class="col-md-4 text-center ">
                    <h3 class="category"><i style="color:#035c0c;" class="fab fa-brands fa-whatsapp"></i> (722) 759-7609</h3>
                </div>
                <div class="col-md-4 text-center ">
                  <a
                    class="nav-link"
                    rel="tooltip"
                    data-placement="bottom"
                    href="https://www.instagram.com/constructorabautista_/"
                    target="_blank"
                  >
                    <h3 class="category"><i style="color:#ab0000;" class="fab fa-brands fa-instagram"></i> INSTAGRAM</h3>
                  </a>
                 </div>
            </card>
          </div>
          <div class="row">
            <div class="col-md-6 text-center">
              <h2 style="background-color:#02945d; text-align:center;" class="text-white">UBICACIÓN</h2>
            </div>
            <div  class="col-md-6 text-center">
              <h2 style="background-color:#02945d; text-align:center;" class="text-white">COTIZA YA</h2>
            </div>
          </div>
          <div class="button-container row">
            <card class="col-md-6 text-center">
              <h6 class="title"><i style="color:#026fe3;" class="fas fa-solid fa-building"></i> Oficinas: Av. Tlaloc #26, Int LT24, Col. Niños Heroes 2, Municipio Valle de Chalco Solidaridad, Estado de México.</h6>
              <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3766.732916537732!2d-98.96053883018295!3d19.286039305505387!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x85ce1c451d79cab9%3A0xeed480f2270bcca9!2sAv%20Tlaloc%2026%2C%20Ni%C3%B1os%20Heroes%2C%2056610%20Valle%20de%20Chalco%20Solidaridad%2C%20M%C3%A9x.!5e0!3m2!1ses!2smx!4v1707197036523!5m2!1ses!2smx" width="520" height="450" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
            </card>
            <card class="col-md-6 card-body">
              <div class="text-center">
                <div class="">
                  <div class="col-md-12">
                    <label for="nombreC">Nombre Completo:</label>
                    <input type="text" class="form-control form-control-rounded"
                      v-model="form.nombreC"
                      placeholder="Escribe tu nombre completo"
                    >
                  </div>
                  <div class="col-md-12">
                    <label for="correoE">Correo Electrónico: </label>
                    <input type="text" class="form-control form-control-rounded"
                      v-model="form.correoE"
                      placeholder="Escribe tu correo electrónico"
                    >                  
                  </div>
                  <div class="col-md-12">
                    <label for="correoE">Teléfono: </label>
                    <input type="text" class="form-control form-control-rounded"
                      v-model="form.telefono"
                      placeholder="Escribe tu número de teléfono"
                    >                  
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlSelect1">Example select</label>
                    <select class="form-control" id="exampleFormControlSelect1">
                      <option>1</option>
                      <option>2</option>
                      <option>3</option>
                      <option>4</option>
                      <option>5</option>
                    </select>
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlSelect2">Example multiple select</label>
                    <select multiple class="form-control" id="exampleFormControlSelect2">
                      <option>1</option>
                      <option>2</option>
                      <option>3</option>
                      <option>4</option>
                      <option>5</option>
                    </select>
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlTextarea1">Domicilio:</label>
                    <textarea class="form-control" id="exampleFormControlTextarea1" rows="3"></textarea>
                  </div>
                </div>
              </div>
            </card>
          </div>
        </div>
      </div>
    </div>
  </template>
  <script>
  import { Button, FormGroupInput } from '@/components';
  export default {
    name: 'contacto',
    bodyClass: 'landing-page',
    components: {
      [Button.name]: Button,
      [FormGroupInput.name]: FormGroupInput,
    },
    data() {
      return {
        form: {
          nombreC: '',
          correoE: '',
          telefono: '',
          fecha: '',
          domicilio:'',
          catSolicitud:[],
          solicitud:0,
          catSubSolicitud:[],
          subSolicitud:0
        },
      };
    },
    methods:{
    }
  };
  </script>
  <style>
    .tab-content.tab-content-padding {
      padding: 20px;
    }
    .info {
      max-width: 360px;
      margin: 0 auto;
      padding: 70px 0 30px;
      text-align: center;
    }
    .card-background {
      background-position: 50%;
      background-size: cover;
      text-align: center;
    }
    .card-raised {
      -webkit-box-shadow: 0 20px 50px 0 rgba(0,0,0,.3);
      box-shadow: 0 20px 50px 0 rgba(0,0,0,.3);
    }
    .info-title {
      color:black;
      background-color: black;
    }
    .description {
      color: #9a9a9a;
      font-weight: 300;
    }
  </style>
  