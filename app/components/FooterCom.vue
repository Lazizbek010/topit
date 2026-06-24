<template>
  <footer class="bg-gray-900 text-gray-300">
    <div class="max-w-7xl mx-auto px-6 py-12">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-5 gap-8">
        <div>
          <h3 class="text-white font-semibold mb-4">Покупателям</h3>
          <ul class="space-y-2 text-sm">
            <li class="hover:text-white"><a href="#">Как сделать заказ</a></li>
            <li class="hover:text-white"><a href="#">Способы оплаты</a></li>
            <li class="hover:text-white"><a href="#">Доставка</a></li>
            <li class="hover:text-white"><a href="#">Возврат товара</a></li>
            <li class="hover:text-white"><a href="#">Вопросы и ответы</a></li>
          </ul>
        </div>

        <div>
          <h3 class="text-white font-semibold mb-4">Партнёрам</h3>
          <ul class="space-y-2 text-sm">
            <li class="hover:text-white"><a href="#">Продайте на TOP-IT</a></li>
            <li class="hover:text-white"><a href="#">Перевозчики</a></li>
            <li class="hover:text-white"><a href="#">Откройте пункт выдачи</a></li>
          </ul>
        </div>

        <div>
          <h3 class="text-white font-semibold mb-4">Компания</h3>
          <ul class="space-y-2 text-sm">
            <li class="hover:text-white"><a href="#">О нас</a></li>
            <li class="hover:text-white"><a href="#">Контакты</a></li>
            <li class="hover:text-white"><a href="#">Вакансии</a></li>
          </ul>
        </div>

        <div>
          <h3 class="text-white font-semibold mb-4">Наши проекты</h3>
          <ul class="space-y-2 text-sm">
            <li class="hover:text-white"><a href="#">ЗОЖ и спорт</a></li>
            <li class="hover:text-white"><a href="#">Детям</a></li>
            <li class="hover:text-white"><a href="#">Трудоустройство</a></li>
          </ul>
        </div>

        <div class="space-y-6">
          <div>
            <h3 class="text-white font-semibold mb-3">Мобильные устройства</h3>
            <div class="flex flex-col sm:flex-row sm:items-center sm:space-x-3 space-y-3 sm:space-y-0">
              <a class="flex items-center bg-gray-800 hover:bg-gray-700 px-3 py-2 rounded shadow-sm" href="#">
                <svg class="w-5 h-5 mr-2 text-white" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg"><path d="M16.365 1.43c0 1.02-.39 1.98-1.04 2.71-.69.76-1.75 1.45-2.8 1.45-.09-1.03.35-1.95 1.04-2.71.7-.78 1.75-1.46 2.81-1.45zM12.5 6.5c-2.66 0-4.81 2.15-4.81 4.81 0 2.66 2.15 4.81 4.81 4.81s4.81-2.15 4.81-4.81c0-2.66-2.15-4.81-4.81-4.81z"/></svg>
                <span class="text-sm">App Store</span>
              </a>

              <a class="flex items-center bg-gray-800 hover:bg-gray-700 px-3 py-2 rounded shadow-sm" href="#">
                <svg class="w-5 h-5 mr-2 text-white" viewBox="0 0 24 24" fill="currentColor" xmlns="http://www.w3.org/2000/svg"><path d="M2 3h20v18H2z"/></svg>
                <span class="text-sm">Google Play</span>
              </a>
            </div>
          </div>

          <div>
            <h3 class="text-white font-semibold mb-3">Мы в соцсетях</h3>
            <div class="flex items-center space-x-3">
              <a class="w-9 h-9 rounded-full bg-gray-800 flex items-center justify-center hover:bg-green-500" href="#" aria-label="Telegram">
                <svg class="w-4 h-4 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 2L11 13"/><path d="M22 2L15 22L11 13L2 9L22 2Z"/></svg>
              </a>
              <a class="w-9 h-9 rounded-full bg-gray-800 flex items-center justify-center hover:bg-pink-500" href="#" aria-label="Instagram">
                <svg class="w-4 h-4 text-white" viewBox="0 0 24 24" fill="currentColor"><path d="M7 2h10a5 5 0 015 5v10a5 5 0 01-5 5H7a5 5 0 01-5-5V7a5 5 0 015-5z"/></svg>
              </a>
              <a class="w-9 h-9 rounded-full bg-gray-800 flex items-center justify-center hover:bg-blue-600" href="#" aria-label="Facebook">
                <svg class="w-4 h-4 text-white" viewBox="0 0 24 24" fill="currentColor"><path d="M22 12a10 10 0 10-11.5 9.9v-7h-2.2v-2.9h2.2V9.4c0-2.2 1.3-3.4 3.3-3.4.95 0 1.95.17 1.95.17v2.1h-1.07c-1.05 0-1.38.66-1.38 1.33v1.6h2.35l-.37 2.9h-1.98v7A10 10 0 0022 12z"/></svg>
              </a>
              <a class="w-9 h-9 rounded-full bg-gray-800 flex items-center justify-center hover:bg-red-600" href="#" aria-label="YouTube">
                <svg class="w-4 h-4 text-white" viewBox="0 0 24 24" fill="currentColor"><path d="M23 7s-.2-1.7-.8-2.4c-.7-.9-1.5-.9-1.9-1C17.6 3 12 3 12 3s-5.6 0-8.3.6c-.4.1-1.2.1-1.9 1C1.2 5.3 1 7 1 7s-.2 1.8-.2 3.6V13c0 1.8.2 3.6.2 3.6s.2 1.7.8 2.4c.7.9 1.6.9 2 1 1.5.4 6.6.6 6.6.6s5.6 0 8.3-.6c.4-.1 1.2-.1 1.9-1 .6-.7.8-2.4.8-2.4s.2-1.8.2-3.6V11c0-1.8-.2-3.6-.2-3.6z"/></svg>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="border-t border-gray-800 mt-8 pt-6 text-sm text-gray-400 flex flex-col sm:flex-row sm:items-center sm:justify-between gap-4">
        <div>
          <div class="text-xs">© 2021-2026 TOP-IT. Все права защищены.</div>
          <div class="text-2xs">Указанная стоимость товаров и условия их приобретения действительны на текущую дату.</div>
        </div>

        <div class="flex items-center space-x-3">
          <div class="flex items-center space-x-2">
            <span class="px-2 py-1 bg-gray-800 rounded text-xs">VISA</span>
            <span class="px-2 py-1 bg-gray-800 rounded text-xs">Mastercard</span>
            <span class="px-2 py-1 bg-gray-800 rounded text-xs">Payme</span>
          </div>
        </div>
      </div>
    </div>

    <button class="fixed right-[200px] bottom-[350px] w-10 h-10 bg-green-500 rounded-full flex items-center justify-center shadow-lg hover:bg-green-600" aria-label="Back to top">
      <svg class="w-5 h-5 text-white" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 19V6"/><path d="M5 12l7-7 7 7"/></svg>
    </button>
  </footer>
</template>

<script setup>

</script>

<style scoped>
/* No additional styles — Tailwind handles the layout */
</style>