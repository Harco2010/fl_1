<script>
	let nan = 'ml-0'

   
</script>

<div class="flex flex-col h-screen bg-gray-50">
  <header class="h-10 w-full bg-gray-100 overflow-auto shadow-md">
        <div class="flex content-center items-center justify-end">
           <b class="flex justify-end text-center" />
        </div>
  </header>
  <nav class="flex">
        <input class="w-0 h-0" id="menu__toggle" type="checkbox" />
        <label class="menu__btn" for="menu__toggle">
          <span></span>
        </label>
        <ul class="menu__box">      
          <li>
            <a class="menu__item" href="/">{"Главная"}</a>
          </li>
          <li>
            <a class="menu__item" href="/config">{"Конфиг"}</a>
          </li>
          <li>
            <a class="menu__item" href="/connection">{"Подключение"}</a>
          </li>
        </ul>
  </nav>  
  <main class="flex-1 overflow-y-auto p-0 nan">
    <ul class="menu__main">
      <div class="bg-cover pt-0 px-4">
        <div class="grd-1col1 animate-pulse"></div>
        <div class="grd-3col1">
          <div class="crd">
            <h1 class="crd-hdr">flprog_svelte</h1>
          </div>
        </div>
      </div>
    </ul>
  </main>
</div>



