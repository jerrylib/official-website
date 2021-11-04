<template>
    <div id="CompanyIntroduction">
        <div class="banner container-fuild text-center"></div>
        <div class="container">
            <div class="row CompanyIntroduction-container">
                <div class="col-xs-12 col-sm-12 col-md-6 wow zoomIn">
                    <img class="img-responsive center-block" src="@/assets/img/banner6.jpg">
                </div>
                <div class="col-xs-12 col-sm-12 col-md-6">
                    <h3>福安市玲珑摩托车培训有限公司</h3>
                    <p class=".text-justify">福安市玲珑摩托车培训有限公司驾照培训网至今培训了近千名摩托驾驶员，训练全部在福安市中心城区，设施齐全的专业化摩托车培训驾校。同时代办摩托车、三轮车上牌、年审，报废。凡我处毕业学员享受VIP待遇。学员遍及全国各地。李教练，教学经验丰富，技术精淇，学员上手快，合格率高，本着专业、专心、专注的精神，数年如一日全身心投入摩托车驾照培训事业，培训部本着快速、高效、廉洁的精神，为社会服务，深受广大学员好评。</p>
                    <!-- <p class=".text-justify">我们的客户包括集团上市公司, 酒店, IT科技, 教育, 服装, 贸易, 外贸, 时尚, 生物, 工业, 制造等众多行业, 并树立了良好的口碑, 积累了丰富的经验和成功案例. 我们提供权威专业的互联网品牌策划, 并实施高标准的设计方案, 创造真正意义上的品牌网站, 为互联网品牌在互动行销领域创造最大价值而不懈努力!</p> -->
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import { WOW } from 'wowjs';
export default {
    name: 'CompanyIntroduction',
    data(){
        return{

        }
    },
    mounted(){
        var wow = new WOW();
        wow.init();
    }
}
</script>
<style scoped>
.banner{
    color: #fff;
    font-size: 30px;
    height: 150px;
    line-height: 150px;
    background-image: url('../assets/img/banner1.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    background-attachment: scroll;
    background-position: center center;
}
.row{
    margin-right: 0;
    margin-left: 0;
}
.CompanyIntroduction-container{
    padding: 100px 0;
    color: #808080;
    transition: all ease 0.5s;
}
.CompanyIntroduction-container>div>p{
    font-size: 14px;
    line-height: 2.5rem;
}
@media screen and (max-width: 997px){
    .CompanyIntroduction-container{
    padding: 10px 0;
    color: #808080;
}
}
</style>

