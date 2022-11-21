<template>
    <sidebar>
        <div class="sidebar">
            <div class="loginout">
                <a href="#">로그인/회원가입</a>
            </div>
            <div class="menu">
                <a href="#">내작품</a><br>
                <a href="#">스크랩</a><br>
                <a href="#">HOT게시판</a><br>
                <a href="#">자유게시판</a><br>
                <a href="#">팀원모집</a>
            </div>
        </div>
    </sidebar>
</template>

<script>
export default {

}
</script>
<style scoped>
div.sidebar {width: 150px; text-align: center; padding: 30px 0 0 45px; font-size: 20px;}
div.loginout {font-size: 19px; padding-bottom: 10px;border: 1px solid black;}
div.menu {border: 1px solid black;}
</style>