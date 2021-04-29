<template>
<div class=" container mx-auto p-5 mt-10">
    <div class="h-100 relative m-10 cont2">
        <div class="flex flex-row">
            <div class="flex flex-col w-5/12 text-4xl mt-10 ml-20">
                <div>Посмотрите каких результатов</div>
                <div>можно достичь при помощи</div>
                <div>интернет - маркетинга</div>
                <div class="mt-20 relative">
                    <input type="text" class="px-4 py-3 w-100 border-2 border-gray-400" placeholder="+7 (___) ___ __ ___">
                    <div class="absolute text-gray-500 -top-5 left-20 text-3xl form-text-2 px-3">Введите Ваш номер</div>
                </div>
                <button @click="TelegramOrWhatsApp(tow), tow = false" class="relative w-full">
                    <img src="../assets/buttonformprez.png" class="btnprez">
                </button>
            </div>
            <div class="flex flex-col text-2xl mt-10 ml-20">
                <div>Запомните форму и получите презентацию</div>
                <div>о компании в Whats App. а так же документ с полной</div>
                <div>подборкой наших кейсов. Мы так же подробно</div>
                <div>расписали методологию работы в разных сферах</div>
                <div>бизнеса.</div>
            </div>
        </div>
        <div class="absolute right-32 bottom-5"><img src="../assets/bookcont3.png" class=" transform scale-150"></div>
        <div class="absolute top-4 left-1/2">
            <img src="../assets/flag.png">
        </div>
    </div>
</div>
</template>
<style>
.btnprez {
    width: 600px;
    margin-left: -50px;
}
.form-text-2 {
    background: rgb(226,228,232);
background: radial-gradient(circle, rgba(226,228,232,1) 38%, rgba(226,228,232,1) 75%, rgba(226,228,232,0.6965161064425771) 95%, rgba(226,228,232,0.6881127450980392) 99%);
}
.w-100 {
    width: 31rem;
}
.h-100 {
    height: 35rem/* 384px */
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