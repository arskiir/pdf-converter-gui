<script lang="ts">
    const dpi = [6, 3, 1]
</script>

<div class="title-bar">
    <div class="title">
        <span class="title-text accent-red">PDF</span>
        <span class="title-text">Converter</span>
    </div>
</div>

<style>
    .title-bar {
        width: 100%;
        display: flex;
    }

    .title {
        display: flex;
    }

    .title-text {
        font-family: Montserrat;
        font-style: normal;
        font-weight: bold;
        font-size: 36px;
        line-height: 44px;
        color: rgba(255, 255, 255, 0.95);
    }

    .title-text.accent-red {
        color: rgba(255, 52, 52, 0.95);
        margin-right: 10px;
    }
</style>
