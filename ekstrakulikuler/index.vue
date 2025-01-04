<template>
  <div class="ekskul-page">
    <header>
      <h1>Ekstrakurikuler Sekolah</h1>
    </header>
    <section class="ekskul-list">
      <div v-for="activity in activities" :key="activity.id" class="ekskul-item">
        <img :src="activity.logo" :alt="activity.name" class="ekskul-logo" />
        <h2 class="ekskul-name">{{ activity.name }}</h2>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  name: "EkstrakulikulerPage",
  data() {
    return {
      activities: [
        {
          id: 1,
          name: "Basketball",
          logo: "https://basketball-logo-emblem-341459381",
        },
        {
          id: 2,
          name: "Paskibra",
          logo: "https://down-id.img.susercontent.com/file/id-11134207-7qul9-lk57huxtby22f5",
        },
        {
          id: 3,
          name: "Pmr",
          logo: "https://imgres.html",
        },
        {
          id: 4,
          name: "Volly",
          logo: "assets/img/Volly.jpeg",
        },
        {
          id: 5,
          name: "BASKETT",
          logo: "assets/img/BASKETT.jpeg"
        },
        {
          id: 6,
          name: "ITCLUB",
          logo: "assets/img/ITCLUB.jpeg"
        },
        {
          id: 7,
          name: "PMR",
          logo: "assets/img/Pmr.jpeg"
        }
        {
          id: 8,
          name: "PKS",
          logo: "assets/img/PKS.jpeg"
        },
        {
          id: 9,
          name: "PLH",
          logo: "assets/img/PLH.jpeg"
        },
        {
          id: 10,
          name: "English club",
          logo: "assets/img/ENGLISHCLUB.jpeg"
        }

      ],
    };
  },
};
</script>

<style scoped>
.ekskul-page {
  font-family: Arial, sans-serif;
  text-align: center;
  margin: 20px auto;
  max-width: 1200px;
}

header h1 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #333;
}

.ekskul-list {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 20px;
  padding: 10px;
}

.ekskul-item {
  display: flex;
  flex-direction: column;
  align-items: center;
  background: #f9f9f9;
  border-radius: 10px;
  padding: 15px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: transform 0.2s;
}

.ekskul-item:hover {
  transform: scale(1.05);
}

.ekskul-logo {
  width: 80px;
  height: 80px;
  object-fit: contain;
  margin-bottom: 10px;
}

.ekskul-name {
  font-size: 1.2rem;
  color: #555;
}
</style>