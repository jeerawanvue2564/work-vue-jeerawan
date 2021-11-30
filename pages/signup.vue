<template>
  <div>
    <v-card
      vlevation="3"
      light
      class="box"
    >
      <v-row justify="center" align="center">
        <v-col cols="12" sm="8" md="6" />
      </v-row>
      <div class="box">
        <p style="color : rgb(70, 70, 226);font-size:15px">
          Sign up your bank account
        </p>

        <v-form>
          <v-container>
            <v-row style="padding-top: 1px;">
              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Your Name"
                  outlined
                  dense
                />
              </v-col>
            </v-row>

            <v-row style="margin-top:-2rem;">
              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Bank Account"
                  outlined
                  dense
                />
              </v-col>
            </v-row>

            <v-row style="margin-top:-2rem;">
              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Mobile phone number"
                  outlined
                  dense
                />
              </v-col>
            </v-row>

            <v-row style="margin-top:-2rem;">
              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Email"
                  outlined
                  dense
                />
              </v-col>
            </v-row>

            <v-row style="margin-top:-2rem;">
              <v-col
                cols="12"
                sm="6"
                md="3"
              >
                <v-text-field
                  label="Password"
                  append-icon="mdi-eye"
                  outlined
                  dense
                />
              </v-col>
            </v-row>
          </v-container>
        </v-form>
        <p style="color : rgb(70, 70, 226);font-size:15px; padding-left:20px;text-align: left;">
          Use 6 characters with a mix of number <br> and letters
        </p>
        <!-- <div class="chk" style="display: flex">
          <v-row>
            <div class="check">
              <v-checkbox
                color="blue"
                value="black"
              />
            </div>
            <div class="check2">
              <p style="color : rgb(19, 19, 20);font-size:15px; margin-top: 24px;">
                By signin up,you agree to Bank's Term of <br>
                Use & Privacy Policy.
              </p>
            </div>
          </v-row>
        </div> -->
        <div class="chk">
          <div>
            <v-checkbox
              input-value="true"
              value
              style=""
            />
          </div>
          <div class="chk2">
            <p>
              By signing up, you agree to
            </p>
            <p>
              Bank's Term of Use & Privacy Policy.
            </p>
          </div>
        </div>

        <div>
          <v-btn
            class="btn1"
            style="height:30px;"
          >
            <span class="txt1" style="color:black;"> SING UP </span>
          </v-btn>
          &nbsp; or &nbsp;
          <v-btn
            class="btn2"
            style="height:30px;"
            outlined
            color="indigo"
          >
            <span class="txt2" style="color:black;"> CANCEL </span>
          </v-btn>
        </div>
        <div>
          <p style="color : rgb(0, 0, 0);font-size:15px">
            Already signed up? <a href="#">Log in</a>
          </p>
        </div>
      </div>
    </v-card>
  </div>
</template>

<style>
.box {
  background-color: white;
  padding: 5px;
  border-radius : 50rem;
  margin-top : 20px;
  font-size: 18px;
  /* color: rgb(22, 22, 22); */
}

.v-text-field--outlined fieldset {
  color: #222020 !important;
}

.v-text-field--outlined label {
  color: #615e5e !important;
}

.btn1 {
  background: linear-gradient(to bottom,#ffeb3b,#ffc107);
  margin-bottom: 60px;
  margin-top: 50px;
}

.btn2 {
  margin-bottom: 60px;
   margin-top: 50px;
}

.txt1 {
  color: brown;

}

a {
  color: blue;
}
.chk {
  display: flex;
  padding: 10px;
  padding-left:20px;
}
.chk2 {
  padding-left:10px;
  text-align: left;
  color : rgb(0, 0, 0);
  font-size:15px;
}

</style>
