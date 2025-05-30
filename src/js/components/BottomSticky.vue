<template>
  
</template>
<script>

export default {
    props: {
        unitSystem: {
            type: String
        }
    },
    data: () => ({
        
    }),
    methods: {
        test: () => {
            alert('test')
        }
    },
    computed: {
        units: () => {
            return 'US'
        }
    },
    created() {
        //
    }
}
</script>