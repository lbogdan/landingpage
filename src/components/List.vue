<template>
    <div>
        <b-container>
            <ListRow
                :url="require('../assets/icons/007-dumbbell.png')"
                text="abc"
                :url2="require('../assets/icons/007-dumbbell.png')"
                text2="abcd"
            />
        </b-container>
    </div>
</template>

<script>
    import ListRow from "@/components/ListRow";

    export default {
        name: "List",
        components:{
            ListRow
        }
    }
</script>

<style scoped>

    .red {
        background: red;
    }

    .green {
        background: green;
    }

    .icon-size {
        width: 100%;
        height: 100%;
    }


</style>