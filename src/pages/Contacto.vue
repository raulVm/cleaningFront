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
              <div class="">
                <div class="">
                  <div class="col-md-12">
                    <label for="nombreC">Nombre Completo: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <input type="text" class="form-control form-control-rounded"
                      v-model="form.nombreC"
                      placeholder="Escribe tu nombre completo"
                    >
                    <span v-if="error.nombreC" class="error">{{error.mensaje}}</span>
                  </div>
                  <div class="col-md-12">
                    <label for="correoE">Correo Electrónico: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <input type="email" class="form-control form-control-rounded"
                      v-model="form.correoE"
                      placeholder="Escribe tu correo electrónico"
                    >    
                    <span v-if="error.correoE" class="error">{{error.mensaje}}</span>              
                  </div>
                  <div class="col-md-12">
                    <label for="correoE">Teléfono: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <input type="text" class="form-control form-control-rounded"
                      v-model="form.telefono"
                      placeholder="Escribe tu número de teléfono"
                    >     
                    <span v-if="error.telefono" class="error">{{error.mensaje}}</span>             
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlSelect1">Estado: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <v-select
                      placeholder="Selecciona el estado"
                      label="Estado:"
                      :options="opcionesEstado"
                      v-model="form.estado"
                      @input="OpcionesEstado(form.estado)"
                      :getOptionLabel="estados => estados.nombre"
                    ></v-select>
                    <span v-if="error.estado" class="error">{{error.mensaje}}</span>
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlSelect2">Municipio: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <v-select
                      placeholder="Selecciona el municipio"
                      label="Municipio:"
                      :options="opcionesMunicipio"
                      v-model="form.municipio"
                      @input="OpcionesMunicipio(form.municipio)"
                      :disabled="disableMunicipio"
                      :getOptionLabel="municipios => municipios.nombre"
                    ></v-select>
                    <span v-if="error.municipio" class="error">{{error.mensaje}}</span>
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlSelect1">Localidad:</label>
                    <v-select
                      placeholder="Selecciona la localidad"
                      label="Localidad:"
                      :options="opcionesLocalidades"
                      v-model="form.localidad"
                      :disabled="disableLocalidad"
                      :getOptionLabel="localidades => localidades.nombre"
                    ></v-select>
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlSelect1">Colonia:</label>
                    <v-select
                      placeholder="Selecciona la colonia"
                      label="Colonia:"
                      :options="opcionesColonias"
                      v-model="form.colonia"
                      :disabled="disableColonia"
                      :getOptionLabel="colonias => colonias.asentamiento"
                    ></v-select>
                  </div>
                  <div class="col-md-12">
                    <label for="servicio">Servicio: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <v-select
                      placeholder="Selecciona el servicio"
                      label="Servicio:"
                      :options="opcionesServicio"
                      v-model="form.servicio"
                      :disabled="disableServicio"
                      multiple
                    ></v-select>   
                    <span v-if="error.servicio" class="error">{{error.mensaje}}</span>        
                  </div>
                  <div class="col-md-12">
                    <label for="exampleFormControlTextarea1">Descripción breve del servicio: <span style="color: #ab0000;font-size: 20px">*</span></label>
                    <textarea class="form-control form-control-rounded" v-model="form.descripcion" rows="3"></textarea>
                    <span v-if="error.descripcion" class="error">{{error.mensaje}}</span>
                  </div>
                  <div class="col-md-12">
                    <button  @click="Guardar()" type="submit" class="btn btn-info btn-lg btn-block">Enviar</button>
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
  // import instance from '../components/index';
  import axios from 'axios';

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
          estado: '',
          municipio: '',
          localidad: '',
          colonia: '',
          servicio: [],
          descripcion: '',
        },
        url:'http://127.0.0.1:8000/api',
        opcionesEstado: [],
        opcionesMunicipio: [],
        opcionesLocalidades: [],
        opcionesColonias: [],
        disableMunicipio: true,
        disableLocalidad: true,
        disableColonia: true,
        disableServicio: false,
        opcionesServicio: ['Innova, Crea y Construye', 'Clening'],
        error:{
          nombreC: false,
          correoE: false,
          telefono: false,
          estado: false,
          municipio: false,
          servicio: false,
          descripcion: false,
          mensaje: 'Este campo es requerido'
        }
      };
    },
    mounted() {
      this.getEstados();
    },
    methods:{
      getEstados(){
        axios.get(this.url + '/catalogo/estados')
        .then(response => {
          this.opcionesEstado = response.data;
        })
      },
      getMunicipios(data){
        axios.get(this.url + '/catalogo/municipios/'+data)
        .then(response => {
          this.opcionesMunicipio = response.data;
        })
      },
      getLocalidades(estado,mun){
        axios.get(this.url + '/catalogo/localidades/'+ estado + '/'+ mun)
        .then(response => {
          this.opcionesLocalidades = response.data;
        })
      },
      getColonias(estado,mun){
        axios.get(this.url + '/catalogo/colonias/'+ estado + '/'+ mun)
        .then(response => {
          this.opcionesColonias = response.data;
        })
      },
      OpcionesEstado(data){
        this.disableMunicipio = false;
        this.disableLocalidad = true;
        this.disableColonia = true;
        this.form.localidad = '';
        this.form.colonia = '';
        this.form.municipio = '';
        this.getMunicipios(data.id);
      },
      OpcionesMunicipio(data){
        this.disableLocalidad = false;
        this.disableColonia = false;
        this.form.localidad = '';
        this.form.colonia = '';
        this.getLocalidades(this.form.estado.id,data.cve_mun);
        this.getColonias(this.form.estado.id,data.cve_mun);
      },
      async Guardar(e){
        console.log(this.form);
        (!this.form.nombreC)?this.error.nombreC = true: this.error.nombreC = false;
        (!this.form.correoE)?this.error.correoE = true: this.error.correoE = false;
        (!this.form.telefono)?this.error.telefono = true: this.error.telefono = false;
        (!this.form.estado)?this.error.estado = true: this.error.estado = false;
        (!this.form.municipio)?this.error.municipio = true: this.error.municipio = false;
        (this.form.servicio.length == 0)?this.error.servicio = true: this.error.servicio = false;
        (!this.form.descripcion)?this.error.descripcion = true: this.error.descripcion = false;
        if(this.error.nombreC == false && this.error.correoE == false && this.error.telefono == false
          && this.error.estado == false && this.error.municipio == false &&this.error.servicio == false &&
          this.error.descripcion == false){
            let solicitud = {
              nombre_completo: this.form.nombreC, correo_electronico: this.form.correoE,
              telefono: this.form.telefono, id_estado: this.form.estado, id_municipio: this.form.municipio,
              id_localidad: this.form.localidad ,id_colonia: this.form.colonia,
              servicio:this.form.servicio, descripcion: this.form.descripcion
            }
          console.log('enviar solicitud saveSolicitud',solicitud);
          let api = axios.post(this.url + `/saveSolicitud`, solicitud);
          api.then((res) => {
            swal({
              title: 'Solicitud Registrada',
              text: 'La solicitud se ha enviado correctamente',
              type: 'success',
              confirmButtonText: 'Aceptar',
              allowOutsideClick: false,
              allowEscapeKey: false,
            })
            .then((button) => {
              if (button) {

              }
            });
          }).catch(function (error){
          });
        }else{
          console.log('no se puede enviar solicitud');
        }
      }
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
    .error {
      color:red;
    }
  </style>
  