<template>
  <div>
    <b-nav tabs>
      <b-nav-item disabled>
        <b>Quiz App</b>
      </b-nav-item>
      <b-nav-item disabled>Correct answers: {{numCorrect}} out of {{numTotal}}</b-nav-item>
    </b-nav>
  </div>
</template>

<script>
export default {
  props: ["numCorrect", "numTotal"]
};
</script>