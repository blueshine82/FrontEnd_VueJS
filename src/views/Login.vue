<template>
    <v-app id="inspire">
      <v-main class="blue-grey lighten-4">
        <!-- Login Component -->
        <v-container style="max-width: 450px" fill-height>
          <v-layout align-center row wrap>
            <v-flex xs12>
              <v-card>
                <div class="pa-10">
                  <h1 style="text-align: center" class="mb-10">Login</h1>
                  <form>
                    <v-text-field
                      label="ID"
                      prepend-inner-icon="mdi-account"
                    ></v-text-field>
                    <v-text-field
                      prepend-inner-icon="mdi-lock"
                      type="password"
                      label="Password"
                    >
                    </v-text-field>
                    <v-btn
                      type="submit"
                      color="blue lighten-1 text-capitalize"
                      depressed
                      large
                      block
                      dark
                      class="mb-3"
                    >
                      Login
                    </v-btn>
                    <v-btn
                      @click="addUserShow"
                      color="blue lighten-1 text-capitalize"
                      depressed
                      large
                      block
                      dark
                    >
                      Sign Up
                    </v-btn>
                  </form>
                </div>
              </v-card>
            </v-flex>
          </v-layout>
        </v-container>
      </v-main>
    </v-app>
  </template>
  
  <script>
  // import axios from 'axios'

  // export default {
  //         name: 'login',
  //         data() {
  //             return {
  //                 loginSuccess: false,
  //                 loginError: false,
  //                 user: '',
  //                 password: '',
  //                 error: false
  //             }
  //         },
  //         methods: {
  //             async login() {
  //                 try {
  //                     const result = await axios.get('/api/login', {
  //                         auth: {
  //                             username: this.user,
  //                             password: this.password
  //                         }
  //                     });
  //                     if (result.status === 200) {
  //                         this.loginSuccess = true
  //                     }
  //                 } catch (err) {
  //                     this.loginError = true;
  //                     throw new Error(err)
  //                 }
  //             }
  //         }
  //     }


  export default {
    data() {
      return {
      };
    },
    components: {},
    computed: {},
    methods: {},
  };
  </script>