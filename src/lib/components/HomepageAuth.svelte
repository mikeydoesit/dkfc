<style>
    .auth {
        @apply px-2 mb-24;
    }
    .btn {
        @apply rounded-xl flex justify-center items-center py-4 mb-3 font-bold;
    }
    .join_btn {
        @apply border-2 border-primary text-primary;
    }
    .login_btn {
        @apply border-2 bg-primary text-white;
    }
    .forgot {
        @apply px-2;
    }
</style>

<section class="auth">
    <div class="join_btn btn">
        <span>JOIN NOW</span>
    </div>
    <div class="login_btn btn">
        <span>MEMBER LOGIN</span>
    </div>
    <a class="forgot" href="/auth">Forgot password</a>
</section>