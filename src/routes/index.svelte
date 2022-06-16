<script>
    import HeroNoImg from "../components/hero-no-img.svelte";
    import HeroImgLeft from "../components/hero-img-left.svelte";
    import HeroImgTop from "../components/hero-img-top.svelte";
    </script>

    <!-- Hero Section -->
    <section class="p-8 bg-white">
        <h1 class="text-6xl text-red-500 py-4">Welcome to Soda UI</h1>
        <h2 class="text-4xl my-4">An Open Source UI component library built on Svelte and TailwindCSS.</h2>
        <p class="my-8">Soda UI is a Svelte JS and Tailwind CSS UI library. It was created by <a class="text-red-500" href="https://brijr.dev">Bridger Tower</a> and <a class="text-red-500" href="https://cameronyoungblood.dev">Cameron Youngblood</a> in 2022. Updated regularly.</p>
    </section> 

    <!-- Components Start -->

    <!-- Hero Components -->
    <h2 class="text-4xl m-8 mt-12">Hero Section Components</h2>
    <div class="bg-slate-700 h-px m-8"></div>

    <h3 class="text-2xl mx-8 mt-12">Hero Section with no Image</h3>
    <div class="drop-shadow-md bg-white mx-8 my-4 rounded-xl">
        <!-- Fake Browser Head Section -->
        <div class="w-full h-12 bg-slate-200 rounded-t-xl text-right flex justify-between">
            <div class="flex items-center w-1/2 h-8 p-3 bg-slate-100 rounded-lg text-left my-auto ml-2">
                <p class="text-slate-400">https://sodaui.dev</p>
            </div>
            <svg class="m-4" xmlns="http://www.w3.org/2000/svg" height="1rem" viewBox="0 0 329.26933 329"><path d="m194.800781 164.769531 128.210938-128.214843c8.34375-8.339844 8.34375-21.824219 0-30.164063-8.339844-8.339844-21.824219-8.339844-30.164063 0l-128.214844 128.214844-128.210937-128.214844c-8.34375-8.339844-21.824219-8.339844-30.164063 0-8.34375 8.339844-8.34375 21.824219 0 30.164063l128.210938 128.214843-128.210938 128.214844c-8.34375 8.339844-8.34375 21.824219 0 30.164063 4.15625 4.160156 9.621094 6.25 15.082032 6.25 5.460937 0 10.921875-2.089844 15.082031-6.25l128.210937-128.214844 128.214844 128.214844c4.160156 4.160156 9.621094 6.25 15.082032 6.25 5.460937 0 10.921874-2.089844 15.082031-6.25 8.34375-8.339844 8.34375-21.824219 0-30.164063zm0 0"/></svg>
        </div>
        <!-- UI Component Goes here -->
        <HeroNoImg/>
    </div>
    
    <h3 class="text-2xl mx-8 mt-12">Hero Section with Left Image</h3>
    <div class="drop-shadow-md bg-white mx-8 my-4 rounded-xl">
        <!-- Fake Browser Head Section -->
        <div class="w-full h-12 bg-slate-200 rounded-t-xl text-right flex justify-between">
            <div class="flex items-center w-1/2 h-8 p-3 bg-slate-100 rounded-lg text-left my-auto ml-2">
                <p class="text-slate-400">https://sodaui.dev</p>
            </div>
            <svg class="m-4" xmlns="http://www.w3.org/2000/svg" height="1rem" viewBox="0 0 329.26933 329"><path d="m194.800781 164.769531 128.210938-128.214843c8.34375-8.339844 8.34375-21.824219 0-30.164063-8.339844-8.339844-21.824219-8.339844-30.164063 0l-128.214844 128.214844-128.210937-128.214844c-8.34375-8.339844-21.824219-8.339844-30.164063 0-8.34375 8.339844-8.34375 21.824219 0 30.164063l128.210938 128.214843-128.210938 128.214844c-8.34375 8.339844-8.34375 21.824219 0 30.164063 4.15625 4.160156 9.621094 6.25 15.082032 6.25 5.460937 0 10.921875-2.089844 15.082031-6.25l128.210937-128.214844 128.214844 128.214844c4.160156 4.160156 9.621094 6.25 15.082032 6.25 5.460937 0 10.921874-2.089844 15.082031-6.25 8.34375-8.339844 8.34375-21.824219 0-30.164063zm0 0"/></svg>
        </div>
        <!-- UI Component Goes here -->
        <HeroImgLeft/>
    </div>
    
    <h3 class="text-2xl mx-8 mt-12">Hero Section with Right Image</h3>
    <div class="drop-shadow-md bg-white mx-8 my-4 rounded-xl">
        <!-- Fake Browser Head Section -->
        <div class="w-full h-12 bg-slate-200 rounded-t-xl text-right flex justify-between">
            <div class="flex items-center w-1/2 h-8 p-3 bg-slate-100 rounded-lg text-left my-auto ml-2">
                <p class="text-slate-400">https://sodaui.dev</p>
            </div>
            <svg class="m-4" xmlns="http://www.w3.org/2000/svg" height="1rem" viewBox="0 0 329.26933 329"><path d="m194.800781 164.769531 128.210938-128.214843c8.34375-8.339844 8.34375-21.824219 0-30.164063-8.339844-8.339844-21.824219-8.339844-30.164063 0l-128.214844 128.214844-128.210937-128.214844c-8.34375-8.339844-21.824219-8.339844-30.164063 0-8.34375 8.339844-8.34375 21.824219 0 30.164063l128.210938 128.214843-128.210938 128.214844c-8.34375 8.339844-8.34375 21.824219 0 30.164063 4.15625 4.160156 9.621094 6.25 15.082032 6.25 5.460937 0 10.921875-2.089844 15.082031-6.25l128.210937-128.214844 128.214844 128.214844c4.160156 4.160156 9.621094 6.25 15.082032 6.25 5.460937 0 10.921874-2.089844 15.082031-6.25 8.34375-8.339844 8.34375-21.824219 0-30.164063zm0 0"/></svg>
        </div>
        <!-- UI Component Goes here -->
        <HeroImgTop/>
    </div>