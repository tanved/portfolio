<template>
    <section id="projects" class="container mx-auto">
        <div class="flex flex-col justify-center">
            <h1 class="text-center text-4xl font-bold text-red-400 mt-4 mb-8 md:mb-12">
                Designer, Frontend Developer & Mentor
            </h1>
            <p class="text-center text-4xl font-bold text-red-400 mt-4 mb-8 md:mb-12">
                I design and code beautifully simple things, and I love what I do.
            </p>
            <div class="inline-block text-center mx-auto my-auto">
                <div class="">
                    <img alt="hero image" width="300" height="300" src="~/assets/img/hero.png">
                </div>
            </div>
         </div>
         <div class=" exampleClass inline-block">
                <span class="">Pusing</span>
         </div>
        

    </section>
</template>

<style>

.exampleClass {
    padding: 12px 24px;
    background-color: white;
    border-radius: 6px;
    position: relative;
    overflow: hidden;
}

.exampleClass span {
    color: black;
    position: relative;
    z-index: 1;
    transition: color 0.6s cubic-bezier(0.53, 0.21, 0, 1);
}

.exampleClass::before {
    content: '';
    position: absolute;
    top: 50%;
    left: 0;
    border-radius: 6px;
    transform: translate(-100%, -50%);
    width: 100%;
    height: 100%;
    background-color: hsl(244, 63%, 69%);
    transition: transform 0.6s cubic-bezier(0.53, 0.21, 0, 1);
}

.exampleClass:hover span {
    color: white;
}

.exampleClass:hover::before {
    transform: translate(0, -50%);
}

</style>