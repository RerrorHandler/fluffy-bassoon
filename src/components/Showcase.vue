<template>
    <div class="container mx-auto flex flex-col text-center relative">
        <div class="text-3xl text-white my-10">
            Ознакомьтесь с <span class="text-yellow-500">отраслевой картой</span> проектов 
        </div>
        <div class=" container mx-auto">
            <Hooper :itemsToShow="3" :centerMode="false" pagination="yes" class="showcase"> 
                <Slide class="px-20">
                    <div class=" relative">
                        <div class="border-2 rounded-md border-showcase p-2">
                            <div class="bg-showcase px-1 flex flex-col text-left items-center">
                                <div class="mx-auto">
                                    <img src="../assets/flag.png" class="mt-3">
                                </div>
                                <ul class=" list-disc text-white my-4">
                                    <li>
                                        Молочная продукция;
                                    </li>
                                    <li>
                                        Кондитерская продукция;
                                    </li>
                                    <li>
                                        Производство<br>полуфабрикатов;
                                    </li>
                                </ul>
                                <div class="flex flex-row relative">
                                    <img src="../assets/loupe.png" class=" absolute -left-5 top-1">
                                    <span class="underline text-yellow-500">Смотреть полностью</span>
                                </div>
                            </div>
                            <div class=" px-5 py-1 absolute -top-3 text-white span-showcase left-1/3 right-1/3 ">
                                <span class="block mt-2">FMCG</span>
                            </div>
                        </div>
                    </div>
                </Slide>
                <Slide class="px-20">
                    <div class=" relative">
                        <div class="border-2 rounded-md border-showcase p-2">
                            <div class="bg-showcase px-1 flex flex-col text-left items-center">
                                <div class="mx-auto">
                                    <img src="../assets/flag.png" class="mt-3">
                                </div>
                                <ul class=" list-disc text-white my-4">
                                    <li>
                                        Молочная продукция;
                                    </li>
                                    <li>
                                        Кондитерская продукция;
                                    </li>
                                    <li>
                                        Производство<br>полуфабрикатов;
                                    </li>
                                </ul>
                                <div class="flex flex-row relative">
                                    <img src="../assets/loupe.png" class=" absolute -left-5 top-1">
                                    <span class="underline text-yellow-500">Смотреть полностью</span>
                                </div>
                            </div>
                            <div class=" px-5 py-1 absolute -top-3 text-white span-showcase left-1/3 right-1/3 ">
                                <span class="block mt-2">FMCG</span>
                            </div>
                        </div>
                    </div>
                </Slide>
                <Slide class="px-20">
                    <div class=" relative">
                        <div class="border-2 rounded-md border-showcase p-2">
                            <div class="bg-showcase px-1 flex flex-col text-left items-center">
                                <div class="mx-auto">
                                    <img src="../assets/flag.png" class="mt-3">
                                </div>
                                <ul class=" list-disc text-white my-4">
                                    <li>
                                        Молочная продукция;
                                    </li>
                                    <li>
                                        Кондитерская продукция;
                                    </li>
                                    <li>
                                        Производство<br>полуфабрикатов;
                                    </li>
                                </ul>
                                <div class="flex flex-row relative">
                                    <img src="../assets/loupe.png" class=" absolute -left-5 top-1">
                                    <span class="underline text-yellow-500">Смотреть полностью</span>
                                </div>
                            </div>
                            <div class=" px-5 py-1 absolute -top-3 text-white span-showcase left-1/3 right-1/3 ">
                                <span class="block mt-2">FMCG</span>
                            </div>
                        </div>
                    </div>
                </Slide>
                <hooper-pagination slot="hooper-addons"></hooper-pagination>
            </Hooper>
        </div>
    </div>
</template>

<script>
import { Hooper, Slide, Pagination as HooperPagination } from 'hooper';
import 'hooper/dist/hooper.css';
export default {
  name: 'App',
  components: {
    Hooper,
    Slide,
    HooperPagination
  }
};
</script>

<style>
.shadow-linear {
 background: rgb(6, 11, 17);
background: linear-gradient(180deg, rgba(6, 11, 17,0.1) 0%, rgba(6, 11, 17,0.3) 75%, rgba(6, 11, 17,0.3) 100%); 
}
.showcase {
    height: 300px;
}
.span-showcase {
    background-color: #15181d;
}
.border-showcase {
    border-color: rgb(32,36,43);
}
.bg-showcase {
    background: rgb(32,36,43);
    background: linear-gradient(180deg, rgba(32,36,43,1) 0%, rgba(25,30,36,1) 50%, rgba(18,21,27,1) 100%);  
}
.hooper-indicator {
    margin: 0 4px;
    width: 12px;
    height: 12px;
    border-radius: 25px;
}
.hooper-indicator.is-active, .hooper-indicator:hover {
    background-color: #c99865;
}
</style>