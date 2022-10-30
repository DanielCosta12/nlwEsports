<template>
  <section>
    <div>
      <h2>{{ h2 }}</h2>
      <p>{{ p }}</p>
      <ul class="channel-list">
        <li>
          <a :href="linkGaules" target="_blank">
            <img :src="imgGaules" :alt="altGaules" />
          </a>
        </li>
        <li>
          <a :href="linkKrikor" target="_blank">
            <img :src="imgKrikor" :alt="altKrikor" />
          </a>
        </li>
        <li>
          <a :href="linkMch_agg" target="_blank">
            <img :src="imgMch_agg" :alt="altMch_agg" />
          </a>
        </li>
        <li>
          <a :href="linkFallen" target="_blank">
            <img :src="imgFallen" :alt="altFallen" />
          </a>
        </li>
        <li>
          <a :href="linkVinicin" target="_blank">
            <img :src="imgVinicin" :alt="altVinicin" />
          </a>
        </li>
        <li>
          <a :href="linkLiminha" target="_blank">
            <img :src="imgLiminha" :alt="altLiminha" />
          </a>
        </li>
      </ul>
    </div>
  </section>
</template>
<script>
export default {
  name: "ChannelsAndStreamers",
  data() {
    return {
      h2: "Canais e streamers",
      p: "Lista de canais e transmissões que não perco!",

      //   gaules
      linkGaules: "https://www.twitch.tv/gaules",
      imgGaules:
        "https://static-cdn.jtvnw.net/jtv_user_pictures/f4b12683-57ff-4b57-926a-67512b43a7ff-profile_image-150x150.png",
      altGaules: "Imagem canal do gaules",
      //   krikor
      linkKrikor: "https://www.twitch.tv/gmkrikor",
      imgKrikor:
        "https://static-cdn.jtvnw.net/jtv_user_pictures/9cad722a-b493-4b1d-9cca-93da0cfdcbc5-profile_image-150x150.png",
      altKrikor: "Imagem canal do krikor",
      // mch_agg
      linkMch_agg: "https://www.twitch.tv/mch_agg",
      imgMch_agg:
        "https://static-cdn.jtvnw.net/jtv_user_pictures/dfb0cef3-87ca-4f09-9f52-7d7de319afbb-profile_image-150x150.png",
      altMch_agg: "Imagem canal do mch_agg",
      // fallen
      linkFallen: "https://www.twitch.tv/gafallen",
      imgFallen:
        "https://static-cdn.jtvnw.net/jtv_user_pictures/e8b0563d-a036-4bd6-bf3e-5d6b2e9300cf-profile_image-150x150.png",
      altFallen: "Imagem canal do fallen",
      //   vinicin
      linkVinicin: "https://www.twitch.tv/vinicin_lil",
      imgVinicin:
        "https://static-cdn.jtvnw.net/jtv_user_pictures/5549cdb8-4669-4430-b217-e1602a361abf-profile_image-150x150.png",
      altVinicin: "Imagem canal do vinicin",
      // liminha
      linkLiminha: "https://www.twitch.tv/liminhag0d",
      imgLiminha:
        "https://static-cdn.jtvnw.net/jtv_user_pictures/308fa859-303d-44eb-a383-96eb6c18e78a-profile_image-70x70.png",
      altLiminha: "Imagem canal do liminha",
    };
  },
};
</script>
