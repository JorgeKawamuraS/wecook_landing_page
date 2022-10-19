<template>
  <v-app>
    <v-app-bar
      app
      color="#C44C04"
      dark
    >
      <strong style="font-size: 30px;font-family: 'Montserrat'">WeCook</strong>

      <v-spacer></v-spacer>
      <v-toolbar-items>
        <v-btn text style="font-size: 25px;font-family: 'Montserrat';font-weight: bold">Inicio</v-btn>
        <v-btn text style="font-size: 25px;font-family: 'Montserrat';font-weight: bold">Recetas</v-btn>
        <v-btn text style="font-size: 25px;font-family: 'Montserrat';font-weight: bold">Crear Receta</v-btn>
        <v-btn text style="font-size: 25px;font-family: 'Montserrat';font-weight: bold">Iniciar Sesión</v-btn>
      </v-toolbar-items>


    </v-app-bar>

    <v-main>
      <div style="background-color: rgba(0, 0, 0, 0.5)">
      <div style="height: 5%">
        <v-img src="./assets/fondopri.png" >
          <div style="background-color: rgba(0, 0, 0, 0.5);height: 100%">
            <v-container>
              <v-row class="text-center">
                <v-col cols="12" style="margin-top: 10%">
                  <strong style="font-size: 48px;color: white;font-family: 'Montserrat';font-weight: bold">
                    Encuentra la receta que necesitas
                    <br> en un solo click
                  </strong>
                  <div style="margin-top: 2%">
                    <v-btn color="#C44C04" style="padding-top: 35px;padding-bottom: 35px;padding-left: 50px;padding-right: 50px">
                      <strong style="color: white;font-size: 20px;font-family: 'Montserrat';font-weight: bold" >
                        Comenzar ahora
                      </strong>
                    </v-btn>
                  </div>
                </v-col>
              </v-row>
            </v-container>
          </div>
        </v-img>
      </div>
      </div>
      <div style="background: #732712">
        <v-container>
          <v-row class="text-center">
            <v-col cols="12" style="display: flex; flex-direction: row;justify-content: space-between">
              <div style="display: flex; flex-direction: column;margin-top: 4%;margin-bottom: 4%">
                <div style="display: flex; justify-content: center">
                  <img src="./assets/lupa.png" style="width: 30%;margin-right: 5%">
                </div>
                <strong style="color: white; margin-top: 10px;font-size: 25px;font-family: 'Montserrat'">Sistema de búsqueda <br> completo y sencillo de usar</strong>
              </div>
              <div style="display: flex; flex-direction: column;margin-top: 4%;margin-bottom: 4%">
                <div style="display: flex; justify-content: center">
                  <img src="./assets/personas.png"  style="width: 45%">
                </div>
                <strong style="color: white; margin-top: 10px;font-size: 25px;font-family: 'Montserrat'">Canal directo para compartir <br> opiniones de las recetas que <br> visites</strong>
              </div>
              <div style="display: flex; flex-direction: column;margin-top: 4%;margin-bottom: 3%">
                <div style="display: flex; justify-content: center">
                  <img src="./assets/money.png"  style="width: 30%">
                </div>
                <strong style="color: white; margin-top: 10px;font-size: 25px;font-family: 'Montserrat'">Ganancia por medio de <br> comisiones por otros usuarios</strong>
              </div>
            </v-col>

          </v-row>
        </v-container>
      </div>
      <div style="display: flex; flex-direction: row">
        <div style="width: 50%">
          <v-img src="./assets/fondo1.png">
          </v-img>
        </div>
        <div style="background: #C44C04; width: 50%">
          <v-container>
            <v-row>
              <v-col cols="12" style="display: flex; flex-direction: column;margin-top: 18%;margin-left: 5%">
                <strong style="font-size: 50px; color: white;font-family: 'Montserrat'">Comparte Recetas</strong>
                <strong style="font-size: 40px; color: white;font-weight: lighter;font-family: 'Montserrat';margin-top: 5%">Comparte recetas con nuetras
                        <br>comunidad y recibe ganancias a
                        <br>medida que aumenta tu popularidad</strong>
              </v-col>
            </v-row>
          </v-container>
        </div>

      </div>
      <div style="display: flex; flex-direction: row">
        <div style="background: #89250A; width: 50%">
          <v-container>
            <v-row>
              <v-col cols="12" style="display: flex; flex-direction: column;margin-top: 14%;margin-left: 5%">
                <strong style="font-size: 50px; color: white;font-family: 'Montserrat'">Aprende nuevas recetas</strong>
                <strong style="font-size: 40px; color: white;font-weight: lighter;font-family: 'Montserrat';margin-top: 5%">Aprende a cocinar nuevos platos
                  <br>y expande tus conocimientos
                  <br>culinarios</strong>
              </v-col>
            </v-row>
          </v-container>
        </div>
        <div style="width: 50%">
          <v-img src="./assets/fondo2.png">
          </v-img>
        </div>

      </div>

    </v-main>

    <v-footer color="#000000">
      <v-container class="lg1">
        <div style="display: flex;flex-direction: row;justify-content: space-between;flex-wrap: wrap">
          <div style="display: flex;flex-direction: column">
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat';margin-top: 5%">Política de privacidad</v-btn>
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat';margin-top: 5%">Política de cookies</v-btn>
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat';margin-top: 5%">Política de calidad</v-btn>
          </div>
          <div style="display: flex;flex-direction: column">
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat' ;margin-top: 10%">WeCook</v-btn>
            <div style="display: flex;flex-direction: row;margin-top: 10%">
              <v-btn  color="#000000">
                <v-icon
                    color="#FFFFFF">
                  mdi-facebook
                </v-icon>
              </v-btn>
              <v-btn color="#000000">
                <v-icon
                    color="#FFFFFF">
                  mdi-instagram
                </v-icon>
              </v-btn>
              <v-btn  color="#000000" >
                <v-icon
                    color="#FFFFFF">
                  mdi-youtube
                </v-icon>
              </v-btn>
              <v-btn  color="#000000">
                <v-icon
                    color="#FFFFFF">
                  mdi-twitter
                </v-icon>
              </v-btn>
            </div>
          </div>
          <div style="display: flex;flex-direction: column">
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat';margin-top: 5%">WeCook</v-btn>
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat';margin-top: 5%">Contacto</v-btn>
            <v-btn text color="#FFFFFF" style="font-size: 20px;font-family: 'Montserrat';margin-top: 5%">FAQs</v-btn>
          </div>
        </div>
      </v-container>
    </v-footer>
  </v-app>
</template>

<script>

export default {
  name: 'App',

  data: () => ({
    //
  }),
};
</script>
