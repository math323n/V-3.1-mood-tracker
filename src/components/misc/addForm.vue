<template>
  <form class="flex flex-col space-y-2">
    <h2>Hvordan har du det?</h2>
    <input type="text" placeholder="titel" />
    <emojisRating class="mx-auto" />
    <h2>Beskrivelse</h2>
    <textarea type="text" placeholder="Skriv her..." />
    <submitButton class="mx-auto" />
    <cancel-button class="mx-auto" />
  </form>
</template>

<script>
import EmojisRating from "./emojisRating.vue";
import SubmitButton from "../buttons/submitButton.vue";
import CancelButton from "../buttons/cancelButton";

export default {
  name: "AddForm",
  components: {
    EmojisRating,
    SubmitButton,
    CancelButton,
  },
};
</script>