<template>
  <div class="note-selectors">
    <NoteSelector v-for="note in notes" :key="note.id" />
    <!-- <NoteSelector />
    <NoteSelector /> -->
  </div>
</template>

<script>
import NoteSelector from "./NoteSelector.vue";

export default {
  components: {
    NoteSelector,
  },
  data: function () {
    return {
      notes: [
        { id: 1, body: "this is my first note", timestamp: Date.now() },
        { id: 2, body: "this is my second note", timestamp: Date.now() },
        { id: 3, body: "this is my third note", timestamp: Date.now() },
      ],
    };
  },
};
</script>
