<template>
  <div>
    <section id="pageBody">
      <v-row class="content_row">
        <!-- title  -->
        <div style="padding-right: 24px" class="col-12 header_wrapper">
          <div style="display: flex; align-items: center; grid-gap: 35px">
            <div onclick="history.back()" class="header_wrapper-back">
              <svg
                width="25"
                height="16"
                viewBox="0 0 25 16"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M1.42188 6.96875L7.42188 0.96875C7.98438 0.359375 8.96875 0.359375 9.53125 0.96875C10.1406 1.53125 10.1406 2.51562 9.53125 3.07812L6.10938 6.5H23.5C24.2969 6.5 25 7.20312 25 8C25 8.84375 24.2969 9.5 23.5 9.5H6.10938L9.53125 12.9688C10.1406 13.5312 10.1406 14.5156 9.53125 15.0781C8.96875 15.6875 7.98438 15.6875 7.42188 15.0781L1.42188 9.07812C0.8125 8.51562 0.8125 7.53125 1.42188 6.96875Z"
                  fill="var(--primary-color)"
                />
              </svg>

              <span>back</span>
            </div>
            <header>Daniel Nwachukwu</header>
          </div>
          <div class="header_wrapper-buttons">
            <v-btn
              outlined
              color="var(--primary-color)"
              class="button button--header button--outlined"
            >
              <svg
                width="13"
                height="15"
                viewBox="0 0 13 15"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M6.5 14.75C7.45703 14.75 8.22266 13.9844 8.22266 13H4.75C4.75 13.9844 5.51562 14.75 6.5 14.75ZM12.3789 10.6758C11.8594 10.1016 10.8477 9.25391 10.8477 6.4375C10.8477 4.33203 9.37109 2.63672 7.34766 2.19922V1.625C7.34766 1.16016 6.96484 0.75 6.5 0.75C6.00781 0.75 5.625 1.16016 5.625 1.625V2.19922C3.60156 2.63672 2.125 4.33203 2.125 6.4375C2.125 9.25391 1.11328 10.1016 0.59375 10.6758C0.429688 10.8398 0.347656 11.0586 0.375 11.25C0.375 11.7148 0.703125 12.125 1.25 12.125H11.7227C12.2695 12.125 12.5977 11.7148 12.625 11.25C12.625 11.0586 12.543 10.8398 12.3789 10.6758Z"
                  fill="var(--primary-color)"
                />
              </svg>

              <span>NOTIFY payment </span>
            </v-btn>
            <v-btn color="var(--primary-color)" class="button button--header">
              <svg
                width="17"
                height="15"
                viewBox="0 0 17 15"
                fill="none"
                xmlns="http://www.w3.org/2000/svg"
              >
                <path
                  d="M11.6172 3.04688C11.5078 2.9375 11.3438 2.9375 11.2344 3.04688L5.27344 9.00781L5 11.5508C4.94531 11.8789 5.24609 12.1797 5.57422 12.125L8.11719 11.8516L14.0781 5.89062C14.1875 5.78125 14.1875 5.61719 14.0781 5.50781L11.6172 3.04688ZM16.0469 2.41797L14.707 1.07812C14.2969 0.667969 13.6133 0.667969 13.2031 1.07812L12.2461 2.03516C12.1367 2.14453 12.1367 2.30859 12.2461 2.41797L14.707 4.87891C14.8164 4.98828 14.9805 4.98828 15.0898 4.87891L16.0469 3.92188C16.457 3.51172 16.457 2.82812 16.0469 2.41797ZM11.125 10.2383V13H2.375V4.25H8.63672C8.74609 4.25 8.82812 4.22266 8.88281 4.16797L9.97656 3.07422C10.168 2.85547 10.0312 2.5 9.73047 2.5H1.9375C1.19922 2.5 0.625 3.10156 0.625 3.8125V13.4375C0.625 14.1758 1.19922 14.75 1.9375 14.75H11.5625C12.2734 14.75 12.875 14.1758 12.875 13.4375V9.14453C12.875 8.84375 12.5195 8.70703 12.3008 8.89844L11.207 9.99219C11.1523 10.0469 11.125 10.1289 11.125 10.2383Z"
                  fill="white"
                />
              </svg>

              <span>edit teacher</span>
            </v-btn>
          </div>
        </div>

        <v-row style="height: max-content" class="col-12">
          <div style="height: max-content" class="school__info col-3">
            <v-card class="school__card">
              <img src="/images/png/parent/teacher.png" alt="" />

              <div class="school__content">
                <div>
                  <h2 class="school__content-title">Daniel Nwachukwu</h2>
                  <span class="school__content-subtitle">Full Name</span>
                </div>
                <div>
                  <h2 class="school__content-title">
                    <svg
                      width="79"
                      height="15"
                      viewBox="0 0 79 15"
                      fill="none"
                      xmlns="http://www.w3.org/2000/svg"
                    >
                      <path
                        d="M8.64062 1.24219L10.4453 4.87891L14.4375 5.45312C15.1484 5.5625 15.4492 6.4375 14.9297 6.95703L12.0312 9.74609L12.7148 13.7109C12.8242 14.4219 12.0859 14.9688 11.4297 14.6406L7.875 12.7812L4.29297 14.668C3.63672 14.9961 2.89844 14.4492 3.00781 13.7383L3.69141 9.77344L0.792969 6.95703C0.273438 6.4375 0.574219 5.5625 1.28516 5.45312L5.27734 4.87891L7.08203 1.24219C7.41016 0.585938 8.33984 0.613281 8.64062 1.24219ZM24.3906 1.24219L26.1953 4.87891L30.1875 5.45312C30.8984 5.5625 31.1992 6.4375 30.6797 6.95703L27.7812 9.74609L28.4648 13.7109C28.5742 14.4219 27.8359 14.9688 27.1797 14.6406L23.625 12.7812L20.043 14.668C19.3867 14.9961 18.6484 14.4492 18.7578 13.7383L19.4414 9.77344L16.543 6.95703C16.0234 6.4375 16.3242 5.5625 17.0352 5.45312L21.0273 4.87891L22.832 1.24219C23.1602 0.585938 24.0898 0.613281 24.3906 1.24219ZM40.1406 1.24219L41.9453 4.87891L45.9375 5.45312C46.6484 5.5625 46.9492 6.4375 46.4297 6.95703L43.5312 9.74609L44.2148 13.7109C44.3242 14.4219 43.5859 14.9688 42.9297 14.6406L39.375 12.7812L35.793 14.668C35.1367 14.9961 34.3984 14.4492 34.5078 13.7383L35.1914 9.77344L32.293 6.95703C31.7734 6.4375 32.0742 5.5625 32.7852 5.45312L36.7773 4.87891L38.582 1.24219C38.9102 0.585938 39.8398 0.613281 40.1406 1.24219ZM61.6875 5.45312L57.6953 4.87891L55.8906 1.24219C55.7266 0.914062 55.4258 0.75 55.0977 0.75C54.7969 0.75 54.4961 0.914062 54.332 1.24219L52.5273 4.87891L48.5352 5.45312C47.8242 5.5625 47.5234 6.4375 48.043 6.95703L50.9414 9.74609L50.2578 13.7109C50.1758 14.3125 50.6133 14.75 51.1328 14.75C51.2695 14.75 51.4062 14.7227 51.543 14.668L55.125 12.7812L58.6797 14.668C58.8164 14.7227 58.9531 14.7773 59.0898 14.7773C59.6094 14.7773 60.0469 14.3125 59.9648 13.7383L59.2812 9.77344L62.1797 6.98438C62.6992 6.4375 62.3984 5.5625 61.6875 5.45312ZM58.3516 8.81641L57.8594 9.30859L58.5156 13.082L55.125 11.3047V2.60938L56.8203 6.08203L60.6211 6.62891L58.3516 8.81641ZM70.8477 0.75C71.1211 0.75 71.3398 0.914062 71.4492 1.13281L73.3359 4.98828L77.5195 5.61719C77.7656 5.64453 77.957 5.83594 78.0391 6.05469C78.1211 6.30078 78.0664 6.54688 77.875 6.73828L74.8398 9.74609L75.5508 13.9844C75.6055 14.2305 75.4961 14.5039 75.3047 14.6406C75.0859 14.7773 74.8125 14.8047 74.5938 14.6953L70.8477 12.6719L67.1016 14.6953C66.8828 14.8047 66.6367 14.7773 66.418 14.6406C66.2266 14.5039 66.1172 14.2305 66.1445 13.9844L66.8828 9.74609L63.8477 6.73828C63.6562 6.54688 63.6016 6.30078 63.6836 6.05469C63.7656 5.83594 63.957 5.64453 64.2031 5.61719L68.3867 4.98828L70.2734 1.13281C70.3828 0.914062 70.6016 0.75 70.8477 0.75ZM70.8477 2.91016L69.4258 5.89062C69.3164 6.08203 69.1523 6.21875 68.9336 6.24609L65.6797 6.71094L68.0312 9.03516C68.1953 9.19922 68.25 9.41797 68.2227 9.63672L67.6758 12.8906L70.5469 11.3594C70.7383 11.25 70.9844 11.25 71.1758 11.3594L74.0469 12.8906L73.5 9.63672C73.4453 9.41797 73.5273 9.19922 73.6914 9.03516L76.0156 6.71094L72.7891 6.24609C72.5703 6.21875 72.3789 6.08203 72.2969 5.89062L70.8477 2.91016Z"
                        fill="var(--primary-color)"
                      />
                    </svg>
                  </h2>
                  <span class="school__content-subtitle">Ratings</span>
                </div>
                <div class="school__content-status-area">
                  <div>
                    <h4 class="school__content-text">6289178298</h4>
                    <span class="school__content-subtitle">ID</span>
                  </div>
                  <div>
                    <h4 class="school__content-text status">Active</h4>
                    <span class="school__content-subtitle">Status</span>
                  </div>
                </div>
                <div>
                  <div>
                    <h4 class="school__content-text">07023456789</h4>
                    <span class="school__content-subtitle">Phone Number</span>
                  </div>
                </div>
                <div>
                  <div>
                    <h4 class="school__content-text">k.benjamin@gmail.com</h4>
                    <span class="school__content-subtitle">Email Address</span>
                  </div>
                </div>
                <div>
                  <div>
                    <h4 class="school__content-text">Dowen College</h4>
                    <span class="school__content-subtitle"
                      >School Affiliation</span
                    >
                  </div>
                </div>
                <div class="school__content-status-area">
                  <div>
                    <h4 class="school__content-text">942317905</h4>
                    <span class="school__content-subtitle">School ID</span>
                  </div>
                </div>
                <div>
                  <div>
                    <h4 class="school__content-text">Biology, Chemistry</h4>
                    <span class="school__content-subtitle">Subject</span>
                  </div>
                </div>

                <div class="school__content-status-area">
                  <div>
                    <h4 class="school__content-text button">Disable Account</h4>
                  </div>
                  <div>
                    <h4 class="school__content-text button">ARCHIVE</h4>
                  </div>
                </div>
              </div>
            </v-card>
            <div style="padding-top: 24px" class="chart">
              <v-card class="chart__container mini">
                <div class="chart__header">
                  <div>
                    <h3 class="chart__title">Recent History</h3>
                  </div>
                </div>
                <div class="chart__list">
                  <div v-for="n in 3" :key="n" class="chart__list-info">
                    <div class="chart__list-title">
                      <svg
                        width="30"
                        height="30"
                        viewBox="0 0 30 30"
                        fill="none"
                        xmlns="http://www.w3.org/2000/svg"
                      >
                        <circle
                          cx="15"
                          cy="15"
                          r="15"
                          fill="#F88B2A"
                          fill-opacity="0.1"
                        />
                        <path
                          d="M9.94205 6.6655C10.2233 6.5405 10.5358 6.57175 10.7545 6.75925L12.0358 7.853L13.2858 6.75925C13.567 6.5405 13.9733 6.5405 14.2545 6.75925L15.5358 7.853L16.7858 6.75925C17.067 6.5405 17.4733 6.5405 17.7545 6.75925L19.0358 7.853L20.2858 6.75925C20.5045 6.57175 20.817 6.5405 21.0983 6.6655C21.3483 6.7905 21.5358 7.0405 21.5358 7.32175V21.8217C21.5358 22.1342 21.3483 22.3842 21.0983 22.5092C20.817 22.6342 20.5045 22.603 20.2858 22.4155L19.0358 21.3217L17.7545 22.4155C17.4733 22.6342 17.067 22.6342 16.7858 22.4155L15.5358 21.3217L14.2545 22.4155C13.9733 22.6342 13.567 22.6342 13.2858 22.4155L12.0358 21.3217L10.7545 22.4155C10.5358 22.603 10.2233 22.6342 9.94205 22.5092C9.69205 22.3842 9.5358 22.1342 9.5358 21.8217V7.32175C9.5358 7.0405 9.69205 6.7905 9.94205 6.6655ZM12.5358 11.0717C12.2545 11.0717 12.0358 11.3217 12.0358 11.5717C12.0358 11.853 12.2545 12.0717 12.5358 12.0717H18.5358C18.7858 12.0717 19.0358 11.853 19.0358 11.5717C19.0358 11.3217 18.7858 11.0717 18.5358 11.0717H12.5358ZM12.5358 18.0717H18.5358C18.7858 18.0717 19.0358 17.853 19.0358 17.5717C19.0358 17.3217 18.7858 17.0717 18.5358 17.0717H12.5358C12.2545 17.0717 12.0358 17.3217 12.0358 17.5717C12.0358 17.853 12.2545 18.0717 12.5358 18.0717ZM12.5358 14.0717C12.2545 14.0717 12.0358 14.3217 12.0358 14.5717C12.0358 14.853 12.2545 15.0717 12.5358 15.0717H18.5358C18.7858 15.0717 19.0358 14.853 19.0358 14.5717C19.0358 14.3217 18.7858 14.0717 18.5358 14.0717H12.5358Z"
                          fill="#F88B2A"
                        />
                      </svg>

                      <span
                        >You have a new ticket from Atlantic Hall College</span
                      >
                    </div>
                    <p class="chart__list-timer">1 min ago</p>
                  </div>
                </div>
              </v-card>
            </div>
          </div>
          <!-- analytics  -->
          <div
            style="height: max-content; margin: 0; padding-top: 0"
            class="col-9 row"
          >
            <!-- header  -->
            <div
              style="height: max-content; padding-bottom: 0"
              class="col-12 chart"
            >
              <v-card class="chart__container only_header">
                <div class="chart__header">
                  <div>
                    <h3 class="chart__title">Account Summary</h3>
                  </div>
                  <v-menu nudge-bottom="5" bottom offset-y>
                    <template v-slot:activator="{ on, attrs }">
                      <v-btn
                        :ripple="false"
                        color="var(--faded-color))"
                        outlined
                        dark
                        v-bind="attrs"
                        v-on="on"
                        class="button button--outlined"
                      >
                        <span>Last 6 months</span>
                        <svg
                          width="10"
                          height="6"
                          viewBox="0 0 10 6"
                          fill="none"
                          xmlns="http://www.w3.org/2000/svg"
                        >
                          <path
                            d="M9.47656 1.50391L6.00391 5.00391C5.8125 5.16797 5.59375 5.25 5.375 5.25C5.12891 5.25 4.91016 5.16797 4.74609 5.00391L1.27344 1.50391C1 1.25781 0.917969 0.875 1.05469 0.546875C1.19141 0.21875 1.51953 0 1.875 0H8.84766C9.20312 0 9.50391 0.21875 9.64062 0.546875C9.77734 0.875 9.72266 1.25781 9.47656 1.50391Z"
                            fill="black"
                            fill-opacity="0.6"
                          />
                        </svg>
                      </v-btn>
                    </template>
                    <v-list>
                      <v-list-item>
                        <v-list-item-title>Days</v-list-item-title>
                      </v-list-item>
                    </v-list>
                  </v-menu>
                </div>
              </v-card>
            </div>

            <!-- analytics  -->
            <div class="col-6 col-md-3 col-lg-3 col-xl-3">
              <v-card class="analyticsCard">
                <h3>Published Content</h3>
                <h4>16</h4>
                <span>23% increase</span>
              </v-card>
            </div>
            <div class="col-6 col-md-3 col-lg-3 col-xl-3">
              <v-card class="analyticsCard">
                <h3>Resolved Questions</h3>
                <h4>13</h4>
                <span>10% increase</span>
              </v-card>
            </div>
            <div class="col-6 col-md-3 col-lg-3 col-xl-3">
              <v-card class="analyticsCard">
                <h3>Open Questions</h3>
                <h4>10</h4>
                <span>23% increase</span>
              </v-card>
            </div>
            <div class="col-6 col-md-3 col-lg-3 col-xl-3">
              <v-card class="analyticsCard">
                <h3>Avg. Students Performance</h3>
                <h4>78%</h4>
                <span class="danger">2% decrease</span>
              </v-card>
            </div>

            <div style="padding: 0" class="col-12 tab__section">
              <v-tabs
                class="tab__container teacher"
                v-model="tab"
                align-with-title
              >
                <v-tabs-slider color="var(--primary-color)"></v-tabs-slider>

                <v-tab :ripple="false" class="tab__container-item">
                  Students
                </v-tab>
                <v-tab :ripple="false" class="tab__container-item">
                  Contents
                </v-tab>
              </v-tabs>
            </div>

            <div class="col-12">
              <v-tabs-items v-model="tab">
                <!-- student tab  -->
                <v-tab-item>
                  <v-data-table
                    v-model="selected"
                    :headers="headers"
                    :items="bookData"
                    :single-select="false"
                    item-key="topic"
                    :disable-filtering="true"
                    :disable-pagination="false"
                    :disable-sort="true"
                    :items-per-page="10"
                    checkbox-color="var(--primary-color)"
                    :hide-default-footer="false"
                    show-select
                    class="generic_data_table"
                  >
                    <!-- name  -->
                    <template v-slot:item.topic="{ item }">
                      <div class="user_content">
                        <p>{{ item.topic }}</p>
                      </div>
                    </template>
                    <!-- subject -->
                    <template v-slot:item.week="{ item }">
                      <div class="user_content">
                        <p>{{ item.week }}</p>
                      </div>
                    </template>
                    <!-- id  -->
                    <template v-slot:item.id="{ item }">
                      <div class="user_content">
                        <p>{{ item.id }}</p>
                      </div>
                    </template>
                    <!-- question id  -->
                    <template v-slot:item.category="{ item }">
                      <div class="user_content">
                        <p class="category">{{ item.category }}</p>
                      </div>
                    </template>
                    <!-- Points  -->
                    <template v-slot:item.point="{ item }">
                      <div class="user_content">
                        <p class="category">{{ item.point }}</p>
                      </div>
                    </template>
                    <!-- status  -->
                    <template v-slot:item.status="{ item }">
                      <div class="user_content">
                        <p class="status" v-if="item.status == 'Resolved'">
                          {{ item.status }}
                        </p>
                        <p class="status draft" v-if="item.status == 'Open'">
                          {{ item.status }}
                        </p>
                        <p
                          class="status danger"
                          v-if="item.status == 'Blocked'"
                        >
                          {{ item.status }}
                        </p>
                      </div>
                    </template>
                    <!-- actions  -->
                    <template v-slot:item.action="{ item }">
                      <div class="user_content">
                        <div class="table__actions">
                          <div>
                            <svg
                              width="17"
                              height="13"
                              viewBox="0 0 17 13"
                              fill="none"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M8.5 0.375C6.28516 0.375 4.50781 1.38672 3.22266 2.58984C1.9375 3.76562 1.08984 5.1875 0.679688 6.17188C0.597656 6.39062 0.597656 6.63672 0.679688 6.85547C1.08984 7.8125 1.9375 9.23438 3.22266 10.4375C4.50781 11.6406 6.28516 12.625 8.5 12.625C10.6875 12.625 12.4648 11.6406 13.75 10.4375C15.0352 9.23438 15.8828 7.8125 16.293 6.85547C16.375 6.63672 16.375 6.39062 16.293 6.17188C15.8828 5.1875 15.0352 3.76562 13.75 2.58984C12.4648 1.38672 10.6875 0.375 8.5 0.375ZM12.4375 6.5C12.4375 8.6875 10.6602 10.4375 8.5 10.4375C6.3125 10.4375 4.5625 8.6875 4.5625 6.5C4.5625 4.33984 6.3125 2.5625 8.5 2.5625C10.6602 2.5625 12.4375 4.33984 12.4375 6.5ZM8.5 4.75C8.5 5.73438 7.70703 6.5 6.75 6.5C6.42188 6.5 6.12109 6.41797 5.875 6.28125C5.875 6.36328 5.875 6.44531 5.875 6.5C5.875 7.94922 7.05078 9.125 8.5 9.125C9.94922 9.125 11.125 7.94922 11.125 6.5C11.125 5.05078 9.94922 3.875 8.5 3.875C8.41797 3.875 8.33594 3.90234 8.25391 3.90234C8.39062 4.14844 8.5 4.44922 8.5 4.75Z"
                                fill="black"
                                fill-opacity="0.6"
                              />
                            </svg>
                          </div>
                          <div>
                            <svg
                              width="13"
                              height="13"
                              viewBox="0 0 13 13"
                              fill="none"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M12.625 10C12.625 11.4766 11.4492 12.625 10 12.625C8.52344 12.625 7.375 11.4766 7.375 10C7.375 9.91797 7.375 9.80859 7.40234 9.69922L4.80469 8.41406C4.33984 8.85156 3.68359 9.125 3 9.125C1.52344 9.125 0.375 7.97656 0.375 6.5C0.375 5.05078 1.52344 3.875 3 3.875C3.68359 3.875 4.33984 4.17578 4.80469 4.61328L7.40234 3.32812C7.375 3.21875 7.375 3.10938 7.375 3C7.375 1.55078 8.52344 0.375 10 0.375C11.4492 0.375 12.625 1.55078 12.625 3C12.625 4.47656 11.4492 5.625 10 5.625C9.28906 5.625 8.63281 5.35156 8.16797 4.91406L5.57031 6.19922C5.59766 6.30859 5.625 6.39062 5.625 6.5C5.625 6.60938 5.59766 6.71875 5.57031 6.82812L8.16797 8.11328C8.63281 7.67578 9.28906 7.375 10 7.375C11.4492 7.375 12.625 8.55078 12.625 10Z"
                                fill="black"
                                fill-opacity="0.6"
                              />
                            </svg>
                          </div>
                          <div>
                            <svg
                              width="14"
                              height="13"
                              viewBox="0 0 14 13"
                              fill="none"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M0.875 0.375H13.125C13.5898 0.375 14 0.785156 14 1.25V2.125C14 2.61719 13.5898 3 13.125 3H0.875C0.382812 3 0 2.61719 0 2.125V1.25C0 0.785156 0.382812 0.375 0.875 0.375ZM0.875 3.875H13.125V10.875C13.125 11.8594 12.332 12.625 11.375 12.625H2.625C1.64062 12.625 0.875 11.8594 0.875 10.875V3.875ZM4.375 6.0625C4.375 6.30859 4.56641 6.5 4.8125 6.5H9.1875C9.40625 6.5 9.625 6.30859 9.625 6.0625C9.625 5.84375 9.40625 5.625 9.1875 5.625H4.8125C4.56641 5.625 4.375 5.84375 4.375 6.0625Z"
                                fill="black"
                                fill-opacity="0.6"
                              />
                            </svg>
                          </div>
                        </div>
                      </div>
                    </template>
                  </v-data-table>
                </v-tab-item>
                <!-- content tab  -->
                <v-tab-item>
                  <v-data-table
                    v-model="contentSelected"
                    :headers="contentHeaders"
                    :items="contentData"
                    :single-select="false"
                    item-key="id"
                    :disable-filtering="true"
                    :disable-pagination="false"
                    :disable-sort="true"
                    :items-per-page="10"
                    checkbox-color="var(--primary-color)"
                    :hide-default-footer="false"
                    show-select
                    class="generic_data_table"
                  >
                    <!-- name  -->
                    <template v-slot:item.subject="{ item }">
                      <div class="user_content">
                        <p>{{ item.subject }}</p>
                      </div>
                    </template>
                    <!-- subject -->
                    <template v-slot:item.type="{ item }">
                      <div class="user_content">
                        <p>{{ item.type }}</p>
                      </div>
                    </template>
                    <!-- id  -->
                    <template v-slot:item.id="{ item }">
                      <div class="user_content">
                        <p>{{ item.id }}</p>
                      </div>
                    </template>
                    <!-- question id  -->
                    <template v-slot:item.engage="{ item }">
                      <div class="user_content">
                        <p class="engage">{{ item.engage }}</p>
                      </div>
                    </template>
                    <!-- status  -->
                    <template v-slot:item.status="{ item }">
                      <div class="user_content">
                        <p class="status" v-if="item.status == 'resolved'">
                          {{ item.status }}
                        </p>
                        <p class="status draft" v-if="item.status == 'draft'">
                          {{ item.status }}
                        </p>
                        <p
                          class="status danger"
                          v-if="item.status == 'archived'"
                        >
                          {{ item.status }}
                        </p>
                      </div>
                    </template>
                    <!-- actions  -->
                    <template v-slot:item.action="{ item }">
                      <div class="user_content">
                        <div class="table__actions">
                          <div>
                            <svg
                              width="17"
                              height="13"
                              viewBox="0 0 17 13"
                              fill="none"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M8.5 0.375C6.28516 0.375 4.50781 1.38672 3.22266 2.58984C1.9375 3.76562 1.08984 5.1875 0.679688 6.17188C0.597656 6.39062 0.597656 6.63672 0.679688 6.85547C1.08984 7.8125 1.9375 9.23438 3.22266 10.4375C4.50781 11.6406 6.28516 12.625 8.5 12.625C10.6875 12.625 12.4648 11.6406 13.75 10.4375C15.0352 9.23438 15.8828 7.8125 16.293 6.85547C16.375 6.63672 16.375 6.39062 16.293 6.17188C15.8828 5.1875 15.0352 3.76562 13.75 2.58984C12.4648 1.38672 10.6875 0.375 8.5 0.375ZM12.4375 6.5C12.4375 8.6875 10.6602 10.4375 8.5 10.4375C6.3125 10.4375 4.5625 8.6875 4.5625 6.5C4.5625 4.33984 6.3125 2.5625 8.5 2.5625C10.6602 2.5625 12.4375 4.33984 12.4375 6.5ZM8.5 4.75C8.5 5.73438 7.70703 6.5 6.75 6.5C6.42188 6.5 6.12109 6.41797 5.875 6.28125C5.875 6.36328 5.875 6.44531 5.875 6.5C5.875 7.94922 7.05078 9.125 8.5 9.125C9.94922 9.125 11.125 7.94922 11.125 6.5C11.125 5.05078 9.94922 3.875 8.5 3.875C8.41797 3.875 8.33594 3.90234 8.25391 3.90234C8.39062 4.14844 8.5 4.44922 8.5 4.75Z"
                                fill="black"
                                fill-opacity="0.6"
                              />
                            </svg>
                          </div>
                          <div>
                            <svg
                              width="13"
                              height="13"
                              viewBox="0 0 13 13"
                              fill="none"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M12.625 10C12.625 11.4766 11.4492 12.625 10 12.625C8.52344 12.625 7.375 11.4766 7.375 10C7.375 9.91797 7.375 9.80859 7.40234 9.69922L4.80469 8.41406C4.33984 8.85156 3.68359 9.125 3 9.125C1.52344 9.125 0.375 7.97656 0.375 6.5C0.375 5.05078 1.52344 3.875 3 3.875C3.68359 3.875 4.33984 4.17578 4.80469 4.61328L7.40234 3.32812C7.375 3.21875 7.375 3.10938 7.375 3C7.375 1.55078 8.52344 0.375 10 0.375C11.4492 0.375 12.625 1.55078 12.625 3C12.625 4.47656 11.4492 5.625 10 5.625C9.28906 5.625 8.63281 5.35156 8.16797 4.91406L5.57031 6.19922C5.59766 6.30859 5.625 6.39062 5.625 6.5C5.625 6.60938 5.59766 6.71875 5.57031 6.82812L8.16797 8.11328C8.63281 7.67578 9.28906 7.375 10 7.375C11.4492 7.375 12.625 8.55078 12.625 10Z"
                                fill="black"
                                fill-opacity="0.6"
                              />
                            </svg>
                          </div>
                          <div>
                            <svg
                              width="14"
                              height="13"
                              viewBox="0 0 14 13"
                              fill="none"
                              xmlns="http://www.w3.org/2000/svg"
                            >
                              <path
                                d="M0.875 0.375H13.125C13.5898 0.375 14 0.785156 14 1.25V2.125C14 2.61719 13.5898 3 13.125 3H0.875C0.382812 3 0 2.61719 0 2.125V1.25C0 0.785156 0.382812 0.375 0.875 0.375ZM0.875 3.875H13.125V10.875C13.125 11.8594 12.332 12.625 11.375 12.625H2.625C1.64062 12.625 0.875 11.8594 0.875 10.875V3.875ZM4.375 6.0625C4.375 6.30859 4.56641 6.5 4.8125 6.5H9.1875C9.40625 6.5 9.625 6.30859 9.625 6.0625C9.625 5.84375 9.40625 5.625 9.1875 5.625H4.8125C4.56641 5.625 4.375 5.84375 4.375 6.0625Z"
                                fill="black"
                                fill-opacity="0.6"
                              />
                            </svg>
                          </div>
                        </div>
                      </div>
                    </template>
                  </v-data-table>
                </v-tab-item>
              </v-tabs-items>
            </div>
          </div>
        </v-row>
      </v-row>
    </section>
  </div>
