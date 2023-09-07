<template lang="pug">
.container.border-solid.border-green
  .div(v-for='driver in drivers')
</template>

<script>
import summaries from '~/assets/data/summaries.json'

export default {
  name: 'Home',
  data () {
    return {
      playing: false,
      interval: 1000,
      drivers: [
        { 'name': 'VER', 'image': '/images/driver-headshots/2023/VER.png' },
        { 'name': 'PER', 'image': '/images/driver-headshots/2023/PER.png' },
        { 'name': 'LEC', 'image': '/images/driver-headshots/2023/LEC.png' },
        { 'name': 'SAI', 'image': '/images/driver-headshots/2023/SAI.png' },
        { 'name': 'GAS', 'image': '/images/driver-headshots/2023/GAS.png' },
        { 'name': 'OCO', 'image': '/images/driver-headshots/2023/OCO.png' },
        { 'name': 'NOR', 'image': '/images/driver-headshots/2023/NOR.png' },
        { 'name': 'PIA', 'image': '/images/driver-headshots/2023/PIA.png' },
        { 'name': 'HAM', 'image': '/images/driver-headshots/2023/HAM.png' },
        { 'name': 'RUS', 'image': '/images/driver-headshots/2023/RUS.png' },
        { 'name': 'TSU', 'image': '/images/driver-headshots/2023/TSU.png' },
        { 'name': 'LAW', 'image': '/images/driver-headshots/2023/LAW.png' },
        { 'name': 'HUL', 'image': '/images/driver-headshots/2023/HUL.png' },
        { 'name': 'MAG', 'image': '/images/driver-headshots/2023/MAG.png' },
        { 'name': 'BOT', 'image': '/images/driver-headshots/2023/BOT.png' },
        { 'name': 'ZHO', 'image': '/images/driver-headshots/2023/ZHO.png' },
        { 'name': 'STR', 'image': '/images/driver-headshots/2023/STR.png' },
        { 'name': 'ALO', 'image': '/images/driver-headshots/2023/ALO.png' },
        { 'name': 'SAR', 'image': '/images/driver-headshots/2023/SAR.png' },
        { 'name': 'ALB', 'image': '/images/driver-headshots/2023/ALB.png' },
      ]
    }
  }
}
</script>

<style lang='scss'>
@tailwind base;
@tailwind components;
@tailwind utilities;
</style>
