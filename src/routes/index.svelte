<script>
    import Navbar from '../component/navbar.svelte'
    import Footer from '../component/footer.svelte'
    //comp
    import Card from '../component/mycard.svelte'
    import Popover from '../component/dropdown.svelte'

</script>

<main>

    <section class="sticky top-0 z-50 ">
        <!--navbar-->

        <Navbar />



    </section>

    <div class="h-20" id="home"></div>
    <!--space-->

    <section>
        <div class="container mx-auto">

            <!--part 1-->
            <div class="grid grid-cols-1  gap-2 my-2">
                <div class="p-10 bg-black flex justify-center flex-wrap rounded-3xl">
                    <div class="flex flex-col ">
                        <div class="flex justify-center transition ease-in-out delay-250 hover:-translate-y-2">
                            <img src="../img/piccaio3.jpeg" class="rounded-full scale-75 object-contain w-40 " alt="">
                        </div>

                        <h1 class="text-4xl flex justify-center text-white text-center">Caio Santos da Silva</h1>
                        <div class="flex justify-center">
                            <p class="text-white">I'm Front-End web developer</p>
                        </div>
                        <div class="mb-2 flex flex-row flex-wrap  gap-x-3 justify-center text-white">
                            <div>
                                <a href="https://www.linkedin.com/in/caio-santos-b02524180/?locale=es_ES" target="_blank">
                                    <i class="bi bi-linkedin hover:text-yellow-200"></i>
                                </a>
                            </div>
                            <div>
                                <a href="https://github.com/caiosantosSTL" target="_blank">
                                    <i class="bi bi-github hover:text-yellow-200"></i>
                                </a>
                            </div>

                            <div>
                                <a class="flex flex-row hover:text-yellow-200" href="mailto:caiosantos_xds@hotmail.com">
                                    <i
                                        class="bi bi-envelope-fill mr-2"></i>
                                    <p>caiosantos_xds@hotmail.com</p>
                                </a>
                            </div>
                            <div>
                                <a class="flex flex-row hover:text-yellow-200" href="tel:+524421097022">
                                    <i class="bi bi-telephone-fill"></i>
                                    <p>+ 52 442 109 7022</p>
                                </a>
                            </div>

                            <div>
                                <a class="flex flex-row hover:text-yellow-200" href="https://docusaurus-notes.vercel.app/">
                                    <i class="bi bi-box-arrow-in-up-right mr-2"></i> 
                                    <p>My notes</p>
                                </a>
                            </div>

                        </div>
                    </div>

                </div>
            </div>

            <div class="h-20" id="profile-edu"></div>
            <!--space-->

            <!--part 2-->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-2 my-4">
                <div class="flex justify-center">
                    <div class="flex flex-col p-2">

                        <p class="text-2xl flex justify-center">Profile</p>

                        <p>I'm a web developer, front-end using Vue.js and React.js and back-end using MySQL, SQLite and
                            API. I also like to develop in game engine like Unity and Godot.</p>

                    </div>

                </div>
                <div class="flex justify-center">
                    <div class="flex flex-col p-2">
                        <p class="text-2xl flex justify-center">Education</p>
                        <ul>
                            <li><span class="font-bold">Institution:</span> UVM - Universidad del Valle de México</li>
                            <li><span class="font-bold">Course:</span> Computer systems engineering</li>
                            <li><span class="font-bold">Conclusion:</span> 2020</li>
                        </ul>
                    </div>

                </div>

            </div>

            <div class="h-20" id="employment"></div>
            <!--space-->

            <!-- part 3-->
            <div class="grid grid-cols-1 gap-2 my-4">
                <p class="text-2xl flex justify-center mb-4">Employment History</p>
                <div class="flex justify-center">
                    <div class="flex flex-col p-2">


                        <div class="flex flex-col gap-2 md:flex-nowrap flex-wrap">

                            <div class="collapse  border rounded-box border-base-300 collapse-arrow">
                                <input type="checkbox">
                                <div class="collapse-title text-xl font-medium text-center">
                                    Unidad de investigación de Neurodesarrollo UNAM
                                </div>

                                <div class="collapse-content space-y-2">
                                    <p class="italic flex justify-center">09/2019 * 03/2020</p>
                                    <p class="text-center"><span class="font-bold">Responsibilities:</span> Social
                                        service: Web applications, Database administration,
                                        Unity3D application
                                    </p>
                                </div>
                            </div>

                            <div class="collapse border rounded-box border-base-300 collapse-arrow">
                                <input type="checkbox">
                                <div class="collapse-title text-xl font-medium text-center">
                                    Cerocatorce The Rewards Company
                                </div>

                                <div class="collapse-content space-y-2">
                                    <p class="italic flex justify-center">08/2021 * 02/2022</p>
                                    <p class="text-center"><span class="font-bold">Responsibilities:</span> I worked on
                                        front-end and back-end project development,
                                        landing page creation, project maintenance using the symfony framework.
                                    </p>
                                </div>
                            </div>

                        </div>

                    </div>
                </div>
            </div>

            <div class="h-20" id="skills"></div>
            <!--space-->

            <!-- part 5-->
            <div class="grid grid-cols-1 gap-2 my-4">
                <div>
                    <p class="text-2xl flex justify-center mb-4">Skills - Web development</p>
                    <div class="flex justify-start flex-wrap gap-2">

                        <Popover title="Symfony">
                            <Card picsrc="../img/sf.png" title="Symfony" />
                        </Popover>

                        <Popover title="Django">
                            <Card picsrc="../img/django.png" title="Django" />
                        </Popover>

                        <Popover title="Flask">
                            <Card picsrc="../img/flask.png" title="Flask" />
                        </Popover>

                        <Popover title="Laravel">
                            <Card picsrc="../img/laravel.png" title="Laravel" />
                        </Popover>

                        <Popover title="Node js">
                            <Card picsrc="../img/node.png" title="Node js" />
                        </Popover>

                        <Popover title="React Js">
                            <Card picsrc="../img/react.png" title="React Js" link="https://next-tailwind-pokemon.vercel.app/" />
                        </Popover>

                        <Popover title="Vue Js">
                            <Card picsrc="../img/vue.png" title="Vue Js" />
                        </Popover>

                        <Popover title="Svelte">
                            <Card picsrc="../img/svelte.png" title="Svelte" />
                        </Popover>

                        <Popover title="Tailwind">
                            <Card picsrc="../img/tailwind.png" title="Tailwind" link="https://codesandbox.io/s/brave-cannon-8jkdk0?file=/index.html" />
                        </Popover>

                        <Popover title="Bootstrap">
                            <Card picsrc="../img/bootstrap.png" title="Bootstrap" />
                        </Popover>


                    </div>
                </div>

                <div>
                    <p class="text-2xl flex justify-center mb-4">Skills - 3D development</p>
                    <div class="flex justify-start flex-wrap gap-2">

                        <Popover title="Blender">
                            <Card picsrc="../img/blender.png" title="Blender" link="https://www.deviantart.com/redenalux" />
                        </Popover>

                        <Popover title="Godot">
                            <Card picsrc="../img/godot.png" title="Godot" link="https://vimeo.com/user130645208" />
                        </Popover>

                        <Popover title="Unity">
                            <Card picsrc="../img/unity.png" title="Unity" link="https://vimeo.com/user130645208" />
                        </Popover>


                    </div>
                </div>
                <div>
                    <p class="text-2xl flex justify-center mb-4">Skills - Music composition</p>
                    <div class="flex justify-start flex-wrap gap-2">

                        <Popover title="LMMS">
                            <Card picsrc="../img/lmms.png" title="LMMS" link="https://soundcloud.com/caiosds" />
                        </Popover>

                    </div>
                </div>

            </div>




        </div>

    </section>
    <div class="h-20"></div>
    <!--space-->
    <footer class="bg-black h-28">
        <!-- footer -->
        <Footer />

    </footer>
</main>