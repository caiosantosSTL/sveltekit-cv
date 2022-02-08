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
    <section>
        <div class="container mx-auto">

            <!--part 1-->
            <div class="grid grid-cols-1  gap-2 my-2">
                <div class="p-10 bg-black flex justify-center flex-wrap rounded-3xl">
                    <div class="flex flex-col ">
                        <div class="flex justify-center">
                            <img src="../img/piccaio3.jpeg" class="rounded-full scale-75 object-contain w-40" alt="">
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
                            <Card picsrc="../img/react.png" title="React Js" />
                        </Popover>

                        <Popover title="Vue Js">
                            <Card picsrc="../img/vue.png" title="Vue Js" />
                        </Popover>

                        <Popover title="Svelte">
                            <Card picsrc="../img/svelte.png" title="Svelte" />
                        </Popover>

                        <Popover title="Tailwind">
                            <Card picsrc="../img/tailwind.png" title="Tailwind" />
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
                            <Card picsrc="../img/blender.png" title="Blender" />
                        </Popover>

                        <Popover title="Godot">
                            <Card picsrc="../img/godot.png" title="Godot" />
                        </Popover>

                        <Popover title="Unity">
                            <Card picsrc="../img/unity.png" title="Unity" />
                        </Popover>
    
    
                    </div>
                </div>
                <div>
                    <p class="text-2xl flex justify-center mb-4">Skills - Music composition</p>
                    <div class="flex justify-start flex-wrap gap-2">
    
                        <Popover title="LMMS">
                            <Card picsrc="../img/lmms.png" title="LMMS" />
                        </Popover>
    
                    </div>
                </div>

            </div>



        </div>

    </section>
    <section>
        <!-- footer -->
        <Footer />

    </section>
</main>