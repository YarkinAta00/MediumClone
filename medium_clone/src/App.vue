<script>
import Navbar from './components/Navbar.vue'
import BigTitlePart from './components/BigTitlePart.vue'
import Articles from './components/Articles.vue'
import BottomArticles from './components/BottomArticles.vue'
export default {
  name: 'App',
  components: {
    Navbar,
    BigTitlePart,
    Articles,
    BottomArticles,
  }
}
</script>

<template>
 <Navbar />
  <BigTitlePart />
  <Articles />
  <BottomArticles />

</template>

