<template>
    <div>
      <p>hello</p>
    </div>
</template>


<script>
  import headTop from '~/components/header/head'


  export default {
    data () {
      return {
        geoHash: '',
        msietTitle: '请选择地址...'
      }
    },
   /* async asyncData ({params}) {
      let result = {}
      console.log('param.geohash', params.geohash)
      if (!params.geohash) {
        const {data} = await axios.get(`/v1/cities`, {params: {type: 'guess'}})
        result.geohash = data.latitude + ',' + data.longitude
      } else {
        result.geohash = params.geohash
      }
      return result
    }, */
    // async beforeMount () {
    //   console.log('this.$route.query.geohash', this.$route.query.geohash)
    //   if (!this.$route.query.geohash) {
    //     const address = await cityGuess()
    //     this.geohash = address.latitude + ',' + address.longitude
    //   } else {
    //     this.geohash = this.$route.query.geohash
    //   }
    // },
    components: {
      // headTop
    }
  }
</script>

