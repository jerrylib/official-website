<template>
  <div id="CompanyIntroduction">
    <div class="banner container-fuild text-center"></div>
    <div class="container">
      <div class="row CompanyIntroduction-container">
        <div class="col-xs-24 col-sm-24 col-md-12">
          <div>
            <h3>考试流程</h3>
            <h4>一、驾校报名</h4>
            <p>
              需要提供资料（身份证复印、小车驾驶证复印件；需本人到现场拍摄照片、需本人到现场签字
            </p>
            <p>1、车型D（正三轮）、E（二轮）F（轻便摩托车）。</p>
            <p>年龄要求：1、车型D、E（三轮车、摩托车）年满18周岁至60岁。</p>
            <p>2、车型F（轻便摩托车）</p>
            <p>年龄要求：年满18周岁至70岁。</p>
            <h4>二、学员申领摩托车驾证业务限制</h4>
            <p>1、无论初次申领和增驾申领的学员不能有在办驾驶证业务；</p>
            <p>2、增驾申领的学员驾驶证必须满一年实习期；</p>
            <p>3、增驾学员比上一记分周期无12分记录；</p>
            <p>4、不能有吸毒记录。</p>

            <h3>理论考试注意事项</h3>
            <p>一、手机上交，考场保管。</p>
            <p>二、考试时不准左顾右盼，保持安静，认真作答。</p>
            <p>
              三、第一遍考试认真作答，每科目没有10分钟不能交卷，好比交通规则闯红灯，按不听考试员指挥论处。考完科目一，接着科目四安全文明，每科50题，每题2分，90分及格。
            </p>
            <p>四、如第二遍补考，先把信得足的做掉，不会的和模糊的空列，跳转下一题。</p>
            <p>五、科目四安全文明考试只有唯一一次机会，要谨慎作答，不要冒然交卷。否则过10天重考。</p>
            <p>六、科目四安全文明考题，最后从41题起是多选题，不仅仅是这一个答案。</p>
            <p>七、车考过程中，不许玩或者打手机，前面的人考试的路线仔细看清楚。</p>
            <p>八、拿到驾照。让大安高兴而来，满意而归是本团队的良好愿望，望大家珍惜，不要作负面宣传。</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import { WOW } from "wowjs";
export default {
  name: "CompanyIntroduction",
  data() {
    return {};
  },
  mounted() {
    var wow = new WOW();
    wow.init();
  },
};
</script>
<style scoped>
.banner {
  color: #fff;
  font-size: 30px;
  height: 150px;
  line-height: 150px;
  background-image: url("../assets/img/banner1.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  background-attachment: scroll;
  background-position: center center;
}
.row {
  margin-right: 0;
  margin-left: 0;
}
.CompanyIntroduction-container {
  padding: 100px 0;
  color: #808080;
  transition: all ease 0.5s;
}
.CompanyIntroduction-container > div > p {
  font-size: 14px;
  line-height: 2.5rem;
}
@media screen and (max-width: 997px) {
  .CompanyIntroduction-container {
    padding: 10px 0;
    color: #808080;
  }
}
</style>

