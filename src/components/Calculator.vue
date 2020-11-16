<template>
    <div class="calc">
        <div class="basic-calc">
            <div class="display">Hello</div>
            <div class="control-btn">
                <div class="btn">C</div>
                <div class="btn">Del</div> 
            </div>
            <div class="other-btns">
                <div class="num-block">
                    <div class="num">7</div>
                    <div class="num">8</div>
                    <div class="num">9</div>
                    <div class="num">4</div>
                    <div class="num">5</div>
                    <div class="num">6</div>
                    <div class="num">1</div>
                    <div class="num">2</div>
                    <div class="num">3</div>
                    <div class="num">0</div>
                    <div class="num">.</div>
                    <div class="num operator">/</div>
                </div>
                <div class="operator-block">
                    <div class="btn operator">x</div>
                    <div class="btn operator">-</div>
                    <div class="btn operator">+</div>
                    <div class="btn operator">=</div>
                </div>    
            </div>
        </div>
    </div>
</template>

<script>

export default {
    name: "Calculator",
    props: {

    },
}

</script>

<style lang="sass" scoped>

    .basic-calc
        display: flex
        flex-direction: column
        margin: 0 auto
        width: 400px
        font-size: 40px 
    
    .display 
        width: 100%
        background-color: #333 !important
        color: #fff

    .control-btn
        width: 100%
        display: flex
        flex-direction: row

        .btn 
            width: 50%

    .other-btns 
        width: 100%
        display: flex
        flex-direction: row

        .num-block
            width: 75%
            display: flex
            flex-direction: row
            flex-wrap: wrap

            .num
                width: 32%
                flex-grow: 1
                background-color: #f2f2f2
                border: 1px solid #999
                cursor: pointer


        .operator-block 
            width: 25%
            display: column
            flex-wrap: wrap
            

    .btn     
        background-color: #f2f2f2
        border: 1px solid #999
        cursor: pointer

    .operator 
        background-color: rgb(49, 120, 148)
        color: #fff 
        
</style>