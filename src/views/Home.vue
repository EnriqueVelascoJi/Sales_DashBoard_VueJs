<template>
  <div class="home">
    <v-container>
      <v-row class="mt-2">
        <v-col cols="12" sm="3">
          <v-card color="#23262D" elevation="10">
            <v-row>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 mb-14 grey--text">
                        FAMILY
                      </v-list-item-subtitle>
                      <v-icon color="grey" x-large>fas fa-users</v-icon>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 grey--text">742,824</v-list-item-subtitle>
                      <v-list-item-subtitle class="grey--text" style="font-size: 11px">CHANGE TO</v-list-item-subtitle>
                      <v-list-item-subtitle class="mb-5 grey--text" style="font-size: 11px">PREVIOUS MONTH</v-list-item-subtitle>
                      <v-icon color="green" class="mt-2 mr-2" x-large>fas fa-sort-up</v-icon>
                      <span class="green--text">+20,597</span><br>
                      <span class="green--text">(2.16%)</span>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
        <v-col cols="12" sm="3">
          <v-card color="#23262D" elevation="10">
            <v-row>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 mb-14 grey--text">
                        YOUTH
                      </v-list-item-subtitle>
                      <v-icon color="grey" x-large>fas fa-pagelines</v-icon>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 grey--text">914,179</v-list-item-subtitle>
                      <v-list-item-subtitle class="grey--text" style="font-size: 11px">CHANGE TO</v-list-item-subtitle>
                      <v-list-item-subtitle class="mb-5 grey--text" style="font-size: 11px">PREVIOUS MONTH</v-list-item-subtitle>
                      <v-icon color="red" class="mt-2 mr-2" x-large>fas fa-sort-down</v-icon>
                      <span class="red--text">-21,597</span><br>
                      <span class="red--text">(0.12%)</span>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
        <v-col cols="12" sm="3">
          <v-card color="#23262D" elevation="10">
            <v-row>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 mb-14 grey--text">
                        SALES
                      </v-list-item-subtitle>
                      <v-icon color="grey" x-large>fas fa-chart-pie</v-icon>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 grey--text">456,765</v-list-item-subtitle>
                      <v-list-item-subtitle class="grey--text" style="font-size: 11px">CHANGE TO</v-list-item-subtitle>
                      <v-list-item-subtitle class="mb-5 grey--text" style="font-size: 11px">PREVIOUS MONTH</v-list-item-subtitle>
                      <v-icon color="green" class="mt-2 mr-2" x-large>fas fa-sort-up</v-icon>
                      <span>+12,876</span><br>
                      <span class="green--text">(4.76%)</span>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
        <v-col cols="12" sm="3">
          <v-card color="#23262D" elevation="10">
            <v-row>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 mb-14 grey--text">
                        RETURN
                      </v-list-item-subtitle>
                      <v-icon color="grey" x-large>fas fa-sort-up</v-icon>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
              <v-col cols="12" sm="6">
                <v-list-item three-line>
                  <v-list-item-content>
                    <div>
                      <v-list-item-subtitle class="subtitle-1 grey--text">235,335</v-list-item-subtitle>
                      <v-list-item-subtitle class="grey--text" style="font-size: 11px">CHANGE TO</v-list-item-subtitle>
                      <v-list-item-subtitle class="mb-5 grey--text" style="font-size: 11px">PREVIOUS MONTH</v-list-item-subtitle>
                      <v-icon color="green" class="mt-2 mr-2" x-large>fas fa-sort-up</v-icon>
                      <span>+16,432</span><br>
                      <span class="green--text">(7.11%)</span>
                    </div>
                  </v-list-item-content>
                </v-list-item>
              </v-col>
            </v-row>
          </v-card>
        </v-col>
        <v-col cols="12" sm="7">
          <v-card color="#23262D">
            <v-app-bar color="rgba(0, 0, 0, 0)" flat>
              <v-toolbar-title class="grey--text title">Monthly Trend</v-toolbar-title>
              <v-spacer></v-spacer>
              <v-chip class="ma-2" color="grey darken" pill>April 10
                <v-icon right small color="cyan">fas fa-chevron-circle-down</v-icon>
              </v-chip>
            </v-app-bar>
            <v-data-table :headers="headers" :items="desserts" class="dattab">
              <template v-slot:item.glutenfree="{item}">
                <v-simple-checkbox v-model="item.glutenfree" color="cyan"></v-simple-checkbox>
              </template>
              <template v-slot:item.action="">
                <v-icon small>mdi-pencil</v-icon>
              </template>
            </v-data-table>
          </v-card>
        </v-col>
        <v-col cols="12" sm="5">
          <v-card color="#23262D">
            <v-app-bar color="rgba(0, 0,0, 0)" flat>
              <v-toolbar-title class="grey--text title">
                Support Tickets
              </v-toolbar-title>
            </v-app-bar>
              <v-list three-line class="mt-5" color="#23262D">
                <v-list-item-group>
                  <template v-for="(item) in files">
                    <v-list-item :key="item.title">
                      <v-list-item-avatar>
                        <img :src="item.avatar">
                      </v-list-item-avatar>
                      <template>
                        <v-list-item-content>
                          <v-list-item-title v-html="item.title"></v-list-item-title>
                          <v-list-item-subtitle v-text="item.subtitle"></v-list-item-subtitle>
                        </v-list-item-content>
                      </template>
                      <v-list-item-action>
                        <v-btn v-text="item.action" rounded color="cyan" small></v-btn>
                      </v-list-item-action>
                    </v-list-item>
                  </template>
                </v-list-item-group>
              </v-list>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>

  export default {
    name: 'Home',
    data() {
      return {
        desserts: [
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
          {
            glutenfree: false,
            name: 'Enrique Velasco',
            email: 'enriquevelas393@gmail.com',
            contact: '2345123432',
            status: 'Open'
          },
        ],
        headers: [
          {
            text: '',
            align: 'start',
            sortable: false,
            value: '',
          },
          { text: '', value: 'glutenfree' },
          { text: 'Email', value: 'email' },
          { text: 'Contact', value: 'contact' },
          { text: 'Status', value: 'status', sortable: false },
          { text: 'Actions', value: 'actions', sortable: false }
        ],
        files: [
          {
            avatar: 'https://cdn.vuetifyjs.com/images/lists/1.jpg',
            action: 'Open',
            headline: 'Birthday gift',
            subtitle: 'Have any ideas about what we should get Heidi for her birthday?',
            title: '<strong>Trevoir Hansen</strong>'

          },
          {
            avatar: 'https://cdn.vuetifyjs.com/images/lists/2.jpg',
            action: 'Open',
            headline: 'Birthday gift',
            subtitle: 'Have any ideas about what we should get Heidi for her birthday?',
            title: '<strong>Trevoir Hansen</strong>'

          },
          {
            avatar: 'https://cdn.vuetifyjs.com/images/lists/3.jpg',
            action: 'Open',
            headline: 'Birthday gift',
            subtitle: 'Have any ideas about what we should get Heidi for her birthday?',
            title: '<strong>Trevoir Hansen</strong>'

          },
          {
            avatar: 'https://cdn.vuetifyjs.com/images/lists/4.jpg',
            action: 'Open',
            headline: 'Birthday gift',
            subtitle: 'Have any ideas about what we should get Heidi for her birthday?',
            title: '<strong>Trevoir Hansen</strong>'

          },
          {
            avatar: 'https://cdn.vuetifyjs.com/images/lists/5.jpg',
            action: 'Open',
            headline: 'Birthday gift',
            subtitle: 'Have any ideas about what we should get Heidi for her birthday?',
            title: '<strong>Trevoir Hansen</strong>'

          }
        ]
      }
    }
  }
</script>

<style scoped>
  .datab {
    background: #23263D !important;
  }
</style>