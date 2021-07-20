<template>
  <a href="#">
      <i :class="icon"></i>
  </a>
</template>

<script>
export default {
    name: 'floatActionButton',

    props: {
        icon: {
            type: String,
            required: true
        }
    }
}
</script>

<style lang="scss">
    a {
        padding: 20px;
        border-radius: 50%;
        background: #00E365;
        box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.6);
        position: fixed;
        bottom: 10px;
        right: 10px;
        transition: 0.2s ease-in;
        &:hover {
            background: #006156;
        }
        i {
            color: #ffffff;
        }
    }
</style>