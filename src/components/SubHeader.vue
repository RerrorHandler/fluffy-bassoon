<template>
    <div class="container mx-auto flex pl-8 flex-row mt-14 text-gray-50">
        <div class="flex flex-col w-11/12 pr-40">
            <div class="flex flex-row justify-between text-lg">
                <a href="" class="hover:text-yellow-300">О нас</a>
                <a href="" class="hover:text-yellow-300">Портофлио</a>
                <a href="" class="hover:text-yellow-300">Клиенты</a>
                <a href="" class="hover:text-yellow-300">Новости</a>
                <a href="" class="hover:text-yellow-300">Контакты</a>
            </div>
            <div class="flex flex-col text-3xl mt-20">
                <div>Создадим <span class="text-yellow-300">маркетинговую</span></div>
                <div><span class="text-yellow-300">Стратегию</span> для бизнеса</div>
                <div>и сделаем вас №1 в своей сфере</div>
            </div>
            <div class="flex flex-row my-10 items-center">
                <div class="-ml-10 mr-10"><img src="../assets/todolist.png"></div>
                <div class="flex flex-col mt-8">
                    <div>Только современные инструменты</div>
                    <div>привлечения целевых клиентов</div>
                </div>
            </div>
            <div class="flex flex-row">
                <div class="flex flex-row items-center"><span class="text-4xl">15</span><img src="../assets/img-plus.png" class="-mx-5 transform scale-50">
                <div class="flex flex-col font-light">
                    <div>лет повышаем</div>
                    <div>продажи бизнеса</div>
                </div>
                </div>
                <div class=" ml-20 flex flex-row items-center"><span class="text-4xl">60</span><img src="../assets/img-plus.png" class="-mx-5 transform scale-50">
                <div class="flex flex-col font-light">
                    <div>Направлений освоили</div>
                    <div>на высшем уровне</div>
                </div>
                </div>
            </div>
        </div>
        <div class="w-1/2 flex flex-col items-center">
            <div class="flex flex-col border-4 relative bg-form border-gray-700 max-w-md w-full">
                <img src="../assets/flag.png" class="mx-auto">
                <span class="mx-auto text-xl">Хотите узнать как</span>
                <span class="mx-auto text-xl mb-8 text-yellow-300">увеличить продажи<span class="text-white">?</span></span>
                <div class="relative mb-10 w-84 mx-auto">
                    <input type="text" class="w-full p-2 border-2 border-gray-500">
                    <div class="absolute -top-1/3 left-24 form-text px-2">Вам необходимо:</div>
                </div>
                <div class="relative mb-10 w-84 mx-auto">
                    <input type="text" class="w-full p-2 border-2 border-gray-500">
                    <div class="absolute -top-1/3 left-20 form-text px-2">Чем вы занимаетесь?</div>
                </div>
                <div class="relative mb-8 w-84 mx-auto">
                    <input type="text" class="w-full p-2 border-2 border-gray-500">
                    <div class="absolute -top-1/3 left-20 form-text px-4">Введите ваш номер</div>
                </div>
                <div class="flex flex-row mx-auto justify-between knopka">
                    <button class="w-40 rounded-md bg-gradient-to-r from-gray-800 to-gray-900 border-2 border-gray-700"><img src="../assets/t-icon.png" class="mx-auto filter grayscale contrast-200"></button>
                    <div class="mx-2"></div>
                    <button class="w-40 rounded-md bg-gradient-to-r from-gray-800 to-gray-900 border-2 border-gray-700"><img src="../assets/w-icon.png" class="mx-auto"></button>
                </div>
                <button class="relative mx-auto my-5">
                    <img src="../assets/button-form.png" class=" transform scale-125">
                </button>
                <div class="mx-auto w-84 mb-7"><input type="checkbox">
                    <span class="ml-2 text-gray-700">я согласен с <span class="text-yellow-300 text-sm underline">политикой конфидоциальности</span></span>
                </div>
                <div class="absolute -left-20 top-14">
                    <img src="../assets/chess1.png">
                </div>
            </div>
        </div>
    </div>
</template>
<style>
.knopka img {
    filter: grayscale(1)
}
.knopka img:hover {
    filter: grayscale(0);
}
.knopka button:focus img {
    filter:  grayscale(0);
}
.form-text {
    background: rgb(21,25,34);
background: linear-gradient(180deg, rgba(21,25,34,1) 0%, rgba(21,25,34,0.31556372549019607) 70%, rgba(21,25,34,0.8) 80%, rgba(21,25,34,0.2) 95%, rgba(21,25,34,0) 100%);
}
.w-84 {
    width: 20.75rem;
}
</style>