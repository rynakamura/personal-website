<template>
    <!--article v-if="props.project">
        <aside class="mx-auto relative z-10 max-h-80 w-fit">
            <div
                class="relative z-10 max-h-80 w-fit mx-3.5 shadow-lg bg-gradient-to-br from-purple-400 to-red-300 shadow-3xl overflow-hidden">
                <video v-if="props.project.video" autoplay loop muted controls playsinline src={props.project.video}
                    class="max-h-[inherit] w-auto p-2 sm:p-3 cursor-pointer img-container" />
                <img loading="lazy" src={props.project.image}
                    class="max-h-[inherit] w-auto p-2 sm:p-3 cursor-pointer img-container"
                    :alt="'Screenshot of ' + props.project.name" />
            </div>
        </aside>

        <section class="-mt-5 px-5 pt-10 pb-5 bg-gray-50 dark:bg-gray-900 shadow-xl rounded-sm" style="height: fit-content">
            <h1 data-aos="flip-down" class="font-extrabold text-2xl lg:text-3xl text-gray-800 dark:text-gray-50 mb-1">
                {{ props.project.name }}
                <time class="ml-0.5 font-light text-right text-xl lg:text-2xl dark:text-gray-300">{{ props.project.year }}</time>
            </h1>
            <p data-aos="fade-up" data-aos-delay="100"
                class="font-bold font-mono text-sm text-blue-500 dark:text-blue-300 mb-3">
                {{ props.project.collaborators }}
            </p>

            <hr data-aos="fade-up" data-aos-delay="150" class="mb-4 border-gray-400 dark:border-gray-500" />
            <p data-aos="fade-up" data-aos-delay="200"
                class="mb-4 text-gray-700 dark:text-gray-300 leading-relaxed font-semibold">
                {{props.project.description}}
            </p>

            <div data-aos="fade-up" data-aos-delay="300" class="text-sm font-mono font-semibold flex flex-wrap gap-2 mb-6">
                <a v-for="tech in props.project.technologies" href={techLinks.get(tech)} target="_blank"
                    class="bg-green-200 text-green-900 px-2">{tech}</a>
            </div>

            <div data-aos="flip-up" data-aos-delay="400" class="flex items-center justify-end"
                v-if="props.project.github || props.project.website">
                <a href={props.project.github} target="_blank" v-if="props.project.github"
                    class="px-3 py-1.5 transition-colors flex items-center bg-gray-200 hover:bg-gray-300 dark:bg-gray-700 hover:dark:bg-gray-600 text-gray-500 dark:text-gray-50">
                    <p class="">Github</p>
                    <i class="fab fa-github ml-3 text-lg" />
                </a>
                <a href={props.project.website} target="_blank" v-else
                    class="flex items-center hover:underline text-gray-800 dark:text-gray-50 ml-6">
                    <p class="">Link</p>
                    <i class="fas fa-external-link-alt ml-3 text-md" />
                </a>
            </div>
        </section>
    </article-->
            <p data-aos="fade-up" data-aos-delay="200"
                class="mb-4 text-gray-700 dark:text-gray-300 leading-relaxed font-semibold">
                webdev
            </p>
</template>

<script setup>
/*const props = defineProps({
  project: {
    type: Object,
    required: true,
  },
});
console.log(props.project)*/
</script>
