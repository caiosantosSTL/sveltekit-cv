<script>
    var clicked = true
    function closeTab(){
        if (clicked) {
            document.querySelector('#mobile-menu').classList.remove('block')
            document.querySelector('#mobile-menu').classList.add('hidden')
            clicked = !clicked
        }else{
            document.querySelector('#mobile-menu').classList.remove('hidden')
            document.querySelector('#mobile-menu').classList.add('block')
            clicked = !clicked
        }
    }
</script>

<main>

    <nav class="bg-black border-red-600 px-2 sm:px-4 py-2.5 rounded dark:bg-gray-800">
        <div class="container flex flex-wrap justify-between items-center mx-auto">
            <a href="/" class="flex">
                <i class="bi bi-person-bounding-box text-2xl text-white"></i>
                <span class="hidden self-center text-lg font-semibold whitespace-nowrap dark:text-white">FlowBite</span>
            </a>
            <!-- button open and close on mobile size div-->
            <button data-collapse-toggle="mobile-menu" type="button"
                class="inline-flex items-center p-2 ml-3 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600"
                aria-controls="mobile-menu-2" aria-expanded="false">
                <span class="sr-only">Open main menu</span>
                <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd"
                        d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
                        clip-rule="evenodd"></path>
                </svg>
                <svg class="hidden w-6 h-6" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd"
                        d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z"
                        clip-rule="evenodd"></path>
                </svg>
            </button>

            <!--mobile hidden that div mobile-menu-->
            <div class="hidden w-full md:block md:w-auto" id="mobile-menu">
                <!--flex-col // mobile size, flex-row // md size-->
                <ul class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium">
                    <li on:click={closeTab}>
                        <a href="#home" 
                            class="block py-2 pr-4 pl-3 text-gray-50 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white"
                            aria-current="page">Home</a>
                    </li>
                    <li on:click={closeTab}>
                        <a href="#profile-edu" 
                            class="block py-2 pr-4 pl-3 text-gray-50 border-b border-gray-100 hover:bg-gray-800  md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Profile and Education</a>
                    </li>
                    <li on:click={closeTab}>
                        <a href="#employment"
                            class="block py-2 pr-4 pl-3 text-gray-50 border-b border-gray-100 hover:bg-gray-800  md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Employment History</a>
                    </li>
                    <li on:click={closeTab}>
                        <a href="#skills" 
                            class="block py-2 pr-4 pl-3 text-gray-50 border-b border-gray-100 hover:bg-gray-800 md:hover:bg-transparent md:border-0 md:hover:text-blue-700 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Skills</a>
                    </li>
                </ul>
            </div>
        </div>
    </nav>



</main>