<template>
  <div id="toolbar">
      <div id="title">
          <h1>WhatsApp</h1>
      </div>
      <div id="menu">
          <nav>
              <ul>
                  <li>
                      <i class="fas fa-search fa-lg"></i>
                  </li>
                  <li>
                      <i class="fas fa-ellipsis-v fa-lg"></i>
                  </li>
              </ul>
          </nav>
      </div>
  </div>
</template>

<script>
export default {

}
</script>

<style lang="scss">

    * {
        margin: 0;
        padding: 0;
        font-family: 'Roboto', sans-serif;
    }
    #toolbar {
        width: 100%;
        height: 64px;
        background: #006156;
        display: flex;
        flex-direction: row;
        align-items: center;
        justify-content: space-between;
        
        #title {
            color: #ffffff;
            font-size: 12px;
            padding-left: 10px;
        }

        #menu {
            padding-right: 10px;
            nav {
                ul {
                    display: flex;
                    flex-direction: row;
                    gap: 15px;
                    li {
                        list-style: none;
                        i {
                            color: #ffffff;
                        }
                    }
                }
            }
        }
    }
</style>