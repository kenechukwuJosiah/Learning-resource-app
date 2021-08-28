<template>
  <section>
    <h2>{{ topicTitle ? topicTitle : titlePlaceholder }}</h2>
    <p>{{ text ? text : placeholder }}</p>
  </section>
</template>

<script>
export default {
  props: ['topicTitle', 'text'],
  data() {
    return {
      placeholder:
        'Lorem ipsum dolor sit, amet consectetur adipisicing elit. Corrupti ratione quia quidem possimus impedit sit! Aspernatur earum amet itaque aliquam illum necessitatibus provident dolore eos libero, minus repellendus magni, unde sint quidem inventore soluta dolor at in! Labore cum nihil alias neque cupiditate. Quam praesentium in tempore error nostrum aperiam mollitia blanditiis laudantium facere similique modi velit nisi quis laborum, nulla atque excepturi qui pariatur. Blanditiis ad est illo, repellendus fuga accusantium vitae asperiores culpa debitis, eos nulla incidunt animi!',
      titlePlaceholder: 'Write Clean Lorem Ipsum'
    };
  }
};
</script>
