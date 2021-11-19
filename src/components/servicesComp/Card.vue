<template>
    <b-container class="card-temp">
        <b-row>
            <b-col col lg="4" md="6" sm="12" class="text-center">
                <div class="icons">
                    <font-awesome-icon icon="pencil-alt"/>
                </div>
                <div class="hr"></div>
                <div class="con">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea distinctio quibusdam tempore itaque possimus a incidunt aperiam repellat porro tempora, dolores magni optio qui quo totam rem sed ducimus facere unde excepturi, laboriosam aut esse. Repellat vero tempore obcaecati autem.</p>
                </div>
            </b-col>
            <b-col col lg="4" md="6" sm="12" class="text-center">
                <div class="icons">
                    <font-awesome-icon icon="plug"/>
                </div>
                <div class="hr"></div>
                <div class="con">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea distinctio quibusdam tempore itaque possimus a incidunt aperiam repellat porro tempora, dolores magni optio qui quo totam rem sed ducimus facere unde excepturi, laboriosam aut esse. Repellat vero tempore obcaecati autem.</p>
                </div>
            </b-col>
            <b-col col lg="4" md="6" sm="12" class="text-center">
                <div class="icons">
                    <font-awesome-icon icon="tv"/>
                </div>
                <div class="hr"></div>
                <div class="con">
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ea distinctio quibusdam tempore itaque possimus a incidunt aperiam repellat porro tempora, dolores magni optio qui quo totam rem sed ducimus facere unde excepturi, laboriosam aut esse. Repellat vero tempore obcaecati autem.</p>
                </div>
            </b-col>
        </b-row>
    </b-container>
</template>
<style>
    .card-temp {
        margin: 50px 0;
    }
    .icons{
        font-size: 70px;
    }
    .hr{
        width: 40px;
        height: 2px;
        background-color: var(--main-color);
        margin: 10px auto;
    }
</style>
<script>
    export default {
        name: "Card"
    }
</script>
