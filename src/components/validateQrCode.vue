<template>
    <div class="validate-qrcode">
        <van-icon name="scan" class="validate-qrcode-icon" />
        <van-button type="primary" size="large" class="validate-btn">点击扫描验真伪</van-button>
    </div>
</template>

<script>
    export default {
        name: "validateQrCode"
    }
</script>

<style scoped>
    .validate-qrcode {
        text-align: center;
        width: 100%;
        height: 100%;
        position: relative;
    }
    .validate-qrcode-icon {
        font-size: 10rem;
        display: inline-block;
        position: absolute;
        top: 50%;
        left: 50%;
        margin-top: -5rem;
        margin-left: -5rem;
        color: #00c4ff;
    }
    .validate-btn {
        position: absolute;
        bottom: 0;
        left: 0;
    }
</style>