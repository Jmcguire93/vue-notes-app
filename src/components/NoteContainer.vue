<template>
  <div class="note-container">
    <NoteSelectors />
    <!-- <NoteSelector /> -->
    <NoteEditor />
  </div>
</template>

<script>
import NoteSelectors from "./NoteSelectors.vue";
// import NoteSelector from "./NoteSelector.vue";
import NoteEditor from "./NoteEditor.vue";

export default {
  components: {
    NoteSelectors,
    // NoteSelector,
    NoteEditor,
  },
};
</script>
