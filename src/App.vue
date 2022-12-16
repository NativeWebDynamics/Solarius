<template>
  <div class="app">
    <v-container fluid class="py-0 px-0">
      <v-row no-gutters>
        <v-col cols="12" md="2">
          <div class="icon-area">
            <span class="mdi mdi-speedometer-medium icon-meter"></span>
            <h1 class="sol-head">Solarius</h1>
          </div>

          <div class="option-area">
            <div class="item">
              <span class="mdi mdi-google-analytics"></span> Dashboard
            </div>
            <div class="item">
              <span class="mdi mdi-book-education-outline"></span> Education
            </div>
            <v-expansion-panels accordion>
              <v-expansion-panel class="myaccordion">
                <v-expansion-panel-header class="accordonitem">
                  <div class="rs-area">
                    <span class="mdi mdi-clipboard-file resource-icon"> </span>
                    <p class="r-stlye">Resources</p>
                  </div>
                </v-expansion-panel-header>
                <v-expansion-panel-content>
                  <div class="inner-content">
                    <div class="item-2">
                      <span class="mdi mdi-dice-1 die-1"></span> Genetics
                    </div>
                    <div class="item-2">
                      <span class="mdi mdi-dice-1 die-2"></span> DNA synthesis
                    </div>
                    <div class="item-2">
                      <span class="mdi mdi-dice-1 die-3"></span> Events
                    </div>
                  </div>
                </v-expansion-panel-content>
              </v-expansion-panel>
            </v-expansion-panels>
            <div class="item"><span class="mdi mdi-cog"></span> Settings</div>
          </div>
          <div class="item-log">
            <p><span class="mdi mdi-logout"></span>Logout</p>
          </div>
        </v-col>
        <v-col cols="12" md="4" class="mid-area">
          <div class="today-plan">
            <div class="date">
              <p class="font-style">Today' Plan</p>
              <p class="font-style2">June 14th, 2022</p>
            </div>
            <div class="circle-outer">
              <div class="my-circle">+</div>
            </div>
          </div>
          <div>
            <h1 class="mid-heading font-style">
              Sustainable development Goals and health Innovation
            </h1>
          </div>
          <div class="img-area">
            <div>
              <img
                src="https://www.w3schools.com/howto/img_avatar.png"
                class="img-style"
                alt=""
              />
              <img
                src="https://www.w3schools.com/howto/img_avatar.png"
                class="img-style"
                alt=""
              />
              <img
                src="https://www.w3schools.com/howto/img_avatar.png"
                class="img-style"
                alt=""
              />
            </div>
            <div class="vl"></div>
            <div>
              <div class="date1">
                <p class="font-style">Medi Team Meeting</p>
                <p class="font-style2">13:30 - 14:50</p>
              </div>
            </div>
          </div>
          <div>
            <v-card
              class="mx-auto card-style"
              max-width="460"
              height="180"
              outlined
            >
              <v-list-item three-line>
                <v-list-item-content>
                  <div class="text-overline mb-4 font-style">Weekly Report</div>
                  <v-list-item-title class="text-h5 mb-1 font-style2">
                    Track Your Performance
                  </v-list-item-title>
                  <v-list-item-subtitle></v-list-item-subtitle>
                </v-list-item-content>

                <v-list-item-avatar
                  tile
                  size="80"
                  color="grey"
                ></v-list-item-avatar>
              </v-list-item>

              <v-card-actions>
                <v-btn outlined rounded text>
                  <p class="font-style">View Report</p>
                </v-btn>
              </v-card-actions>
            </v-card>

            <div class="inner-card">
              <v-card
                class="mx-auto card-style2"
                max-width="200"
                height="160"
                outlined
              >
                <v-list-item three-line>
                  <v-list-item-content>
                    <div class="text-overline mb-4 font-style">Study 78 X</div>
                    <v-list-item-title class="text-h5 mb-1">
                      <div>
                        <span class="mdi mdi-clock-time-four"></span>
                        In Progress
                      </div>
                    </v-list-item-title>
                    <v-list-item-subtitle></v-list-item-subtitle>
                  </v-list-item-content>

                  <v-list-item-avatar
                    tile
                    size="80"
                    color="grey"
                  ></v-list-item-avatar>
                </v-list-item>

                <v-card-actions> </v-card-actions>
              </v-card>
              <v-card
                class="mx-auto card-style2"
                max-width="200"
                height="160"
                outlined
              >
                <v-list-item three-line>
                  <v-list-item-content>
                    <div class="text-overline mb-4 font-style">Analyses</div>
                    <v-list-item-title class="text-h5 mb-1">
                      <div>
                        <span class="mdi mdi-check-circle"></span> Completed
                      </div>
                    </v-list-item-title>
                    <v-list-item-subtitle> </v-list-item-subtitle>
                  </v-list-item-content>

                  <v-list-item-avatar
                    tile
                    size="80"
                    color="grey"
                  ></v-list-item-avatar>
                </v-list-item>

                <v-card-actions> </v-card-actions>
              </v-card>
            </div>
          </div>
        </v-col>

        <v-col cols="12" md="4">
          <div class="today-plan">
            <div class="date">
              <h3 class="font-style">Monthly Pinned</h3>
            </div>
            <div class="circle-outer">
              <p>View All</p>
            </div>
          </div>
          <v-card
            class="mx-auto card-style3"
            max-width="460"
            height="110"
            outlined
          >
            <v-list-item three-line>
              <v-list-item-content>
                <div class="text-overline mb-4 font-style2 day">
                  <div>Next-gen immuno</div>
                  <div>5d</div>
                </div>
                <v-list-item-title class="text-h5 mb-1 font-style">
                  Multispecific Liquid Analysis
                </v-list-item-title>
                <v-list-item-subtitle
                  ><span class="mdi mdi-new-box new"></span> New
                  feedback</v-list-item-subtitle
                >
              </v-list-item-content>

              <v-list-item-avatar
                tile
                size="80"
                color="grey"
              ></v-list-item-avatar>
            </v-list-item>

            <v-card-actions> </v-card-actions>
          </v-card>
          <v-card
            class="mx-auto card-style3"
            max-width="460"
            height="110"
            outlined
          >
            <v-list-item three-line>
              <v-list-item-content>
                <div class="text-overline mb-4 font-style2 day">
                  Harmony

                  <div>1h</div>
                </div>
                <v-list-item-title class="text-h5 mb-1">
                  <h4 class="font-style">
                    Protein Characterization during child hood
                  </h4>
                  <h4>and Pregnancy</h4>
                </v-list-item-title>
                <v-list-item-subtitle
                  ><span class="mdi mdi-alert-circle alert"></span> Deadline is
                  Today
                </v-list-item-subtitle>
              </v-list-item-content>

              <v-list-item-avatar
                tile
                size="80"
                color="grey"
              ></v-list-item-avatar>
            </v-list-item>

            <v-card-actions> </v-card-actions>
          </v-card>
          <v-card
            class="mx-auto card-style3"
            max-width="460"
            height="110"
            outlined
          >
            <v-list-item three-line>
              <v-list-item-content>
                <div class="text-overline mb-4 font-style2 day">
                  Pharmaceutical
                  <div>7h</div>
                </div>
                <v-list-item-title class="text-h5 mb-1">
                  <h4 class="font-style">Quick element dissolution testing</h4>
                </v-list-item-title>
                <v-list-item-subtitle
                  ><span class="mdi mdi-check-circle check"></span> Accepted
                </v-list-item-subtitle>
              </v-list-item-content>

              <v-list-item-avatar
                tile
                size="80"
                color="grey"
              ></v-list-item-avatar>
            </v-list-item>

            <v-card-actions> </v-card-actions>
          </v-card>

          <div class="today-plan">
            <div class="date">
              <p class="font-style">My Learnings</p>
              <p class="font-style2">Your Progress of Medical Lectures</p>
            </div>
            <div class="circle-outer">
              <p><span class="mdi mdi-dots-horizontal"></span></p>
            </div>
          </div>
          <div class="data">
            <div class="data-area">
              <div>
                <span class="mdi mdi-virus virus-s"></span>
              </div>
              <div>
                <p class="problem">Viruses</p>
                <p class="detail font-style2">96 % Progress</p>
              </div>
            </div>
            <div class="data-area">
              <div>
                <span class="mdi mdi-bacteria bact-s"></span>
              </div>
              <div>
                <p class="problem">Bacterial Cells</p>
                <p class="detail font-style2">33 % Progress</p>
              </div>
            </div>
          </div>
          <div class="data">
            <div class="data-area">
              <div>
                <span class="mdi mdi-medical-bag med-s"></span>
              </div>
              <div>
                <p class="problem">Med Science</p>
                <p class="detail font-style2">7 % Progress</p>
              </div>
            </div>
            <div class="data-area">
              <div>
                <span class="mdi mdi-dna hum-s"></span>
              </div>
              <div>
                <p class="problem">Human gen</p>
                <p class="detail font-style2">56 % Progress</p>
              </div>
            </div>
          </div>
        </v-col>
        <v-col cols="12" md="1"> </v-col>
        <v-col cols="12" md="1" class="last-col-data">
          <div class="last-col">
            <img
              src="https://www.w3schools.com/howto/img_avatar.png"
              class="img-style"
              alt=""
            />
            <h3 class="font-style">Dr. Riddle</h3>
            <p class="font-style2">Scientist</p>
          </div>

          <div class="options">
            <span class="mdi mdi-account-edit icon-s"></span>
            <span class="mdi mdi-message icon-s"></span>
            <div class="circle-outer2">
              <div class="my-circle2">+</div>
            </div>
          </div>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
