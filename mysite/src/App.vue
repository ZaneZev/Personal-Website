<template>
  <HeadderBar/>
  <SideBar/>
  <div class="prj-List">
    <lu >
      <Project title="EV VW Bus Conversion [IN PROGRESS]" alt="EV Bus" pic="https://i.imgur.com/V7rd16i.gif" info="Classic VW Bus EV conversion. ussing 5 Tesla model S battewry modules ans an AC50 motor to get about 97 HP instead of the 37 HP with internal combustion"/>
      <Project title="EV VW Bus Battery Box [IN PROGRESS]" alt="EV VW Bus Battery Box [IN PROGRESS]" pic="https://i.imgur.com/j5mvWI7.png" info=""/>
      <Project title="Defcon 27 / BlackHat 2019 Electronic Badge" alt="2019 Badge" pic="https://i.imgur.com/rVDgndp.gif" info="ESP32 based electronic badge made for defecon 27 / BlackHat 2019. has both Wifi and Bluetooth abilities. I fully designed the PCB and worked on the development of the software"/>
      <Project title="EV Bike Monitor PCB" alt="EV Bike Monitor PCB" pic="" info="wifi and bluetooth capable board designed to provide an onboard 12v, and 5v source from wide range of battery voltages. This is mean to transmit current and voltage data to a mobile devicefor both remote and onboard monitoring"/>
      <Project title="12Lb Battlebot" alt="Bot Prototype" pic="https://i.imgur.com/pJMERT1.jpg" info="12lb battlebot I designed to compete in a local event. Fabrication still underway"/>
      <Project title="Defcon 26 / BlackHat 2018 Electronic Raspberry Pi Zero Badge" alt="Defcon 26 / BlackHat 2018 Electronic Raspberry Pi Zero Badge" pic="https://i.imgur.com/dV3PWLI.jpg" info="Raspberry Pi zero based electronic badge for defecon 26 / BlackHat 2018. Using a rasberry pi running raspbian this electronic badge gave full access to the OS and badge code. ran off of a singe cell lipo boosted to 5v and drove multiple high-power addressable RGB LEDs. All badge specific code was written by me in python and inculded a game I made as a final project in a c++ class I ported to the raspberry pi. python code not currently available except for what was distributed at the events"/>
      <Project title="Defcon 25 / BlackHat 2017 Electronic Badge" alt="Defcon 26 / BlackHat 2018 Electronic Badge" pic="https://i.imgur.com/UhPuG97.jpg" info="My first badge i designed for defcon / BlackHat. Ran on an arduino compatable micocontroller and has a digital interface of just 1 byte shown through 8 LEDs"/>
      
    </lu>
  </div>
</template>

<script>
import Project from './components/Project.vue'
import SideBar from './components/SideBar.vue'
import HeadderBar from './components/Headder-Bar.vue'

export default {
  name: 'App',
  components: {
    Project,
    SideBar,
    HeadderBar,
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /*text-align: center;*/
  color: #2c3e50;
  /*margin-top: 60px;*/
}
.prj-List{
  margin-left: 160px;
}
body{margin: 0}
*{background-color: black;}
</style>