</template>

<script>
export default {
  data() {
    return {
      selected: [],
      contentSelected: [],
      tab: 0,
      contentHeaders: [
        {
          text: "Subject",
          align: "start",
          value: "subject",
        },
        { text: "Type", value: "type" },
        { text: "Topic", value: "topic" },
        { text: "Content ID", value: "id" },
        { text: "Engagements", value: "engage" },
        { text: "Status", value: "status" },
        { text: "Actions", value: "action" },
      ],
      headers: [
        {
          text: "Student Name",
          align: "start",
          value: "topic",
        },
        { text: "Subject", value: "week" },
        { text: "Student ID", value: "id" },
        { text: "Question ID", value: "category" },
        { text: "Points", value: "point" },
        { text: "Status", value: "status" },
        { text: "Actions", value: "action" },
      ],
      bookData: [
        {
          topic: "Precious Tifeoluwa",
          week: "Biology",
          id: 8755443346,
          category: 8378173618,
          status: "Open",
          point: 10,
          action: null,
        },
        {
          topic: "Chijioke Egwuye",
          week: "Chemistry",
          id: 8755443346,
          category: 8378173618,
          status: "Open",
          point: 5,
          action: null,
        },
        {
          topic: "Mohamed Hauwa",
          week: "Chemistry",
          id: 8755443346,
          category: 8378173618,
          status: "Resolved",
          point: 3,
          action: null,
        },
        {
          topic: "Williams Ebube",
          week: "Chemistry",
          id: 8755443346,
          category: 8378173618,
          status: "Resolved",
          point: 10,
          action: null,
        },
        {
          topic: "Isiaka Ibrahim",
          week: "Chemistry",
          id: 8755443346,
          category: 8378173618,
          status: "Resolved",
          point: 5,
          action: null,
        },
        {
          topic: "Precious Tifeoluwass",
          week: "Chemistry",
          id: 8755443346,
          category: 8378173618,
          status: "Blocked",
          point: 7,
          action: null,
        },
      ],
      contentData: [
        {
          subject: "Biology",
          type: "Note",
          topic: "Photosynthesis",
          id: 8378173618,
          engage: 10,
          status: "draft",
        },
        {
          subject: "Chemistry",
          type: "Weekly Test",
          topic: "Acids, Bases, Salt",
          id: 8378173619,
          engage: 5,
          status: "resolved",
        },
        {
          subject: "Biology",
          type: "Note",
          topic: "Nitrogen Cycle",
          id: 8378173610,
          engage: 7,
          status: "draft",
        },
        {
          subject: "Chemistry",
          type: "Standard Test",
          topic: "Nitrogen Cycle",
          id: 8378173613,
          engage: 7,
          status: "draft",
        },
        {
          subject: "Chemistry",
          type: "Standard Test",
          topic: "Nitrogen Cycle",
          id: 8370173613,
          engage: 7,
          status: "archived",
        },
      ],
    };
  },
  methods: {
    showModal(type) {
      switch (type) {
        case "edit":
          this.$refs.editUser.showDialogue();
          break;
        case "viewUser":
          this.$refs.viewUser.showDialogue();
          break;

        default:
          break;
      }
    },
  },
};
</script>


<style lang="scss" scoped></style>