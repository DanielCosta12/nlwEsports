<template>
  <section>
    <div>
      <h2>{{ h2 }}</h2>
      <p>{{ p }}</p>
      <ul class="games-list">
        <li>
          <a :href="csLink" target="_blank">
            <img :src="imgCsgo" :alt="altCsgo" />
          </a>
        </li>
        <li>
          <a :href="chessLink" target="_blank">
            <img :src="imgChess" :alt="altChess" />
          </a>
        </li>
        <li>
          <a :href="lolLink" target="_blank">
            <img :src="imgLol" alt="altLol" />
          </a>
        </li>
        <li>
          <a :href="valorantLink" target="_blank">
            <img :src="imgValorant" :alt="altValorant" />
          </a>
        </li>
        <li>
          <a :href="softwareLink" target="_blank">
            <img :src="imgSoftware" :alt="altSoftware" />
          </a>
        </li>
      </ul>
    </div>
  </section>
</template>

<script>
export default {
  name: "Category",
  data() {
    return {
      // top
      h2: "minhas categorias favoritas",
      p: "O que eu mais gosto de assistir",
      //   csgo
      csLink:
        "https://www.twitch.tv/directory/game/Counter-Strike%3A%20Global%20Offensive",
      imgCsgo: "https://static-cdn.jtvnw.net/ttv-boxart/32399_IGDB-188x250.jpg",
      altCsgo: "Imagem cs:go",
      //   chess
      chessLink: "https://www.twitch.tv/directory/game/Chess",
      imgChess: "https://static-cdn.jtvnw.net/ttv-boxart/743-188x250.jpg",
      altChess: "Imagem xadrez",
      //   leagueoflegends
      lolLink: "https://www.twitch.tv/directory/game/League%20of%20Legends",
      imgLol: "https://static-cdn.jtvnw.net/ttv-boxart/21779-188x250.jpg",
      altLol: "Imagem league of legends",
      //   valorant
      valorantLink: "https://www.twitch.tv/directory/game/VALORANT",
      imgValorant: "https://static-cdn.jtvnw.net/ttv-boxart/516575-188x250.jpg",
      altValorant: "Imagem valorant",
      // software
      softwareLink:
        "https://www.twitch.tv/directory/game/Software%20and%20Game%20Development",
      imgSoftware:
        "https://static-cdn.jtvnw.net/ttv-boxart/1469308723-188x250.jpg",
      altSoftware: "Imagem software",
    };
  },
};
</script>
