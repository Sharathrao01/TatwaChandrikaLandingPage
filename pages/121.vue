<template>
  <div class="bg-amber-50 min-h-screen">
    <!-- Header -->
    <header class="bg-orange-700 text-white">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-xl font-bold">Hari Sarvottama</h1>
        <img
          src="https://vyasarajamatha.org/wp-content/uploads/2022/03/Hanuma3-.png"
          alt="hanuma"
        />
        <div class="relative flex flex-col items-center">
          <svg width="300" height="200">
            <defs>
              <path
                id="curve"
                d="M 150, 150 m -100, 0 a 100,100 0 1,1 200,0 a 100,100 0 1,1 -200,0"
              />
            </defs>
            <text>
              <textPath
                xlink:href="#curve"
                startOffset="25%"
                text-anchor="middle"
              >
                Sri Moola Gopala Krishno Vijayathe
              </textPath>
            </text>
          </svg>
          <img
            src="https://vyasarajamatha.org/wp-content/uploads/2022/03/circle-1-oif243d5q4sylp98lhxtjts6goczthixxotr90wtrk.png"
            alt="Bheema"
            class="w-24 h-24 rounded-full absolute"
            style="top: 80px; left: 50%; transform: translateX(-50%)"
          />
        </div>
        <img
          src="https://vyasarajamatha.org/wp-content/uploads/2022/03/Garuda-Stone3.png"
          alt="Bheema"
        />
        <h1 class="text-xl font-bold">Vaayu Jeevottama</h1>
      </div>
    </header>

    <!-- Main content -->
    <main class="container mx-auto mt-8 p-4">
      <div class="bg-white rounded-lg shadow-lg p-6">
        <!-- <div class="flex justify-between text-center">
          <div class="w-1/3 p-4">
            <h3 class="text-lg font-semibold mb-2 text-orange-700">
              Sri Rajendratirthiya Poorvadi Matha
            </h3>
          </div>
          <div class="w-1/3 p-4">
            <h3 class="text-lg font-semibold mb-2 text-orange-700">
              Sri Jagadguru Madhvacharya Moola Maha Samsthanam
            </h3>
          </div>
          <div class="w-1/3 p-4">
            <h3 class="text-lg font-semibold mb-2 text-orange-700">
              Sri Vyasaraja Matha (Sosale)
            </h3>
          </div>
        </div> -->

        <h2 class="text-3xl font-bold text-center mb-4 text-orange-800">
          Sri Tatwa Chandrika: Your Monthly Companion for Spiritual Growth and
          Knowledge
        </h2>

        <!-- Main image -->
        <div class="flex justify-center mb-6">
          <div class="relative">
            <img
              src="https://anandsp1.wordpress.com/wp-content/uploads/2020/08/moola-gopalakrishna-devaru-20.jpg"
              alt="Deity statue"
              class="rounded-lg shadow-md max-w-2xl"
            />
            <div class="absolute top-2 right-2">
              <!-- <img
                src="require('@/assets/path-to-small-logo.png')"
                alt="Small logo"
                class="w-12 h-12"
              /> -->
            </div>
          </div>
        </div>

        <!-- Mathas information -->
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "LandingPage",
};
</script>

<style scoped>
svg text {
  font-size: 18px;
  font-weight: bold;
  fill: white;
}
</style>