// import HelloWorld from "./components/HelloWorld";

export default {
  name: "App",

  components: {},

  data: () => ({
    //
  }),
};
</script>

<style scoped>
.new {
  color: #f8dabf;
  font-size: 18px;
}
.alert {
  color: black;
  font-size: 18px;
}
.check {
  color: lightgreen;
  font-size: 18px;
}
.icon-area {
  display: flex;
  flex-direction: column;
  margin-left: 40px;
  margin-top: 30px;
}
.last-col {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  gap: 10px;
}

.item:hover {
  background-color: #eee6e2;
}
.inner-content {
  display: flex;
  gap: 20px;
  flex-direction: column;
}
.img-area {
  margin-top: 40px;

  display: flex;
  justify-content: space-between;
}
.my-circle {
  height: 50px;
  width: 50px;
  border-radius: 50%;
  background-color: black;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}

.my-circle2 {
  font-weight: bold;
  height: 30px;
  width: 30px;
  border-radius: 50%;
  background-color: black;
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
}
.sol-head {
  font-family: Impact, Haettenschweiler, "Arial Narrow Bold", sans-serif;
  word-spacing: 2em;
}
.resource-icon {
  font-weight: bold;
  margin-left: 15px;
}

.card-style3 {
  margin-left: 20px;
  margin-top: 30px;
  background-color: #fbf7f4;
}
.card-style {
  margin-left: 20px;
  margin-top: 30px;
}
.card-style2 {
  margin-top: 10px;
}
.option-area {
  margin-top: 50px;
  display: flex;
  justify-content: center;
  flex-direction: column;
  gap: 10px;
}
.today-plan {
  display: flex;
  justify-content: space-between;
}
.myaccordion {
  background-color: hsl(26, 47%, 97%) !important;
}
.v-expansion-panel::before {
  box-shadow: none !important;
}

