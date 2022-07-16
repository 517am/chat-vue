<script>

</script>

<template>
    <div class="wrapperSearch">
        <div class="search-user">
            <span>?</span>
        </div>
        <div class="listForChoose">
            <ul>
                <li> <img src="../assets/image/icon-user.png" alt="" /></li>
                <li> <img src="../assets/image/icon-user.png" alt="" /></li>
                <li> <img src="../assets/image/icon-user.png" alt="" /></li>
            </ul>
        </div>
    </div>
</template>

<style>
    .wrapperSearch{
        position: absolute;
        top: -150px;
        left: -150px;
        background: #f5f5f5;
        width: 350px;
        height: 340px;
        border-radius: 50%;
    }

        .search-user{
            width: 200px;
            height: 200px;
            background-color: black;
            position: absolute;
            top: 50px;
            right: 100px;
            border-radius: 50%;
        }

        .search-user span{
            position: absolute;
            right: 50px;
            top: 110px;
            font-size: 50px;
        }

    img{
        width: 70px;
    }
</style>