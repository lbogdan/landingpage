<template>
    <div>
        <b-container>
            <ListRow url="assets/icons/007-dumbbell.png" text="abc" url2="/img/007-dumbbell.d5390bc2.png" text2="abcd"></ListRow>
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