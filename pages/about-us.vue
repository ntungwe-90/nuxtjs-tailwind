<template>
    <div>
    <div class="mt-6 text-center">
        <div class="container">
            <h2 class="text-primary-700 text-4xl font-extrabold leading-10 text-primary mt-8 mb-2
             mx-auto">We are delighted you are thinking <br> of joining us!</h2>
        </div>
        <div>

            <p class="text-sm font-normal leading-7 mb-6">We live and breathe technology digital focused
                creatives building unique and <br>
                engaging experiences so that brands can transform the future.
                Join our small <br>and mighty digit design team.</p>
        </div>

        <img src="../static/images/🦆 illustration _blogging blog computer desk laptop work office_.png" class="mx-auto"
            alt="about-image" />

        <!-- <NuxtLink to="/">Home page</NuxtLink> works like the anchor tag -->
        <button @click="findJob()" type="button"
            class="text-white bg-primary hover:bg-red-300  focus:outline-none rounded-full font-medium  text-sm px-5 py-2.5 text-center mr-2 mt-6">View
            Opportunities</button>


        <div class="flex flex-col space-y-5 ">
            <h2 class="text-primary-700 text-4xl font-extrabold leading-10 text-primary mt-8 mb-2
             mx-auto">Life at Walulel</h2>

            <ul class=" flex-none max-w-4xl font-normal text-lg leading-5 list-disc mx-auto">
                <li class="mb-5"> We tame data to inform the world about the quality of the locations that are our
                    communities we
                    chose to live work and play in.</li>


                <li class="mb-5">
                    We harness the power of location attributes to bring communities and estates and together in the
                    digital
                    sphere to create networked buildings.
                </li>
                <li class="mb-5 ">
                    We champion locals by minimising the distance between consumers and producers of real estate
                    services.
                </li>
                <li class="mb-5">We empower artisans to serve their neighbourhoods, safely and securely.</li>
            </ul>
            <h2 class="text-primary-700 text-4xl font-extrabold leading-10 text-primary mt-8 mb-2
             mx-auto">About Us</h2>
             <div class="font-normal text-lg mx-w-4xl">
            <p class="mb-3">
                Walulel was born in 2017 out of the realisation that meaningful information about one’s neighbourhood
                and (existing or prospective) property was disparate at best and in most cases unavailable. This applied
                to renters and purchasers who had the means to access premium analysis in relation to any other asset
                they wished to purchase.</p>

            <p> With average property prices and rents soaring at the time, and with this being unlikely to change in
                the near future, Walulel’s founders could see an ever-widening gulf between equity of information,
                meaning that urbanites in London, Accra, and in turn other city dwellers, would continue to part with
                money to live in properties and neighbourhoods based mainly on anecdotes, some partial information about
                historical price movements in the area, and distance to local infrastructure. We considered that this
                could at times yield positive outcomes for urbanites by chance, but on many occasions might lead to them
                not finding the best value neighbourhood for their particular wants and needs.
            </p>
        </div>
        </div>
        
    </div>
   
    </div>
</template>
<script>
export default {
    // this method is good when reading from api
    methods: {
        findJob() {
            this.$router.push('/find-job');
        }
    }
}
</script>