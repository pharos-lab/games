<template>
    <main class="flex justify-center">
        
        <section class="board mt-12 bg-slate-200">
            <div class="mastermind-grid divide-slate-300 divide-y">
                <div class="row" v-for="n in 10">
                    <div class="combination flex gap-4 p-2">
                        <div class="size-7 rounded-full border bg-white" v-for="n in 4"></div>
                    </div>
                    <div class="result">

                    </div>
                </div>
            </div>
            
            <div class="mastermind-choice">
                
            </div>
        </section>
    </main>
</template>