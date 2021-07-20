<template>
  <div id="tabs">
      <button id="camera"><i class="fas fa-camera fa-lg"></i></button>
      <button id="chats" class="active">Conversas</button>
      <button id="status">Status</button>
      <button id="calls">Chamadas</button>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">
    #tabs {
        width: 100%;
        height: 64px;
        background: #006156;
        display: flex;
        flex-direction: row;
        flex-wrap: nowrap;
        box-shadow: 0 4px 4px rgba(0, 0, 0, 0.4);
        button {
            background: none;
            border: none;
            outline: none;
            color: #ffffff;
            opacity: 0.7;
            font-size: 16px;
            font-family: 'Roboto',  sans-serif;
        }
        #camera {
            flex: 1
        }
        #chats {
            flex: 2
        }
        #status {
            flex: 2
        }
        #calls {
            flex: 2
        }
        .active {
            border-bottom: 3px solid #ffffff;
            opacity: 1;
        }
    }
</style>