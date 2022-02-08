<script>
    import Navbar from '../navbar.svelte'
    
</script>

<main>

    <section>
        <!--navbar-->
        <Navbar/>

    </section>
    <section>
        <div class="container mx-auto">

            <!--part 1-->
            <div class="grid grid-cols-1  gap-2 my-2">
                <div class="p-10 bg-black flex justify-center flex-wrap rounded-3xl">
                    <div class="flex flex-col ">
                        <div class="flex justify-center">
                            <img src="../img/piccaio2.jpeg" class="rounded-full scale-75 object-contain w-40" alt="">
                        </div>

                        <h1 class="text-4xl flex justify-center text-white text-center">Caio Santos da Silva</h1>
                        <div class="flex justify-center">
                            <p class="text-white">I'm Front-End web developer</p>
                        </div>
                        <div class="mb-2 flex flex-row flex-wrap  gap-x-3 justify-center text-white">
                            <div>
                                <a href="/">
                                    <i class="bi bi-linkedin hover:text-yellow-200"></i>
                                </a>
                            </div>
                            <div>
                                <a href="/">
                                    <i class="bi bi-github hover:text-yellow-200"></i>
                                </a>
                            </div>

                            <div>
                                <a href="/">
                                    <i
                                        class="bi bi-envelope-fill mr-2 hover:text-yellow-200">caiosantos_xds@hotmail.com</i>
                                </a>
                            </div>
                            <div>
                                <i class="bi bi-telephone-fill hover:text-yellow-200">+ 52 442 109 7022</i>

                            </div>

                        </div>
                    </div>

                </div>
            </div>

            <!--part 2-->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-2 my-4">
                <div class="flex justify-center">
                    <div class="flex flex-col p-2">

                        <p class="text-2xl flex justify-center">Profile</p>

                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem fuga excepturi vel
                            reprehenderit inventore magni aliquid nemo laboriosam provident fugit.Lorem ipsum dolor sit
                            amet, consectetur adipisicing elit. Dolorem fuga excepturi vel
                            reprehenderit inventore magni aliquid nemo laboriosam provident fugit.</p>

                    </div>

                </div>
                <div class="flex justify-center">
                    <div class="flex flex-col p-2">
                        <p class="text-2xl flex justify-center">Education</p>
                        <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem fuga excepturi vel
                            reprehenderit inventore magni aliquid nemo laboriosam provident fugit.Lorem ipsum dolor sit
                            amet, consectetur adipisicing elit. Dolorem fuga excepturi vel
                            reprehenderit inventore magni aliquid nemo laboriosam provident fugit.</p>
                    </div>

                </div>

            </div>

            <!-- part 3-->
            <div class="grid grid-cols-1 gap-2 my-4">
                <p class="text-2xl flex justify-center mb-4">Employment History</p>
                <div class="flex justify-center">
                    <div class="flex flex-col p-2">


                        <div class="flex flex-col gap-2 md:flex-nowrap flex-wrap">

                            <div class="collapse  border rounded-box border-base-300 collapse-arrow">
                                <input type="checkbox">
                                <div class="collapse-title text-xl font-medium text-center">
                                    Company A
                                </div>
                                <div class="collapse-content">
                                    <p>Collapse content reveals with focus. If you add a checkbox, you can control it
                                        using checkbox instead of focus. Or you can force-open/force-close using. Lorem
                                        ipsum dolor sit amet consectetur, adipisicing elit. Expedita officia itaque ut
                                        magnam provident facilis illo tenetur, harum id culpa.
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Non officiis soluta
                                        enim a consectetur nisi harum distinctio velit earum quaerat!
                                    </p>
                                </div>
                            </div>

                            <div class="collapse border rounded-box border-base-300 collapse-arrow">
                                <input type="checkbox">
                                <div class="collapse-title text-xl font-medium text-center">
                                    Company B
                                </div>

                                <div class="collapse-content">
                                    <p>dasjdkl</p>
                                    <p>Collapse content reveals with focus. If you add a checkbox, you can control it
                                        using checkbox instead of focus. Or you can force-open/force-close using. Lorem
                                        ipsum dolor sit amet consectetur, adipisicing elit. Expedita officia itaque ut
                                        magnam provident facilis illo tenetur, harum id culpa.
                                        Lorem ipsum dolor sit amet consectetur adipisicing elit. Non officiis soluta
                                        enim a consectetur nisi harum distinctio velit earum quaerat!
                                    </p>
                                </div>
                            </div>

                        </div>

                    </div>
                </div>
            </div>

            <!-- part 5-->
            <div class="grid grid-cols-1 gap-2 my-4">
                <p class="text-2xl flex justify-center mb-4">Skills</p>
                <div class="flex justify-around flex-wrap gap-2">


                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/sf.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Symfony</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/node.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Node Js</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/flask.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Flask</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/django.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Django</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/laravel.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Laravel</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/godot.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Godot</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/unity.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Unity</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/bootstrap.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Godot</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>

                    <div class="flex flex-col p-2  w-52 card border-black border-2">
                        <div class="flex justify-center">
                            <img src="../img/blender.png" class="w-40 rounded-2xl" alt="">
                        </div>
                        <div class="flex justify-center">Godot</div>
                        <div>
                            <p class="text-center flex flex-wrap p-2">Lorem ipsum, dolor sit amet consectetur adipisicing
                                elit.
                            </p>
                        </div>

                    </div>


                </div>
            </div>

        </div>

    </section>
    <section>
        <!-- footer -->

    </section>
</main>