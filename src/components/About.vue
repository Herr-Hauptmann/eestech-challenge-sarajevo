<script setup>
import Card from '../components/Card.vue'

let titles = [
    "Topic",
    "Teams",
    "Rounds",
]

let descriptions = [
    "This year, the topic is Mobile App Development: Gamification. Before the beginning of the competition, the organising teams of EESTech Challenge Project are preparing educational materials that increase students' awareness and knowledge in the selected topic.",
    "Each competing team consists of three members that have the opportunity to gain practical knowledge about a technological topic that is chosen annually.",
    "The competition is structured into two rounds: <br /> 1) The Local Rounds - Local hackathons that are organized by EESTEC branches in different European cities. <br /> 2) The Final Round - The winners of Local Rounds have the opportunity to come together and compete.",
]
</script>

<template>
    <div class="container mx-auto mt-12">
        <h2 class="text-center text-5xl text-eestech-2">About EESTech Challenge</h2>
        <p class="my-3 text-center text-lg">EESTech Challenge (EESTEC Technology Challenge) is the students' international competition organized by EESTEC. It aims to create opportunities for European students to gain knowledge in the field of Electrical Engineering and Computer Science (EECS) and develop professional networks.</p>
        <div class="grid grid-cols-3 gap-2 my-9">
            <div>
                <card :heading="titles[0]" :content="descriptions[0]">
                    <div class="flex justify-center">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12 white">
                            <path d="M12 .75a8.25 8.25 0 00-4.135 15.39c.686.398 1.115 1.008 1.134 1.623a.75.75 0 00.577.706c.352.083.71.148 1.074.195.323.041.6-.218.6-.544v-4.661a6.714 6.714 0 01-.937-.171.75.75 0 11.374-1.453 5.261 5.261 0 002.626 0 .75.75 0 11.374 1.452 6.712 6.712 0 01-.937.172v4.66c0 .327.277.586.6.545.364-.047.722-.112 1.074-.195a.75.75 0 00.577-.706c.02-.615.448-1.225 1.134-1.623A8.25 8.25 0 0012 .75z" />
                            <path fill-rule="evenodd" d="M9.013 19.9a.75.75 0 01.877-.597 11.319 11.319 0 004.22 0 .75.75 0 11.28 1.473 12.819 12.819 0 01-4.78 0 .75.75 0 01-.597-.876zM9.754 22.344a.75.75 0 01.824-.668 13.682 13.682 0 002.844 0 .75.75 0 11.156 1.492 15.156 15.156 0 01-3.156 0 .75.75 0 01-.668-.824z" clip-rule="evenodd" />
                          </svg>
                    </div>
                </card>
            </div>
            <div>
                <card :heading="titles[1]" :content="descriptions[1]">
                    <div class="flex justify-center align-center">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12 white">
                            <path d="M4.5 6.375a4.125 4.125 0 118.25 0 4.125 4.125 0 01-8.25 0zM14.25 8.625a3.375 3.375 0 116.75 0 3.375 3.375 0 01-6.75 0zM1.5 19.125a7.125 7.125 0 0114.25 0v.003l-.001.119a.75.75 0 01-.363.63 13.067 13.067 0 01-6.761 1.873c-2.472 0-4.786-.684-6.76-1.873a.75.75 0 01-.364-.63l-.001-.122zM17.25 19.128l-.001.144a2.25 2.25 0 01-.233.96 10.088 10.088 0 005.06-1.01.75.75 0 00.42-.643 4.875 4.875 0 00-6.957-4.611 8.586 8.586 0 011.71 5.157v.003z" />
                          </svg>                          
                    </div>
                </card>
            </div>
            <div>
                <card :heading="titles[2]" :content="descriptions[2]">
                    <div class="flex justify-center items-center">
                        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="currentColor" class="w-12 h-12 white">
                            <path fill-rule="evenodd" d="M9.315 7.584C12.195 3.883 16.695 1.5 21.75 1.5a.75.75 0 01.75.75c0 5.056-2.383 9.555-6.084 12.436A6.75 6.75 0 019.75 22.5a.75.75 0 01-.75-.75v-4.131A15.838 15.838 0 016.382 15H2.25a.75.75 0 01-.75-.75 6.75 6.75 0 017.815-6.666zM15 6.75a2.25 2.25 0 100 4.5 2.25 2.25 0 000-4.5z" clip-rule="evenodd" />
                            <path d="M5.26 17.242a.75.75 0 10-.897-1.203 5.243 5.243 0 00-2.05 5.022.75.75 0 00.625.627 5.243 5.243 0 005.022-2.051.75.75 0 10-1.202-.897 3.744 3.744 0 01-3.008 1.51c0-1.23.592-2.323 1.51-3.008z" />
                          </svg>
                          
                    </div>
                </card>
            </div>
        </div>
    </div>

</template>

<style scoped>
.white{
    color:white;
}
</style>