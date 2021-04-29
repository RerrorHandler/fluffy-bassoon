<template>
    <div class=" container mx-auto p-5 mt-10">
        <div class="h-100 relative m-10 cont2">
            <div class="flex flex-row text-4xl ml-20">
                <div class="flex flex-col w-6/12 mt-10">
                    <div>Кроме того, 90% бизнесов сливают</div>
                    <div>деньги из - за плохого маркетинга</div>
                    <div class="flex flex-col mt-6 text-xl">
                        <div>Запишитесь на консультацию, чтобы провести аудит</div>
                        <div>своего бизнеса и получить персональное</div>
                        <div>коммерческое предложение</div>
                    </div>
                </div>
                <div class="flex flex-col ml-20 mt-32 text-gray-500">
                    <div class=" relative text-2xl ">
                        <input type="text" class="px-4 py-3 w-100 border-2 border-gray-400" placeholder="+7 (___) ___ __ ___">
                        <div class="absolute form-text-22 -top-4 left-28 px-6">Введите Ваш номер</div>
                    </div>
                    <div class="mt-10 relative text-2xl">
                        <input type="text" class="px-4 py-3 w-100 border-2 border-gray-400" placeholder="Имя">
                        <div class="absolute form-text-22 -top-4 left-28 px-6">Введите Ваше Имя</div>
                    </div>
                    <button @click="TelegramOrWhatsApp(tow), tow = false" class="relative w-full">
                        <img src="../assets/buttonformprez.png" class="btnprez2">
                    </button>
                    <div class="text-xl"><input type="checkbox" checked>Я согласен с <span>политикой конфидоциальности</span></div>
                </div>
                <div class="absolute top-4 left-1/2"><img src="../assets/flag.png"></div>
                <div class="absolute -bottom-10 left-44"><img src="../assets/bookcont2.png" class="transform scale-150"></div>
            </div>
        </div>
    </div>
</template>
<style>
.btnprez2 {
    width: 660px;
    margin-left: -50px;
}
.form-text-22 {
    background: rgb(200,201,208);
background: radial-gradient(circle, rgba(200,201,208,1) 38%, rgba(200,201,208,1) 75%, rgba(200,201,208,0.6965161064425771) 95%, rgba(200,201,208,0.6881127450980392) 99%);
}
</style>
<script>
export default {
    data () {
      return {tow : false};
  },
  methods: {
    TelegramOrWhatsApp: function (ToW) {
        if (ToW === true) {
        location.href='https://web.telegram.org/#/im?p=@muju_c07'
        }
        else {
            location.href="https://api.whatsapp.com/send?phone=77476498669&text=%D0%94%D0%BE%D0%B1%D1%80%D1%8B%D0%B9%20%D0%B4%D0%B5%D0%BD%D1%8C%2C%20%D1%8F%20%D0%BF%D0%BE%20%D0%BF%D0%BE%D0%B2%D0%BE%D0%B4%D1%83"
        }
    }
},
}
</script>