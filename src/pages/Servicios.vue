<template>
    <div>
      <div class="page-header page-header-small">
        <parallax
          class="page-header-image"
          style="background-image: url('img/servicios.png')"
        >
        </parallax>
        <div class="content-center">
          <div class="container">
            <h1 class="title">SERVICIOS</h1>
          </div>
        </div>
      </div>
      <div class="section section-about-us">
        <div class="container">
          <div class="row">
            <div class="col-md-8 ml-auto mr-auto text-center">
              <h2 class="title">¿Que servicios ofrecemos?</h2>
            </div>
          </div>
          <div class="button-container">
            <tabs
              pills
              class="nav-align-center"
              tab-content-classes="gallery"
              tab-nav-classes="nav-pills-just-icons"
              type="neutral"
            >
              <tab-pane title="Cleaning">
                <!-- <i slot="label" class="now-ui-icons design_image"></i> -->
                <img slot="label" class="n-logo" src="img/cleaning.png" alt="" />
  
                <div class="col-md-10 ml-auto mr-auto">
                  <div class="row collections">
                    <div class="col-md-12">
                      <h3 class="title">CLEANING</h3>
                      <p class="category">Servicios de:</p>
                    </div>
                    <div class="col-md-12 ml-auto col-xl-12 mr-auto">
                        <card>
                            <tabs
                            slot="raw-content"
                            tab-content-classes="tab-content-padding text-center"
                            >
                            <tab-pane>
                                <template slot="label">
                                <!-- <i class="now-ui-icons objects_umbrella-13"></i>  -->
                                  <i class="fas fa-solid fa-hand-sparkles"></i> LIMPIEZA 
                                </template>
                                <div class="row">
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-limpieza.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza de Airbnb </h4><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-casaH.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h6 class="info-title"> Limpieza casa habitación-resindencial </h6><br><br><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-finaO.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza fina de obra </h4><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-gruesaO.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza gruesa de obra </h4><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-profunda.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza profunda </h4><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-lobbys.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza de lobbys </h4><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-recepcion.jfif&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza de recepción </h4><br><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-estacionamiento.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h5 class="info-title"> Limpieza de estacionamientos </h5><br><br><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-amenidadesE.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h4 class="info-title"> Limpieza de amenidades de edificios </h4><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                </div>
                            </tab-pane>
                            <tab-pane>
                                <template slot="label">
                                <i class="now-ui-icons shopping_cart-simple"></i> LAVADO
                                </template>
                                <div class="row">
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/lavado-aibnb.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h6 class="info-title"> Lavado de prendas de Airbnb </h6><br><br><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                </div>
                            </tab-pane>
                            <tab-pane>
                                <template slot="label">
                                <i class="now-ui-icons shopping_shop"></i> JARDINERíA
                                </template>
                                <div class="row">
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-jardineria.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h6 class="info-title"> Mantenimiento a jardinería </h6><br><br><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                </div>
                            </tab-pane>
                            <tab-pane>
                                <template slot="label">
                                <i class="now-ui-icons ui-2_settings-90"></i> REGISTRO Y CONTROL
                                </template>
                                <div class="row">
                                  <div class="col-md-4">
                                      <div  data-background-color="transparent" class="card card-raised card-background"  style="background-image: url(&quot;img/servicio-registro-control.jpg&quot;);">
                                          <div class="info">
                                              <div class="description">
                                                  <h6 class="info-title"> Alojamiento de Airbnb </h6><br><br><br><br>
                                              </div>
                                          </div>
                                      </div>
                                  </div>
                                </div>
                            </tab-pane>
                            </tabs>
                        </card>
                    </div>
                  </div>
                </div>
              </tab-pane>
  
              <tab-pane title="Innova">
                <!-- <i slot="label" class="now-ui-icons location_world"></i> -->
                <img slot="label" class="n-logo" src="img/innova.png" alt="" />
  
                <div class="col-md-10 ml-auto mr-auto">
                  <div class="row collections">
                    <div class="col-md-12">
                      <h3 class="title">INNOVA, CREA Y CONSTRUYE</h3>
                    </div>
                    <div class="col-md-4">
                      <p class="category">MISIÓN</p>
                      <h5 class="description">
                        An artist of considerable range, Ryan — the name taken by
                        Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and
                        records all of his own music, giving it a warm, intimate feel with a
                        solid groove structure. An artist of considerable range.
                      </h5>
                    </div>
                    <div class="col-md-4">
                      <p class="category">VISIÓN</p>
                      <h5 class="description">
                        An artist of considerable range, Ryan — the name taken by
                        Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and
                        records all of his own music, giving it a warm, intimate feel with a
                        solid groove structure. An artist of considerable range.
                      </h5>
                    </div>
                    <div class="col-md-4">
                      <p class="category">VALORES</p>
                      <h5 class="description">
                        An artist of considerable range, Ryan — the name taken by
                        Melbourne-raised, Brooklyn-based Nick Murphy — writes, performs and
                        records all of his own music, giving it a warm, intimate feel with a
                        solid groove structure. An artist of considerable range.
                      </h5>
                    </div>
                  </div>
                </div>
              </tab-pane>

            </tabs>
          </div>
        </div>
      </div>
    </div>
  </template>
  <script>
  import { Button, FormGroupInput, Tabs, TabPane } from '@/components';
  export default {
    name: 'servicios',
    components: {
      [Button.name]: Button,
      [FormGroupInput.name]: FormGroupInput,
      [Tabs.name]: Tabs,
      [TabPane.name]: TabPane,

    },
    data() {
      return {
        form: {
          firstName: '',
          email: '',
          message: ''
        }
      };
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
  