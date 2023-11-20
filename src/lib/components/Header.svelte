<style>
    .header {
        @apply flex flex-row h-auto w-full justify-between items-end pt-16 pb-4 px-4 bg-primary;
    }
    .left_col, .right_col {
        @apply h-auto flex flex-row items-center;
    }
    .btn_wrapper {
        @apply h-7 w-7 cursor-pointer;
    }
    .btn_wrapper img {
        @apply h-full w-full;
    }
    h1 {
        @apply text-white font-bold text-xl;
    }
</style>

<section class="header">
    <div class="left_col">
        <h1>Welcome</h1>
    </div>
    <div class="right_col">
        <div class="btn_wrapper">
            <img src="/images/menu.png" alt="hamburger menu" />
        </div>
    </div>
</section>