<template>
    <div class="regBox">
        <div class="login_cont">
            <ul class="login">
                <li><span class="reg_item"><i>*</i>账户名:</span><div class="input_item"><input type="text" class="login_input user_icon"></div></li>
                <li><span class="reg_item"><i>*</i>密码</span><div class="input_item"><input type="text" class="login_input user_icon"></div></li>
                <li><span class="reg_item"><i>*</i>验证码</span><div class="input_item"><input type="text" class="login_input user_icon"></div></li>
                <li><span class="reg_item"><i>*</i>确认密码:</span><div class="input_item"><input type="text" class="login_input user_icon"></div></li>
                <li><span class="reg_item">&nbsp;</span><input type="checkbox" id="t1" class="checked"><label for="t1">我已阅读并同意《用户注册协议》</label></li>
                <li><span class="reg_item">&nbsp;</span><router-link to="../../login"><input type="button" class="reg_btn"></router-link></li>
            </ul>
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
.regBox{
    width: 628px;
    margin: 10px auto;
    border: #ccc solid 1px;
}
.reg_item{
    font: 14px/34px "宋体";
    width: 110px;
    text-align: center;
    float: left;
}
.reg_item i{
    color: red;
    font-style: normal;
    margin-right: 5px;
}
.input_item{
    width: 306px;
    float: left;
}
.regBox li{
    height: 70px;
    vertical-align: top;
}
.regBox .autoLogin{
    height: 46px;
    padding: 0;
}
.regBox .login_cont{
    padding: 35px 76px 20px 76px;
}
.reg_btn{
    width:309px;height: 36px;
   background:url(../../images/注册.gif) left top no-repeat;
}
.login_input{border:#999 solid 1px; height:32px; line-height:32px\9; text-indent:5px; width:100%;}
.user_icon{background:url(../../images/header.gif) right top no-repeat;}
</style>
