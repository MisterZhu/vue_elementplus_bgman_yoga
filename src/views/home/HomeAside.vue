<script lang="ts" setup>
import { isCollapse } from "./isCollapse";
</script>

<template>
    <el-aside>
        <el-menu router unique-opened :collapse="isCollapse">
            <a href="/" class="logo">
                <img src="@/assets/img/log.svg" alt="">
                <h1>课后学堂</h1>
            </a>

            <el-sub-menu index="1">
                <template #title>
                    <el-icon>
                        <IEpHomeFilled />
                    </el-icon> 
                    <span>课程管理</span>
                </template>
                <el-menu-item index="/course">
                    <el-icon>
                        <IEpTickets />
                    </el-icon>
                    <span>瑜伽课程</span>
                </el-menu-item>
                
            </el-sub-menu>

            <el-sub-menu  index="2">
                <template #title>
                    <el-icon>
                        <IEpUserFilled />
                    </el-icon>

                    <span>用户管理</span>
                </template>
                <el-menu-item  index="/about">
                    <el-icon>
                        <IEpUser />
                    </el-icon>
                    <span>用户员</span>
                </el-menu-item>
                <el-menu-item  index="/about">

                    <el-icon>
                        <IEpUser />
                    </el-icon>
                    <span>用户token</span>
                </el-menu-item>
                <el-menu-item  index="/about">
                    <el-icon>
                        <IEpUser />
                    </el-icon>
                    <span>微信token</span>
                </el-menu-item>
            </el-sub-menu>
            <el-sub-menu index="3">
                <template #title>
                    <el-icon>
                        <IEpUploadFilled />
                    </el-icon>
                    <span>系统管理</span>
                </template>
                <el-menu-item  index="/system">
                    <el-icon>
                        <IEpPicture />
                    </el-icon>
                    <span>图片管理</span>
                </el-menu-item>
                <el-menu-item  index="/system">
                    <el-icon>
                        <IEpFolderRemove />
                    </el-icon>
                    <span>数据字典</span>
                </el-menu-item>
            </el-sub-menu>
        
        </el-menu>
    </el-aside>
</template>

<style lang="scss" scoped>
.el-aside {
    background-color: #e9e9eb;
    height: 100vh;
    width: auto;
}

.el-menu {
    background-color: #e9e9eb;
    border-right: none;
    width: 150px;

    &.el-menu--collapse {
        width: 60px;

        & h1 {
            display: none;
        }
    }
}


.logo {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60px;
    text-decoration: none;
    color: black;

    img {
        width: 32px;
        height: 32px;
    }
}</style>
