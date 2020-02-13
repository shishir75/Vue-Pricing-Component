<template>
    <div class="flex justify-center">
        <div class="w-1/2 bg-blue-900 rounded-lg shadow px-6 py-12 flex flex-col items-center">
            <div class="bg-gray-400 rounded-full flex justify-around p-1">
                <button class="rounded-full text-xs font-bold px-6 py-1 uppercase focus:outline-none bg-blue-600 text-gray-200">Starter</button>
                <button class="rounded-full text-xs font-bold px-6 py-1 uppercase focus:outline-none">Pro</button>
            </div>

            <div class="flex w-full pt-8">
                <div class="text-white w-1/2">
                    <h1 class="text-2xl font-bold">Starter</h1>
                    <ul class="pt-4">
                        <li>Benefit 1</li>
                        <li>Benefit 2</li>
                        <li>Benefit 3</li>
                        <li>Benefit 4</li>
                    </ul>
                    <div class="flex justify-center pt-8">
                        <div class="text-4xl font-bold">$99</div>
                        <div class="pl-1 pt-2 text-gray-300">/mo</div>
                    </div>
                </div>

                <div class="text-white w-1/2">
                    <h1 class="text-2xl font-bold">Starter</h1>
                    <ul class="pt-4">
                        <li>Benefit 1</li>
                        <li>Benefit 2</li>
                        <li>Benefit 3</li>
                        <li>Benefit 4</li>
                    </ul>
                    <div class="flex justify-center pt-8">
                        <div class="text-4xl font-bold">$199</div>
                        <div class="pl-1 pt-2 text-gray-300">/mo</div>
                    </div>
                </div>

            </div>


        </div>
    </div>
</template>

<script>
    export default {
        name: "Pricing"
    }
</script>

<style scoped>

</style>
