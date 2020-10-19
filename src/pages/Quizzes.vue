<template>
    <q-page class="q-pa-md row justify-center">
        <div class="q-pa-md items-start q-gutter-md text-h1">
            This is the Quizzes page
        </div>
        <div class="row">
            <div class="q-pa-md">
                <q-card class="my-card">
                    <q-card-section>
                        <div class="text-h6">Quiz 1</div>
                        <div class="text-subtitle2">Product 1</div>
                        <q-banner inline-actions rounded class="bg-green text-white">
                            <q-icon name="grade" size="md"/>
                            Pass
                        </q-banner>
                    </q-card-section>

                    <q-separator />

                    <q-card-actions vertical>
                        <q-btn label="Show Results" color="primary" />
                        <q-btn label="Retry" color="primary" />
                    </q-card-actions>
                </q-card>
            </div>
            <div class="q-pa-md">
                <q-card class="my-card">
                    <q-card-section>
                        <div class="text-h6">Quiz 2</div>
                        <div class="text-subtitle2">Product 2</div>
                        <q-banner inline-actions rounded class="bg-orange text-white">
                            <q-icon name="assessment" size="md"/>
                            Yet to do
                        </q-banner>
                    </q-card-section>

                    <q-separator />

                    <q-card-actions vertical>
                        <q-btn label="Show Results" color="primary" />
                        <q-btn label="Retry" color="primary" />
                    </q-card-actions>
                </q-card>
            </div>
            <div class="q-pa-md">
                <q-card class="my-card">
                    <q-card-section>
                        <div class="text-h6">Quiz 3</div>
                        <div class="text-subtitle2">Product 3</div>
                        <q-banner inline-actions rounded class="bg-red text-white">
                            <q-icon name="warning" size="md"/>
                            Fail
                        </q-banner>
                    </q-card-section>

                    <q-separator />

                    <q-card-actions vertical>
                        <q-btn label="Show Results" color="primary" />
                        <q-btn label="Retry" color="primary" />
                    </q-card-actions>
                </q-card>
            </div>
        </div>
    </q-page>
</template>
<style lang="sass" scoped>
    .my-card
        width: 100px
        max-width: 300px
        min-width: 300px
</style>
