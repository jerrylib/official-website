<template>
  <div id="footer" class="container-fluid">
    <div class="logo"></div>
    <!-- <p class="title">公司企业网站模板</p> -->
    <div class="address_tel_fax">
      <span
        >地址：宁德市福安市城北街道棠兴路300号3楼玲珑驾校（凯兴酒店对面）</span
      >
      <div>
        <span>Tel：13509588803</span>
        <span>Tel：0593-6668337</span>
        <span>Tel：18060323611</span>
      </div>
      <!-- <span>Fax：8888-88888888</span> -->
    </div>
    <!-- <p class="email_wx">
      <span>邮箱：liyunkun_11@163.com</span>
      <span>公司微信号：ilyk_gg</span>
    </p> -->
    <p class="copy">
      Copyright &copy; {{ year - 1 }} -
      {{ year + 1 }} 福安市玲珑摩托车培训有限公司
    </p>
  </div>
</template>
<script>
export default {
  name: "Footer",
  data() {
    return {
      year: new Date().getFullYear(),
    };
  },
};
</script>
<style scoped>
#footer {
  width: 100%;
  height: 100%;
  color: #fff;
  background: #474747;
  overflow: hidden;
  text-align: center;
}
.logo {
  width: 95px;
  height: 45px;
  margin: 50px auto 20px;
}
.title {
  font-size: 25px;
  margin-bottom: 20px;
}
.address_tel_fax {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0;
}
.email_wx {
  color: #d3d3d3;
  font-size: 14px;
}
.copy {
  color: #d3d3d3;
  font-size: 14px;
  margin: 10px 0 10px;
}
@media screen and (max-width: 997px) {
  .title {
    font-size: 20px;
  }
  .address_tel_fax {
    font-size: 12px;
  }
  .email_wx {
    font-size: 12px;
  }
  .copy {
    font-size: 12px;
    margin: 30px 0 10px;
  }
}
</style>

