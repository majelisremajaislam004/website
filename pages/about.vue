<template>
    <main>
      <div class="fixed-top">
        <navbar/>
      </div>
            <div class="container" style="margin-top: 2rem;">
                <div class="row justify-content-center" >
                    
                </div>
            </div>
        <end/>
    </main>
</template>

<script>
export default {
      mounted() {
    console.log (this.$supabase)
  },
  data() {
    return {
      his: '',
    }
  },
  mounted () {
    this.ambildata()
  },
  methods: {
    async ambildata() {
      const { data, error } = await this.$supabase
      .from('struks')
      .select()
      if(data)
      this.his = data
      if(error) console.log(error)
    }
  }
}
</script>
