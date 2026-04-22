[CPS center.html](https://github.com/user-attachments/files/26966806/CPS.center.html)
<!DOCTYPE html>
<!-- saved from url=(0036)http://127.0.0.1:5500/6.8/index.html -->
<html lang="ru"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CPS center</title>
    <link rel="stylesheet" href="./CPS center_files/style.css">
</head>
<body>

    <header class="hair">

      <nav class="burger">

        <button class="hair__button">

          <img src="./CPS center_files/burger.svg" alt="burger.svg">

        </button>

        <div class="line hair__none">

      </div>

        <img src="./CPS center_files/Group.svg" alt="Group.svg">

      </nav>

      <div class="none__button">

      <div class="hair__none">

      <button class="hair__button">

        <img src="./CPS center_files/call.svg" alt="">

      </button>

      <button class="hair__button">
        <img src="./CPS center_files/chat.svg" alt="">

      </button>

      <button class="hair__button">

        <img src="./CPS center_files/profile.svg" alt="">

      </button>

      </div>

      </div>

      <div class="line">

      </div>

      <div class="search">

        <button class="hair__button">

          <img src="./CPS center_files/repair.svg" alt="repair.svg">

        </button>

        <button class="hair__button">

          <img src="./CPS center_files/checkstatus.svg" alt="checkstatus.svg">

        </button>


      </div>


    </header>

<br>

    <main class="list">

      <div class="text">

        <div class="text__none">

         <h1 class="text__title">

          Услуги и сервисы

         </h1>

         <div class="search__none">

          <div class="none__search">

            Оставить заявку

            </div>

            <div class="none__width">

            <button class="none__button">

             <img src="./CPS center_files/repair.svg" alt="repair.svg">

            </button>

            </div>

          

          <div class="none__search">

            Статус ремонта

            </div>

            <div class="none__width">

            <button class="none__button">

              <img src="./CPS center_files/checkstatus.svg" alt="checkstatus.svg">

            </button>
            </div>

          
        </div>


        </div>

        <div class="click">

        <div class="button">

          <button type="button" class="button__select 
          button__select--blue"> 

            Ремонтируемые бренды 

          </button>

        </div>

      
      

        <div class="button">

          <button type="button" class="button__select 
          button__select--red">

           Дополнительные услуги

          </button>

        </div> 



        <div class="button">

          <button type="button" class="button__select 
          button__select--glow">

           Цены на услуги

          </button>

        </div>

        <div class="button">

          <button type="button" class="button__select 
          button__select--black">

           Адреса сервисных центров

          </button>

        </div>

        <div class="button">

          <button type="button" class="button__select 
          button__select--orange">

           Специальные цены

          </button>
        
        </div>

        </div>

        <div class="review">

          <button class="information__review">
            Отзывы
          </button>

          </div>

        
        <div class="information">

          

          <span class="information__text">
            Мы являемся авторизованым 
            сервисным центром 
            по ремонту техники Dell. Только у нас вы 
            можете отремонтировать свой ноутбук Dell 
            с официальной гарантией производителя.
            
            <span class="information__none">
              Мы успешно работаем 
              с 1992 года и заслужили репутацию
               надежного партнера

            </span>
            <br>
            <br>
            <span class="information__boock">
              Мы успешно работаем с 1992 года 
              и заслужили репутацию надежного партнера, 
              что подтверждает большое количество постоянных 
              клиентов. Мы гордимся тем, что к нам обращаются 
              по рекомендациям и, в свою очередь, советуют нас 
              родным и близким.
            </span>
            <br>
            <div class="information__loading">

             <div class="information__loading--down">
    

              <img src="./CPS center_files/expand.svg" alt="expand.svg">

             </div>

              <span>Читать далее</span>

         </div>
          </span>

         


          

         <div class="text__cps">

        

          <img src="./CPS center_files/_MG_3223.svg" alt="cps.svg" class="text__cps text__cps--green "></div>

          


         </div>

      

      </div>


      

    </main>



<!-- Code injected by live-server -->
<script>
	// <![CDATA[  <-- For SVG support
	if ('WebSocket' in window) {
		(function () {
			function refreshCSS() {
				var sheets = [].slice.call(document.getElementsByTagName("link"));
				var head = document.getElementsByTagName("head")[0];
				for (var i = 0; i < sheets.length; ++i) {
					var elem = sheets[i];
					var parent = elem.parentElement || head;
					parent.removeChild(elem);
					var rel = elem.rel;
					if (elem.href && typeof rel != "string" || rel.length == 0 || rel.toLowerCase() == "stylesheet") {
						var url = elem.href.replace(/(&|\?)_cacheOverride=\d+/, '');
						elem.href = url + (url.indexOf('?') >= 0 ? '&' : '?') + '_cacheOverride=' + (new Date().valueOf());
					}
					parent.appendChild(elem);
				}
			}
			var protocol = window.location.protocol === 'http:' ? 'ws://' : 'wss://';
			var address = protocol + window.location.host + window.location.pathname + '/ws';
			var socket = new WebSocket(address);
			socket.onmessage = function (msg) {
				if (msg.data == 'reload') window.location.reload();
				else if (msg.data == 'refreshcss') refreshCSS();
			};
			if (sessionStorage && !sessionStorage.getItem('IsThisFirstTime_Log_From_LiveServer')) {
				console.log('Live reload enabled.');
				sessionStorage.setItem('IsThisFirstTime_Log_From_LiveServer', true);
			}
		})();
	}
	else {
		console.error('Upgrade your browser. This Browser is NOT supported WebSocket for Live-Reloading.');
	}
	// ]]>
</script>

</body></html>
