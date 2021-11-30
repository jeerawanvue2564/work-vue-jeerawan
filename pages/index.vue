<template>
  <div>
    <v-row justify="center" align="center">
      <v-col cols="12" sm="8" md="6">
        <div
          class="pa-7 white rounded-circle d-inline-block"
        >
          <!-- <v-icon large color="blue">
            mdi-cloud-upload
          </v-icon> -->
          <i
            class="fas fa-university"
            style="color: rgb(70, 70, 226); font-size:40px;"
          />
        </div>
      </v-col>
    </v-row>
    <h1 style="margin-top:20px;">
      KNN BANK
    </h1>
    <h3>MOBILE APP</h3>
    <v-form>
      <v-container>
        <v-row>
          <v-col
            cols="12"
            sm="6"
            md="4"
          >
            <v-menu transition="scroll-y-transition">
              <template #activator="{ on, attrs }">
                <v-text-field
                  label="PLEATE ENTER YOUR PASSWORD"
                  placeholder="PASSWORD"
                  filled
                  rounded
                  dense
                  v-bind="attrs"
                  v-on="on"
                />
              </template>
              <div class="box">
                <v-row>
                  <v-col class="d-flex justify-center">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      1
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      2
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      3
                    </v-btn>
                  </v-col>
                </v-row>

                <v-row>
                  <v-col class="d-flex justify-center">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      4
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      5
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      6
                    </v-btn>
                  </v-col>
                </v-row>

                <v-row>
                  <v-col class="d-flex justify-center">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      7
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      8
                    </v-btn>
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      9
                    </v-btn>
                  </v-col>
                </v-row>

                <v-row>
                  <v-col class="d-flex justify-center">
                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="primary"
                    >
                      0
                    </v-btn>

                    <v-btn
                      class="mx-2"
                      fab
                      dark
                      color="warning"
                    >
                      <i class="fas fa-times" />
                    </v-btn>
                  </v-col>
                </v-row>
              </div>
            </v-menu>
            <v-btn class="btn1">
              <span class="txt1">LOG IN</span>
            </v-btn>
            <p>Forgot password?</p>
            <p>New to Bank Apps? Sign Up</p>
          </v-col>
        </v-row>
      </v-container>
    </v-form>
  </div>
</template>

<style>
 .pa-7 {
   margin-top: 100px;
 }

h3{
  margin-bottom: 50px;
}

.txt1 {
  color: brown;
}

.btn1 {
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-bottom: 60px;
}

.box {
  background-color: white;
  padding: 5px;
  border-radius: 25px;
  font-size: 18px;
}
</style>
