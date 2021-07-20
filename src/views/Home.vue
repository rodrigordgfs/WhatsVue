<template>
  <div>
    <toolbar></toolbar>
    <tabs></tabs>
    <fab icon="fas fa-comment-alt"></fab>
  </div>
</template>

<script>

import Toolbar from '@/components/Home/toolbar'
import Tabs from '@/components/Home/tabbar'
import Fab from '@/components/shared/floatActionButton'
 
export default {
  name: 'Home',
  
  components: {
    Toolbar,
    Tabs ,
    Fab
  }
}
</script>
