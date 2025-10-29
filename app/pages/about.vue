<template>
    <div class="px-2 sm:px-0">
        <div
            class="flex flex-col items-center mx-auto my-auto space-y-6 mt-10 sm:mt-20 w-full"
        >
            <p class="sm:text-4xl text-4xl font-bold mb-5">About Me</p>
        </div>
        <section class="about-cover-letter">
            <div class="cover-letter-card">
                <h1 class="mb-5">👋 Hi, I'm <strong>Someone!</strong>!</h1>
                <p>I'm just the random person...</p>
                <br /><br />
                <div class="signature">
                    <span>{{ theAuthor }}</span>
                </div>
            </div>
        </section>
    </div>
</template>
<script lang="ts" setup>
const theAuthor: string = "Jackson Paxton";
</script>

<style scoped></style>
