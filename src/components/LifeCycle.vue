<template>
    <div>
        <section class="section_main">
            <article class="article_main">
                <span class="article_span">

                    <img src="~@/assets/logo.png">

                </span>
            </article>
        </section>
    </div>
</template>

<script>
    export default {


        beforeMount: function(){
            console.log(`before mounted log`);
        },


        mounted: function(){


            console.log(`mounted log`);
        },


        beforeCreate: function(){
            console.log(`before create log`);

        },

        created: function(){

            console.log(`created log`);
        }
    };
</script>

<style scoped>
.section_main{


}

.article_main{


}

.article_span{


}
</style>