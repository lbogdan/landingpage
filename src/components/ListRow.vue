<template>
    <b-row>
        <b-col>
            <b-row>
                <b-col>
                    <div class="floatRight">
                        <img :src="url"  width="100px" height="100px">
                    </div>
                </b-col>
                <b-col>
                    <p class>{{text}}</p>
                </b-col>
            </b-row>
        </b-col>

        <b-col>
            <b-row>
                <b-col>
                    <p class="floatRight">{{text2}}</p>
                </b-col>
                <b-col>
                    <div class="floatLeft">
                        <b-img :src="url2" height="100%" width="100%"></b-img>
                    </div>
                </b-col>
            </b-row>
        </b-col>
    </b-row>
</template>

<script>
    export default {
        name: "ListRow",
        props:{
            url: String,
            text: String,

            url2: String,
            text2: String,
        }
    }
</script>

<style scoped>

    .floatRight{
        float: right;
    }

    .floatLeft{
        float: left;
    }

</style>