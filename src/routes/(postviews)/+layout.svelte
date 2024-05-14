<div class="wrap">
    <div class="inner">
        <div class="sidebar">
        </div>
        <slot/>
    </div>
</div>

<style lang="scss">
    .wrap {
        width: 100%;
        height: 100%;
        display: flex;
        align-items: start;
        justify-content: center;
    }

    .inner {
        width: 80%;
        height: 100%;
    }
</style>