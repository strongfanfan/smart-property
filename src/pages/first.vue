<template>
    <el-col>      
        <el-col class="margB20 margT40">
            <el-col :span="6" :offset="2" class="tx-c colfff zhNum bg49b0f1">
                <div class="fs50">
                    <img src="../../static/assets/11.png" alt="">
                    <span class="count1">{{zhcount}}</span>
                </div>
                <span>住户报修</span>
            </el-col>
            <el-col :span="6" :offset="1" class="tx-c colfff zhNum bgf39500">
                <div class="fs50">
                    <img src="../../static/assets/12.png" alt="">
                    <span class="count1">{{todaycount}}</span>
                </div>
                <span>今日进出门禁人数</span>
            </el-col>
            <el-col :span="6" :offset="1" class="tx-c colfff zhNum bg49b0f1">
                <div class="fs50">
                    <img src="../../static/assets/13.png" alt="">
                    <span class="count1">0</span>
                </div>
                <span>总住户数</span>
            </el-col>
        </el-col>
        <el-col class="margT20">
            <el-col :span="7" :offset="2" class="zhNum">
                <router-link to="/smart/first/housemng" class="w100">
                <el-col :span="7">
                    <img src="../../static/assets/fcgl2.png" class="w48 margL20">
                </el-col>
                <el-col :span="16">
                    <el-col class="col333 font18">房产管理</el-col>
                    <el-col class="font12 cola7a7a7">本小区的所有房产管理</el-col>
                </el-col>
                </router-link>
            </el-col>

            <el-col :span="7" class="zhNum">
                <router-link to="/smart/first/leaseMng/lease" class="w100">
                <el-col :span="7">
                    <img src="../../static/assets/zlgl2.png" class="w48 margL20">
                </el-col>
                <el-col :span="16">
                    <el-col class="col333 font18">租赁管理</el-col>
                    <el-col class="font12 cola7a7a7">本小区的所有租赁管理</el-col>
                </el-col>
                </router-link>
            </el-col>

            <el-col :span="7" class="zhNum">
                <router-link to="/smart/first/householdMng" class="w100">
                <el-col :span="7">
                    <img src="../../static/assets/zhgl2.png" class="margL20">
                </el-col>
                <el-col :span="16">
                    <el-col class="col333 font18">住户管理</el-col>
                    <el-col class="font12 cola7a7a7">所有住户管理</el-col>
                </el-col>
                </router-link>
            </el-col>

            <el-col :span="7" :offset="2" class="zhNum">
                <router-link to="/smart/first/chargeMng/charge" class="w100">
                <el-col :span="7">
                    <img src="../../static/assets/sfgl2.png" class="margL20 w48">
                </el-col>
                <el-col :span="16">
                    <el-col class="col333 font18">收费管理</el-col>
                    <el-col class="font12 cola7a7a7">水、燃气、电等生活缴费管理</el-col>
                </el-col>
                </router-link>
            </el-col>
            
            <el-col :span="7" class="zhNum">
                <router-link to="/smart/first/carMng/cars" class="w100">
                <el-col :span="7">
                    <img src="../../static/assets/tcgl2.png" class="margL20 w48">
                </el-col>
                <el-col :span="16">
                    <el-col class="col333 font18">车位管理</el-col>
                    <el-col class="font12 cola7a7a7">车位缴费管理</el-col>
                </el-col>
                </router-link>
            </el-col>
           
        </el-col>
    </el-col>
</template>

<script>
export default {
    data() {
        return {
            zhcount: 2000,
            todaycount: 2000,
            totalcount: 2000
        }
    }
}
</script>
<style lang="scss">

</style>
