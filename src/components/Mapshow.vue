<template>
    <div class=" container mx-auto flex flex-col mt-20 mb-80 text-white">
        <div class="text-center text-3xl">Мы занимаемся продвижением <span class="text-yellow-500">не всех бизнесов</span>,</div>
        <div class="text-center text-3xl mb-20">а только тех, кому мы <span class="text-yellow-500">можем гарантировать продажи</span></div>
        <div class="w-1/2 mx-auto flex flex-col items-center relative">
            <div class="flex flex-col border-4 relative bg-form border-color max-w-md w-full">
                <img src="../assets/flag.png" class="mx-auto">
                <span class="mx-auto text-xl">Хотите узнать как</span>
                <span class="mx-auto text-xl mb-8 text-yellow-300">увеличить продажи<span class="text-white">?</span></span>
                <div class="relative mb-10 w-84 mx-auto">
                    <input type="text" class="w-full p-2 border-2 border-gray-500" placeholder="Увеличение продаж">
                    <div class="absolute -top-1/3 left-24 form-text px-2">Вам необходимо:</div>
                </div>
                <div class="relative mb-10 w-84 mx-auto">
                    <input type="text" class="w-full p-2 border-2 border-gray-500" placeholder="Например производство кухонь">
                    <div class="absolute -top-1/3 left-20 form-text px-2">Чем вы занимаетесь?</div>
                </div>
                <div class="relative mb-8 w-84 mx-auto">
                    <input type="text" class="w-full p-2 border-2 border-gray-500" placeholder="+7 (___) ___ __ ___">
                    <div class="absolute -top-1/3 left-20 form-text px-4">Введите ваш номер</div>
                </div>
                <div class="flex flex-row mx-auto justify-between knopka">
                    <button @click="tow = true" class="w-40 rounded-md bg-gradient-to-r from-gray-800 to-gray-900 border-2 border-gray-700"><img src="../assets/t-icon.png" class="mx-auto filter grayscale contrast-200"></button>
                    <div class="mx-2"></div>
                    <button @click="tow = false" class="w-40 rounded-md bg-gradient-to-r from-gray-800 to-gray-900 border-2 border-gray-700"><img src="../assets/w-icon.png" class="mx-auto"></button>
                </div>
                <button @click="TelegramOrWhatsApp(tow)" class="relative mx-auto my-5">
                    <img src="../assets/button-form.png" class=" transform scale-125">
                </button>
                <div class="mx-auto w-84 mb-7"><input type="checkbox" checked>
                    <span class="ml-2 text-gray-700">я согласен с <span class="text-yellow-300 text-sm underline">политикой конфидоциальности</span></span>
                </div>
            </div>
            <div class="absolute right-28 bottom-56">
                <img src="../assets/maploupe.png">
            </div>
            <div class=" absolute -right-4 top-64 mt-4">
                Смотреть карту
            </div>
        </div>
    </div>
</template>
<style>
.border-color {
    border-color: #191c22;
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