.vl {
  border-left: 2px solid grey;
  height: 50px;
}
.app {
  background-color: #fbf7f4;
  padding-bottom: 40px;
}
.mid-heading {
  margin-top: 50px;
  padding-left: 17px;
  padding-right: 10px;
}
.circle-outer {
  padding-right: 20px;
}

.item {
  margin-left: 30px;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 10px;
  font-weight: bold;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}

.r-stlye {
  font-weight: bold;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
.item-2 {
  margin-left: 30px;
  padding-top: 15px;
  padding-bottom: 15px;
  padding-left: 10px;
  color: #989693;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
.item-log {
  margin-top: 300px;
  margin-left: 30px;
  padding-top: 15px;
  padding-bottom: 15px;
  font-weight: bold;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  padding-left: 10px;
}
.problem {
  font-weight: bold;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
  font-size: 14px;
}

.today-plan {
  margin-top: 30px;
}
.mid-area {
  background-color: white;
  padding-bottom: 10px;
}
.date {
  display: flex;
  flex-direction: column;
  padding-left: 20px;
}
.date1 {
  display: flex;
  flex-direction: column;
  padding-right: 20px;
}
.img-style {
  height: 50px;
  width: 50px;
  border-radius: 50%;
  margin-right: -10px;
  border: 2px solid white;
}
.inner-card {
  display: flex;
  justify-content: space-evenly;
}
.icon-meter {
  font-size: 32px;
  margin-left: 35px;
}
.die-1 {
  color: #e5c2c7;
}
.die-2 {
  color: #fabe8f;
}
.die-3 {
  color: #476087;
}
.rs-area {
  display: flex;
  gap: 7px;
}
.last-col-data {
  border-left: 1px solid #eae6e2;
}
.options {
  margin-top: 500px;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  align-items: center;
  gap: 10px;
}

.icon-s {
  font-size: 20px;
}
.data-area {
  display: flex;
  gap: 5px;
  padding-right: 100px;
}
.data {
  display: flex;
  justify-content: space-between;
  margin-top: 20px;
  margin-left: 13px;
}

.virus-s {
  font-size: 32px;
  color: #455c81;
  background-color: #e9e9e9;
  padding-left: 5px;
  padding-right: 5px;
}

.bact-s {
  font-size: 32px;
  color: #f9be90;
  background-color: #fceee5;
  padding-left: 5px;
  padding-right: 5px;
}

.med-s {
  font-size: 32px;
  color: #e1a9ae;
  background-color: #f7ebeb;
  padding-left: 5px;
  padding-right: 5px;
}

.hum-s {
  font-size: 32px;
  color: #99aeb2;
  background-color: #e8ebea;
  padding-left: 5px;
  padding-right: 5px;
}
.font-style {
  font-weight: bold;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
.font-style2 {
  color: #adaba7;

  font-size: 14px;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}
.day {
  display: flex;
  justify-content: space-between;
}
</style>
