<template>
  <EpisodeCard
    title="Klarede opvasken"
    rating="4"
    date="15 min siden"
    description="Kunne ikke overskue at vaske op hele sidste ige. Klarede det endeligt efter af have snakket med Niels"
  />
  <EpisodeCard
    title="Gik en lang tur"
    rating="3"
    date="I går kl 12"
    description="Gik en mega lang tur i skoven. Alle bladene og de flotte farver gjorde mig varm inden i"
  />
  <EpisodeCard
    title="S-tog"
    rating="1"
    date="I går kl 07.30"
    description="Tog toget til skole. En klam stodder der lugtede af sveskehud satte sig ved siden af mig og var totalt creepy"
  />
</template>

<script>
import EpisodeCard from "../cards/episodeCard.vue";
export default {
  name: "episodeCardList",
  components: {
    EpisodeCard,
  },
};
</script>