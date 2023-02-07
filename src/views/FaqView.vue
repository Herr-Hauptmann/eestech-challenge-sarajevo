<script setup>
import 'flowbite'
</script>

<template>
    <div class="container mx-auto my-12">

        <div id="accordion-collapse" data-accordion="collapse">
            <h2 id="accordion-collapse-heading-1">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 rounded-t-xl focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-800 dark:border-gray-700 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800"
                    data-accordion-target="#accordion-collapse-body-1" aria-expanded="true"
                    aria-controls="accordion-collapse-body-1">
                    <span>1. Binding agreement</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-1" class="hidden" aria-labelledby="accordion-collapse-heading-1">
                <div class="p-5 font-light border border-b-0 border-gray-200 ">
                    <p class="mb-2 text-gray-500 ">To enter the competition, you must agree to these
                        Terms and Conditions ("Terms"). Therefore, please read these Terms before entry to ensure you
                        understand and agree. You agree that the submission of an entry in the EESTech Challenge
                        constitutes agreement to these Terms. These Terms form a binding legal agreement between you,
                        hereafter referred to as "the contestant", and Electrical Engineering STudents' European
                        assoCiation ("EESTEC"),concerning the EESTech Challenge.</p>
                </div>
            </div>


            <h2 id="accordion-collapse-heading-2">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 focus:ring-4 focus:ring-gray-200 hover:bg-gray-100"
                    data-accordion-target="#accordion-collapse-body-2" aria-expanded="true"
                    aria-controls="accordion-collapse-body-2">
                    <span>2. Eligibility</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-2" class="hidden" aria-labelledby="accordion-collapse-heading-1">
                <div class="p-5 font-light border border-b-0 border-gray-200">
                    <ul>
                        <li class="mb-2 text-gray-500">The participation is open and free of registration to individuals
                            who are between 18 and 26 years.</li>
                        <li class="mb-2 text-gray-500">The competition is void where prohibited by law.</li>
                        <li class="mb-2 text-gray-500">The following individuals are not eligible to participate in this
                            Challenge:</li>
                    </ul>
                    <ol>
                        <li class="mb-2 text-gray-500">1. Challenge entities, in detail:</li>
                        <p class="mb-2 text-gray-500">(i) Current EESTech Challenge local and international board
                            members.</p>
                        <p class="mb-2 text-gray-500">(ii) Current board members of EESTEC branches.</p>
                        <p class="mb-2 text-gray-500">(iii) Current members of EESTEC branches that are responsible for
                            overseeing the work of local boards.</p>
                        <p class="mb-2 text-gray-500">(iv) Current EESTEC Board members.</p>
                        <p class="mb-2 text-gray-500">(v) Current EESTEC Supervisory Board members.</p>
                        <p class="mb-2 text-gray-500">(vi) Current technical consultants and academic partners of the
                            EESTech Challenge.</p>
                    </ol>
                    <ol>
                        <li class="mb-2 text-gray-500">2. Current employees, interns, contractors, and official
                            office-holders of the corporate sponsors of EESTech Challenge.</li>
                    </ol>
                    <p class="mb-2 text-gray-500">EESTEC, reserves the right to verify eligibility and to adjudicate on
                        any dispute, at any time.</p>
                    <p class="mb-2 text-gray-500">All communications between EESTech Challenge and contestants,
                        including but not limited to the EESTech Challenge website content and email communications,
                        will be in English, except for the Local Rounds which will be conducted in the native language.
                    </p>
                </div>
            </div>


            <h2 id="accordion-collapse-heading-3">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-800 dark:border-gray-700 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800"
                    data-accordion-target="#accordion-collapse-body-3" aria-expanded="true"
                    aria-controls="accordion-collapse-body-3">
                    <span>3. How to enter</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-3" class="hidden" aria-labelledby="accordion-collapse-heading-3">
                <div class="p-5 font-light border border-b-0 border-gray-200">
                    <p class="mb-2 text-gray-500 ">All contestants must register and provide the required personal
                        information at the competition website located at <a class="text-blue-500"
                            href="https://eestechchallenge.eestec.net">eestechchallenge.eestec.net</a> or at <a
                            href=" https://challenge.eestec-sa.ba">challenge.eestec-sa.ba</a> (for Sarajevo region).
                    </p>
                    <p class="mb-2 text-gray-500 ">As a part of the registration, the contestants will be required to
                        provide information about themselves such as their names and email addresses.
                    </p>
                </div>
            </div>



            <h2 id="accordion-collapse-heading-4">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-800 dark:border-gray-700 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800"
                    data-accordion-target="#accordion-collapse-body-4" aria-expanded="true"
                    aria-controls="accordion-collapse-body-4">
                    <span>4. Conditions of participation</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-4" class="hidden" aria-labelledby="accordion-collapse-heading-4">
                <div class="p-5 font-light border border-b-0 border-gray-200">
                    <p class="mb-2 text-gray-500">The contestant's participation in this competition means that the
                        contestant agrees to be bound by these Terms and by the decisions of EESTEC, which are final and
                        binding on all matters relating to this competition.</p>
                    <p class="mb-2 text-gray-500">The contestant agrees that EESTEC shall have a perpetual, irrevocable,
                        worldwide, royalty-free right to use, copy, distribute, modify and make publicly available the
                        task, solution, submission in connection with the operation, conduct, administration,
                        advertising and promotion of the competition.</p>
                    <p class="mb-2 text-gray-500">The contestants of the Final Round agree that the intellectual
                        property (industrial property rights and copyrights) of the task solutions, created as part of
                        the competition, belongs to the task creator unless the task creator explicitly renounces the
                        appropriation towards the contestants. If the task creator renounces the appropriation, the
                        intellectual property remains with the contestants.</p>
                    <p class="mb-2 text-gray-500">Prizes are awarded without warranty of any kind from EESTEC.</p>
                </div>
            </div>




            <h2 id="accordion-collapse-heading-5">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-800 dark:border-gray-700 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800"
                    data-accordion-target="#accordion-collapse-body-5" aria-expanded="true"
                    aria-controls="accordion-collapse-body-5">
                    <span>5. Travel and expenses</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-5" class="hidden" aria-labelledby="accordion-collapse-heading-5">
                <div class="p-5 font-light border border-b-0 border-gray-200">
                    <p class="mb-2 text-gray-500">Winners are encouraged, but not obliged to be present in the Final
                        Round. EESTEC does not guarantee any cost coverage or refunds of travel, food, or accommodation
                        expenses.</p>
                </div>
            </div>


            <h2 id="accordion-collapse-heading-6">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-800 dark:border-gray-700 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800"
                    data-accordion-target="#accordion-collapse-body-6" aria-expanded="true"
                    aria-controls="accordion-collapse-body-6">
                    <span>6. Privacy</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-6" class="hidden" aria-labelledby="accordion-collapse-heading-6">
                <div class="p-5 font-light border border-b-0 border-gray-200">
                    <p class="mb-2 text-gray-500">The contestant acknowledges and agrees that EESTEC may collect, store,
                        share and otherwise use personally identifiable information provided during the registration
                        process and the competition, including but not limited to full name, address, phone number,
                        email address, and curriculum vitae. Therefore EESTEC can use this information, not only for
                        administering the EESTech Challenge and verifying the contestant's identity and telephone number
                        in case the contestant qualifies for a prize but also for recruiting purposes by the EESTech
                        Challenge's corporate partners or sponsors.</p>
                    <p class="mb-2 text-gray-500">The contestant's information may also be transferred to countries
                        outside his/her residence. Such other countries may not have privacy laws and regulations
                        similar to those of the contestant's country of residence.</p>
                    <p class="mb-2 text-gray-500">If the contestant does not provide the mandatory data required at
                        registration, EESTEC reserves the right to disqualify the entry.</p>
                    <p class="mb-2 text-gray-500">The contestant has the right to request access, review, rectify or
                        delete any personal data held by EESTEC, in connection with the EESTech Challenge, by writing to
                        this email address: eestech-challenge@eestec.net</p>
                    <p class="mb-2 text-gray-500">The contestant agrees to be photographed/filmed/recorded on behalf of
                        EESTEC and its corporate partners or sponsors. The contestant grants EESTEC and its corporate
                        partners or sponsors a transferable, sub-licensable, royalty-free, worldwide license to host,
                        use, distribute, modify, run, copy, publicly perform or display, translate, and create
                        derivative works of any images/videos/recordings. The images/videos/recordings may be used in
                        both printed and digital form, for a maximum of 15 years. The images/videos/recordings may be
                        stored in the EESTech Challenge's image and media data bank, which is available to the EESTech
                        Challenge and the Board of EESTEC. EESTEC and its partners are allowed to use these pictures
                        freely, including but not limited to promotional purposes and grant applications.</p>
                    <p class="mb-2 text-gray-500">If the contestant wants EESTEC and its corporate partners or sponsors
                        to restrain them from using the images/videos/recordings in new material, the contestant should
                        contact eestech-challenge@eestec.net. EESTEC and the EESTech Challenge will then no longer use
                        the contestant's data in new material. The contestant will also be removed from already
                        published material wherever possible. </p>
                    <p class="mb-2 text-gray-500">To request information on how the contestant's data is used or if the
                        contestant feels that his/her data have been used in a way that violates the agreement or
                        current legislation, please contact eestech-challenge@eestec.net.</p>
                </div>
            </div>


            <h2 id="accordion-collapse-heading-7">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-b-0 border-gray-200 focus:ring-4 focus:ring-gray-200 dark:focus:ring-gray-800 dark:border-gray-700 dark:text-gray-400 hover:bg-gray-100 dark:hover:bg-gray-800"
                    data-accordion-target="#accordion-collapse-body-7" aria-expanded="true"
                    aria-controls="accordion-collapse-body-7">
                    <span>7. Elimination</span>
                    <svg data-accordion-icon class="w-6 h-6 rotate-180 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-7" class="hidden" aria-labelledby="accordion-collapse-heading-7">
                <div class="p-5 font-light border border-b-0 border-gray-200">
                    <p class="mb-2 text-gray-500">The contestant may be prohibited from participating in EESTech
                        Challenge if in EESTEC's sole discretion, EESTEC reasonably believes that the contestant has
                        attempted to undermine the legitimate operation of the competition by:</p>
                    <ol>
                        <li class="mb-2 text-gray-500">Providing false information concerning his/her identity and other
                            personal data;</li>
                        <li class="mb-2 text-gray-500">Breaching any of the provisions outlined in these Terms;</li>
                        <li class="mb-2 text-gray-500">Threatening, harassing or interfering with the ability of other
                            contestants to effectively participate in the EESTech Challenge;</li>
                        <li class="mb-2 text-gray-500">Threatening, harassing or interfering with EESTech Challenge
                            organizers or other EESTEC members;</li>
                    </ol>
                    <p class="mb-2 text-gray-500">EESTEC further reserves the right to disqualify any submission that it
                        believes in its sole and unfettered discretion, infringes upon or violates the rights of any
                        third party or otherwise does not comply with these Terms.</p>
                    <p class="mb-2 text-gray-500">Claims or concerns about suspicious activity or cheating in any Round,
                        must be delivered to the EESTech Challenge administrator within seven (7) days, after the end of
                        that Round. If EESTEC suspects cheating or violation of the Terms by any contestant, EESTEC will
                        in its sole discretion, research such claims and take the appropriate action. All decisions of
                        EESTEC on these matters are final and binding.</p>
                </div>
            </div>


            <h2 id="accordion-collapse-heading-8">
                <button type="button"
                    class="flex items-center justify-between w-full p-5 font-medium text-left text-gray-500 border border-gray-200 focus:ring-4 focus:ring-gray-200 hover:bg-gray-100"
                    data-accordion-target="#accordion-collapse-body-8" aria-expanded="false"
                    aria-controls="accordion-collapse-body-8">
                    <span>8. Not an offer or contract of employement</span>
                    <svg data-accordion-icon class="w-6 h-6 shrink-0" fill="currentColor" viewBox="0 0 20 20"
                        xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd"
                            d="M5.293 7.293a1 1 0 011.414 0L10 10.586l3.293-3.293a1 1 0 111.414 1.414l-4 4a1 1 0 01-1.414 0l-4-4a1 1 0 010-1.414z"
                            clip-rule="evenodd"></path>
                    </svg>
                </button>
            </h2>
            <div id="accordion-collapse-body-8" class="hidden" aria-labelledby="accordion-collapse-heading-8">
                <div class="p-5 font-light border border-t-0 border-gray-200 dark:border-gray-700">
                    <p class="mb-2 text-gray-500 dark:text-gray-400">Under no circumstances shall the submission of an
                        entry into the EESTech Challenge or anything in these Terms, be construed as an offer or
                        contract of employment with EESTEC or any of the sponsors of the EESTech Challenge. You
                        acknowledge that you have submitted your entry voluntarily and not in confidence or trust. You
                        acknowledge that no confidential, fiduciary, agency or other relationship or implied-in-fact
                        contract now exists between you and EESTEC and that no such relationship is established by your
                        submission of an entry under these Terms.</p>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>