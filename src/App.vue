<template>
  <div>
    <MyCalculator />
  </div>
</template>

<script>
import MyCalculator from "./components/My-calculator.vue";

export default {
  name: "App",
  components: {
    MyCalculator,
  },
};
</script>

<style lang="scss">
:root {
  // ==============
  //    THEME 1
  // ==============

  // background
  --theme1-main-background: hsl(222, 26%, 31%);
  --theme1-toggle-background: hsl(223, 31%, 20%);
  --theme1-keypad-background: hsl(223, 31%, 20%);
  --theme1-screen-background: hsl(224, 36%, 15%);
  --theme1-toggle: hsl(6, 63%, 50%);

  // keys
  --theme1-delete-key-background: hsl(225, 21%, 49%);
  --theme1-delete-key-hover: hsl(225, 53%, 70%);
  --theme1-delete-key-shadow: hsl(224, 28%, 35%);
  --theme1-equal-key-background: hsl(6, 63%, 50%);
  --theme1-equal-key-hover: hsl(6, 78%, 65%);
  --theme1-equal-key-shadow: hsl(6, 70%, 34%);
  --theme1-main-key-background: hsl(30, 25%, 89%);
  --theme1-main-key-hover: hsl(0, 0%, 97%);
  --theme1-main-key-shadow: hsl(28, 16%, 65%);

  // Text
  --theme1-text-black: hsl(221, 14%, 31%);
  --theme1-text-white: hsl(0, 0%, 100%);

  // ==============
  //    THEME 2
  // ==============

  // background
  --theme2-main-background: hsl(0, 0%, 90%);
  --theme2-toggle-background: hsl(0, 5%, 81%);
  --theme2-keypad-background: hsl(0, 5%, 81%);
  --theme2-screen-background: hsl(0, 0%, 93%);
  --theme2-toggle: hsl(25, 98%, 40%);

  // keys
  --theme2-delete-key-background: hsl(185, 42%, 37%);
  --theme2-delete-key-hover: hsl(185, 40%, 50%);
  --theme2-delete-key-shadow: hsl(185, 58%, 25%);
  --theme2-equal-key-background: hsl(25, 98%, 40%);
  --theme2-equal-key-hover: hsl(25, 100%, 60%);
  --theme2-equal-key-shadow: hsl(25, 99%, 27%);
  --theme2-main-key-background: hsl(45, 7%, 89%);
  --theme2-main-key-hover: hsl(0, 0%, 84%);
  --theme2-main-key-shadow: hsl(35, 11%, 61%);

  // Text
  --theme2-text-black: hsl(60, 10%, 19%);
  --theme2-text-white: hsl(0, 0%, 100%);

  // ==============
  //    THEME 3
  // ==============

  // background
  --theme3-main-background: hsl(268, 75%, 9%);
  --theme3-toggle-background: hsl(268, 71%, 12%);
  --theme3-keypad-background: hsl(268, 71%, 12%);
  --theme3-screen-background: hsl(268, 71%, 12%);
  --theme3-toggle: hsl(176, 100%, 44%);

  // keys
  --theme3-delete-key-background: hsl(281, 89%, 26%);
  --theme3-delete-key-hover: hsl(281, 77%, 35%);
  --theme3-delete-key-shadow: hsl(285, 91%, 52%);
  --theme3-equal-key-background: hsl(176, 100%, 44%);
  --theme3-equal-key-hover: hsl(176, 100%, 53%);
  --theme3-equal-key-shadow: hsl(177, 92%, 70%);
  --theme3-main-key-background: hsl(268, 47%, 21%);
  --theme3-main-key-hover: hsl(268, 61%, 35%);
  --theme3-main-key-shadow: hsl(290, 70%, 36%);

  // Text
  --theme3-text-yellow: hsl(52, 100%, 62%);
  --theme3-text-black: hsl(198, 20%, 13%);
  --theme3-text-white: hsl(0, 0%, 100%);

  // ==============
  //     Fonts
  // ==============

  --font-family: "League Spartan", sans-serif;
  --font-bold: 700;
}

*,
*::after,
*::before {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: var(--font-family);
  overflow: hidden;
}
</style>
