<template>
    <q-page class="q-pa-md row justify-center">
        <div class="q-pa-md items-start q-gutter-md text-h1">
             This is the main layout for lessons
        </div>
        <div class="row">
            <div class="q-pa-md">
                <q-card class="my-card">
                <q-video
                    frameborder="0"
                    allowfullscreen
                    :ratio="16/9"
                    src="https://www.youtube.com/embed/mTv4RYEkGkQ"
                />

                <q-card-section>
                    <div class="text-h6">Lesson 1</div>
                    <div class="text-subtitle2">How to use product 1</div>
                </q-card-section>

                <q-card-section class="q-pt-none">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                    eiusmod tempor incididunt ut labore et dolore magna aliqua.
                </q-card-section>
                </q-card>
            </div>
            <div class="q-pa-md">
                <q-card class="my-card">
                <q-video
                    frameborder="0"
                    allowfullscreen
                    :ratio="16/9"
                    src="https://www.youtube.com/embed/7HpCJov3Uj0"
                />

                <q-card-section>
                    <div class="text-h6">Lesson 2</div>
                    <div class="text-subtitle2">How to use product 2</div>
                </q-card-section>

                <q-card-section class="q-pt-none">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                    eiusmod tempor incididunt ut labore et dolore magna aliqua.
                </q-card-section>
                </q-card>
            </div>
            <div class="q-pa-md">
                <q-card class="my-card">
                <q-video
                    frameborder="0"
                    allowfullscreen
                    :ratio="16/9"
                    src="https://www.youtube.com/embed/l0NOhQj1m3s"
                />

                <q-card-section>
                    <div class="text-h6">Lesson 3</div>
                    <div class="text-subtitle2">How to use product 3</div>
                </q-card-section>

                <q-card-section class="q-pt-none">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                    eiusmod tempor incididunt ut labore et dolore magna aliqua.
                </q-card-section>
                </q-card>
            </div>
        </div>
    </q-page>
</template>
<style lang="sass" scoped>
    .my-card
        width: 100%
        max-width: 300px
</style>
