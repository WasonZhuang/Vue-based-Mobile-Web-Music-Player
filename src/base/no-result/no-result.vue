<template>
    <div class="no-result">
        <p class="no-result-text">{{ title }}</p>
    </div>
</template>

<script type="text/ecmascript">
    export default {
        props: {
            title: {
                type: String,
                default: ''
            }
        }
    }
</script>

<style lang="stylus" scoped rel="stylesheet/stylus">
    @import "~common/stylus/variable"
    @import "~common/stylus/mixin"

    .no-result
        text-align: center
        .no-result-text
         //margin-top: 30px
         font-size: $font-size-medium
         color: $color-text-d

</style>