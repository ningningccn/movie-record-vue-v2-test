<template>
    <header class="container relative my-8 flex h-[48px] justify-between">
        <img src="@/assets/images/register-logo.png" alt="" class="h-[48px]" />
        <div class="flex gap-x-10">
            <button type="button" class="flex items-center gap-x-2 hover:text-primary">
                <img src="@/assets/icons/PlusSquare.svg" alt="" />
                添加
            </button>
            <button type="button" class="flex items-center gap-x-2">
                <img src="@/assets/icons/MagnifyingGlass.svg" alt="" />
                搜尋
            </button>
            <button
                type="button"
                class="flex items-center gap-x-[10px] rounded-lg border border-primary px-6 py-2 text-primary"
            >
                <img src="@/assets/icons/SignIn.svg" alt="" class="h-8 w-8" />登出
            </button>
        </div>
    </header>
</template>

<script setup></script>

<style lang="postcss" scoped></style>
