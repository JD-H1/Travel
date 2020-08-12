<template>
    <div class="loginBox">
        <div class="login_cont">
            <ul class="login">
                <li class="I_tit">邮箱/用户名/手机号</li>
                <li class="mb_10"><input type="text" class="login_input user_icon"></li>
                <li class="I_tit">密码</li>
                <li class="mb_10"><input type="text" class="login_input user_icon2"></li>
                <li class="autoLogin"><input type="checkbox" id="a1" class="checked"><label for="a1">自动登陆</label></li>
                <li><router-link to="./"><input type="button" class="login_btn"></router-link></li>
            </ul>
        </div>
        <div class="login_partners">
            <p class="I_tit">使用合作方账号登陆网站</p>
            <ul class="login_list clearfix">
                <li><a href="#">QQ</a></li>
                <li><span>|</span></li>
                <li><a href="#">网易</a></li>
                <li><span>|</span></li>
                <li><a href="#">新浪微博</a></li>
                <li><span>|</span></li>
                <li><a href="#">腾讯微博</a></li>
                <li><span>|</span></li>
                <li><a href="#">微信</a></li>
                <li><span>|</span></li>
                <li><a href="#">手机号码</a></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.loginBox{width:458px; border:#999 solid 1px; margin:10px auto; padding:15px 40px; position:relative;}
.login_cont{padding:15px 76px;}
.l_tit{color:#666; line-height:20px;}
.login_input{border:#999 solid 1px; height:32px; line-height:32px\9; text-indent:5px; width:100%;}
.user_icon{background:url(../../images/header.gif) right top no-repeat;}
.user_icon2{background:url(../../images/mima.gif) right top no-repeat;}
.mb_10{margin-bottom:10px;}
.autoLogin{padding-top:27px; padding-bottom:28px;}
.checked{position:relative; top:3px; margin-right:3px;}
.login_btn{width:309px; height:36px; background:url(../../images/dl.gif) left top no-repeat;}
.login_partners{padding-top:34px; padding-left:80px;}
.login_list li{float:left; line-height:20px;}
.login_list span{color:#999; margin:0 2px;}

</style>
