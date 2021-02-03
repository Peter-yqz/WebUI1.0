<template>
<div class="container">
    <h1 style="text-align: center">XXX数据统计可视化平台</h1>
    <el-carousel :interval="4000" type="card" height="400px" width='600px'>
    <el-carousel-item v-for="item in imagesbox" :key="item.id">
    <img :src="item.idView" class="image">
    </el-carousel-item>
    </el-carousel>
    <div>
        <el-row>
        <el-col :span="8">
            <el-row>
            <el-col :span="18" class="style1">背景介绍</el-col>
            <!-- <el-col :span="6" style="background-color:rgb(200, 218, 218)"></el-col> -->
            </el-row>
            <el-row class="style1">
            <p>这里写背景介绍</p>
            <p>这里写背景介绍</p>
            <p>这里写背景介绍</p>
            <p>这里写背景介绍</p>
            <p>这里写背景介绍</p>
            <p>这里写背景介绍</p>
            </el-row>
        </el-col>
        <el-col :span="8">
            <el-row>
            <el-col :span="18" class="style2">项目简介</el-col>
            <!-- <el-col :span="6" style="background-color:rgb(200, 218, 218)"></el-col> -->
            </el-row>
            <el-row class="style2">
            <p>这里写项目简介</p>
            <p>这里写项目简介</p>
            <p>这里写项目简介</p>
            <p>这里写项目简介</p>
            <p>这里写项目简介</p>
            <p>这里写项目简介</p>
            </el-row>
        </el-col>
        <el-col :span="8">
            <el-row>
            <el-col :span="18" class="style3">平台简介</el-col>
            <!-- <el-col :span="6" style="background-color:rgb(200, 218, 218)"></el-col> -->
            </el-row>
            <el-row class="style3">
            <p>这里写平台简介</p>
            <p>这里写平台简介</p>
            <p>这里写平台简介</p>
            <p>这里写平台简介</p>
            <p>这里写平台简介</p>
            <p>这里写平台简介</p>
            </el-row>
        </el-col>
        </el-row>
        <el-row>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
            <p style="text-align:center"><i class="el-icon-s-opportunity">这里还不知道写点什么</i></p>
        </el-row>
    </div>
</div>
</template>
<script>
    export default {
        data(){
            return {
                imagesbox:[
                {id:0,idView:require("../../assets/pic1.jpg")},      
                {id:1,idView:require("../../assets/pic2.jpg")},
                {id:2,idView:require("../../assets/pic3.jpg")}
                ]
            }
        }
    }
</script>

<style scoped>
.container{
    background-color: white;
    box-sizing: border-box;
}
.style1{
    border-radius: 4px;
    background-color: rgb(0, 255, 255);
    text-align: center;
}
.style2{
    border-radius: 4px;
    background-color: rgb(0, 255, 179);
    text-align: center;
}
.style3{
    border-radius: 4px;
    background-color: rgb(0, 153, 255);
    text-align: center;
}
</style>