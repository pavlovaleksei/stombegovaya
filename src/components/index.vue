<template>
  <div class="container">
    <div class="row menu" id="menu">
      <div class="col" style="padding: 0px;">
        <ul class="menu_ponts">
          <li  v-on:click="goto('#infoClinica')"><p>О КЛИНИКЕ</p></li>
          <li><p>Персонал</p></li>
          <li><p>Прайс</p>
            <ul>
              <li v-on:click="selectPrise = prise[0]"><p>Ортопедия</p></li>
              <li v-on:click="selectPrise = prise[1]"><p>Терапия</p></li>
              <li v-on:click="selectPrise = prise[2]"><p>Хирургия</p></li>
            </ul>
          </li>
          <li v-on:click="goto('#visiograf')"><p>Рентген диагностика (Визиограф)</p></li>
          <!--<li><p>Наши работы</p></li>-->
          <li v-on:click="goto('#footer')"><p>Контакты</p></li>
        </ul>
      </div>





          <!--<div class="col menuPoint" v-on:click="goto('#infoClinica')"><p>О КЛИНИКЕ</p></div>-->
          <!--<div class="col menuPoint"><p>Персонал</p></div>-->
          <!--<div class="col menuPoint"><p>Прайс</p>-->
          <!--<ul>-->
            <!--<li v-on:click="selectPrise = prise[0]"><p>Ортопедия</p></li>-->
            <!--<li v-on:click="selectPrise = prise[1]"><p>Терапия</p></li>-->
            <!--<li v-on:click="selectPrise = prise[2]"><p>Хирургия</p></li>-->
          <!--</ul></div>-->
          <!--<div class="col menuPoint"><p>Рентген диагностика (Визиограф)</p></div>-->
          <!--<div class="col menuPoint"><p>Наши работы</p></div>-->
          <!--<div class="col menuPoint" v-on:click="goto('#footer')"><p>Контакты</p></div>-->
    </div>
    <div class="row header" style="background-image: url('/static/background-header.jpg')">
      <div class="col"><h1>
        <span>Стоматология</span> <br> <br>
        <span>"На Беговой"</span> <br>
      </h1>
        <h2><span>Большая садовая 82/90</span><br>
            <span>(8452) 52-80-30</span>
        </h2>
        <h2><span>ПН-ПТ 9:00 - 20:00</span><br>
          <span>СБ, ВС 9:00 - 18:00 </span>
        </h2>
        </div>
      <div class="col"></div>
    </div>
    <div class="row">
      <div class="col">
        <div class="container-fluid advantages">
          <div class="row">
            <div class="col">
              <h1>НАШИ ПРЕИМУЩЕСТВА</h1>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <p>
                Сотни пациентов уже сделали выбор в пользу нашей клиники. Секрет нашего успеха – в многообразии преимуществ, которые мы готовы предложить каждому обратившемуся.
              </p>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <div class="row">
                <div class="col"><img src="/static/green_image/image1.png" alt="">
                  <p>100% безболезненное лечение</p>
                </div>
                <div class="col"><img src="/static/green_image/image2.png" alt="">
                  <p>100% безопасное лечение</p>
                </div>
                <div class="col"><img src="/static/green_image/image3.png" alt="">
                  <p>Используем современную анестезию</p>
                </div>
                <div class="col"><img src="/static/green_image/image4.png" alt="">
                  <p>Работаем только с проверенными препаратами</p>
                </div>
              </div>
              <div class="row">
                <div class="col"><img src="/static/green_image/unnamed.png" alt="">
                  <p>Принимаем в точно назначенное время</p>
                </div>
                <div class="col"><img src="/static/green_image/image6.png" alt="">
                  <p>Удобное расположение, есть удобная парковка</p>
                </div>
                <div class="col"><img src="/static/green_image/image7.png" alt="">
                  <p>Врачи с 20-летним стажем</p>
                </div>
                <div class="col"><img src="/static/green_image/image8.png" alt="">
                  <p>Все первичные консультации бесплатно</p>
                </div>
              </div>
            </div>

          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="container-fluid infoClinica" id="infoClinica">
          <div class="row">
            <div class="col">
              <h2>СТОМАТОЛОГИЯ НА БЕГОВОЙ: ПРОФЕССИОНАЛЬНОЕ ЛЕЧЕНИЕ ЗУБОВ В САРАТОВЕ</h2>
            </div>
          </div>
          <div class="row">
            <div class="col"><p>
              Стоматология НА БЕГОВОЙ — это команда доброжелательных специалистов, готовых сделать лечение спокойным и приятным. Мы найдём персональный подход к каждому пациенту, поможем вам преодолеть страх и дискомфорт. У нас сделано все, чтобы вы чувствовали себя комфортно и уверенно.
            </p>
              <p>
              Стоматология НА БЕГОВОЙ – это довольные пациенты, где знаком качества является не только результат работы, но и сам процесс, а это в первую очередь, хорошее обращение к пациенту, стерильные инструменты и безболезненное лечение!
              </p>
              <p>
              Стоимость наших услуг оптимальна для широкого круга пациентов. Врач внимательно выслушает ваши жалобы, проведет профессиональный осмотр полости рта и подробно расскажет о предстоящих процедурах. Лечите зубы недорого и с максимальным удобством в нашей клинике!
              </p>

              <h4>КАЧЕСТВЕННАЯ СТОМАТОЛОГИЯ ПО РАЗУМНОЙ ЦЕНЕ</h4>
              <p>
              Стоматология НА БЕГОВОЙ предлагает широкий спектр стоматологических услуг. Мы используем современное оборудование и предлагаем полный комплекс лечебных мероприятий. Оказывая услуги на высоком уровне, мы удерживаем их стоимость в разумных пределах за счет оптимизации работы с поставщиками материалов и оборудования. Это именно тот случай, когда стоматология действительно может быть недорогой – убедитесь в этом сами, ознакомившись с нашим прейскурантом цен на стоматологические услуги.
              </p>
              <p>
              Мы приглашаем Вас на бесплатную консультацию в нашу клинику. Администратор поможет Вам подобрать наиболее удобное время, тем более что работаем мы ежедневно, без перерыва с 8-00 до 20-00.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="container-fluid gallery">
          <div class="row">
            <div class="col">
              <h1>Галерея</h1>
            </div>
          </div>
          <div class="row">
            <div class="col">
              <img :src="'/static/gallery/'+gallerySelect" class="prevue" alt="">
            </div>
          </div>
          <div class="row">
            <div class="col" v-for="item in gallery"><img :src="'/static/gallery/'+item" class="minill" v-on:click="gallerySelect = item" alt="" v-bind:class="item === gallerySelect? 'selectImg': ''"></div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="container-fluid personalList">
          <div class="row">
            <div class="col">
              <h1>Персонал</h1>
            </div>
          </div>
          <div class="row">
            <div class="col-4">
              <div class="container-fluid">
                <div class="row">
                  <div class="col"><i class="fas fa-user-md fa-7x"></i>
                  </div>
                </div>
                <div class="row">
                  <div class="h5">
                    Рабаданова Карина Александровна
                    Директор, врач-терапевт ,стаж работы 20 лет
                  </div>
                </div>

              </div>
            </div>
            <div class="col-4">
              <div class="container-fluid">
                <div class="row">
                  <div class="col"><i class="fas fa-user-md fa-7x"></i>
                  </div>
                </div>
                <div class="row">
                  <div class="h5">
                    Рахматулина   Аделя   Рашидовна
                    Врач терапевт ,стаж работы более 15 лет
                  </div>
                </div>

              </div>
            </div>
            <div class="col-4">
              <div class="container-fluid">
                <div class="row">
                  <div class="col"><i class="fas fa-user-md fa-7x"></i>
                  </div>
                </div>
                <div class="row">
                  <div class="h5">
                    Рахматулин Ильдар Рашидович
                    Врач общей практики
                    Стаж работы более 10 лет
                  </div>
                </div>

              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="container-fluid visiograf" id="visiograf">
          <div class="row">
            <div class="col">
              <h1>Визиограф</h1>
            </div>
          </div>
          <div class="row">
            <div class="col"><img src="/static/visiograf.jpg" alt="" width="100%"></div>
            <div class="col">
              <ul>
                <li>точность снимка</li>
                <li>возможность мгновенного просмотра больного зуба на экране компьютера с
                  многократным увеличением полученного изображения, хранение картинки на ПК и
                  передача ее по локальной сети и электронной почте;</li>
                <li>безопасность процедуры</li>
                <li>быстрота манипуляции</li>
                <li>редактирование цифровой визиограммы, использование различных фильтров для
                  улучшения визуального восприятия картинки</li>
              </ul>
            </div></div>
        </div>
      </div>
    </div>
    <div class="row priceFull">
      <div class="col">
        <div class="container-fluid" v-for="it in prise" style="position: relative">
            <div class="row" v-on:click="it.showTable = !it.showTable" style="text-align: center">
              <i class="fas fa-sort-down fa-2x" v-if="!it.showTable" style="position: absolute;
                                                                      "></i>
              <i class="fas fa-sort-up fa-2x" v-if="it.showTable"></i>
              <h1 style="margin-left: 30px">{{ it.title }}</h1>
            </div>
            <div class="row" v-if="it.showTable">
              <table class="table">
                <thead class="thead-dark">
                <tr>
                  <th v-for="item in it.headerTable">{{ item }}</th>
                </tr>
                </thead>
                <tbody>
                <tr v-for="item in it.data">
                  <td>{{ item.code }}</td>
                  <td>{{ item.text }}</td>
                  <td>{{ item.price }}</td>
                </tr>
                </tbody>
              </table>
            </div>
          <hr>
        </div>
      </div>
    </div>
    <div class="row">
      <div class="col">
        <div class="container-fruid footer" id="footer">
          <div class="row">
            <div class="col-6" id="map">
            </div>
            <div class="col-6"><p>
              Реквизиты:
              <br>
              <br>
              Общество с ограниченной ответственностью «Стоматология»
              <br>
              410054, г. Саратов, ул. Большая Садовая, д. 82/90, пом. 56
              <br>
              Тел: 8(845-2) 52-80-30
              <br>
              ИНН/КПП: 6454133186/645401001
              <br>
              ОГРН:1136454003344
              <br>
              р/с:40702810111010034093
              <br>
              ФИЛИАЛ «БИЗНЕС» ПАО «СОВКОМБАНК» г Москва
              <br>
              БИК: 044525058
              <br>
              к/с: 30101810045250000058
              <br>
              <br>

              Директор Рабаданова Карина Сапиюллаевна
            </p></div>
          </div>
        </div>
      </div>
    </div>
    <div class="modalWindow" v-if="selectPrise !== undefined">
      <div class="back">
        <div class="data">
          <div class="container-fluid">
            <div class="row">
              <div class="col">
                <table class="table">
                  <thead class="thead-dark">
                  <tr>
                    <th v-for="item in selectPrise.headerTable">{{ item }}</th>
                  </tr>
                  </thead>
                  <tbody>
                  <tr v-for="item in selectPrise.data">
                    <td>{{ item.code }}</td>
                    <td>{{ item.text }}</td>
                    <td>{{ item.price }}</td>
                  </tr>
                  </tbody>
                </table>

              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="closeButton" v-on:click="selectPrise = undefined">
        <p>Закрыть</p>
      </div>

    </div>
    <div class="buttonUp" v-if="scrollPosition >=80" v-on:click="goto('#menu')">
      В НАЧАЛО
    </div>
  </div>
</template>

<script>
  import $ from 'jquery'
export default {
  name: 'index',
  created(){
    this.gallerySelect = this.gallery[0]
    $(window).scroll(()=>{
      this.scrollPosition = $(window).scrollTop()
    })

  },
  methods:{
    goto(val){
      $('html, body').animate({ scrollTop: $(val).offset().top }, 500);
    }
  },
  data () {
    return {
      msg: 'Welcome to Your Vue.js App',
      selectPrise: undefined,
      scrollPosition: null,
      gallerySelect: "",
      gallery:[
        "20180202_181603.jpg",
        "20180202_181638.jpg",
        "20180202_181950.jpg",
        "20180202_182048.jpg",
        "20180202_183837.jpg",
        "20180202_183904.jpg",
        "20180202_185158.jpg"
      ],
      prise:[
        {
          title: "ПРЕЙСКУРАНТ НА УСЛУГИ ОРТОПЕДИЧЕСКОЙ СТОМАТОЛОГИИ",
          showTable: false,
          headerTable:[
            "№ п/п (код услуги по прейскуранту)", "Ортопедическая стомотология", "Стоимость 1 процедуры в рублях"
          ],
          data: [
            {code: "16", text: "Общие виды работ", price:""},
            {code: "16.1", text: "Осмотр, консультация стоматолога", price:"-"},
            {code: "18", text: "Несъемное протезирование", price:""},
            {code: "18.1", text: " Коронка металлокерамическая (зуб) до пяти зубов", price:"4500,0"},
            {code: "18.1.1", text: "Коронка металлокерамическая (зуб) пять и более зубов", price:"4200,0"},
            {code: "18.2", text: "Коронка цельнолитая (зуб)", price:"2850,0"},
            {code: "18.3", text: "Коронка штампованная (фасетка, зуб)", price:"1500,0"},
            {code: "18.4", text: "Коронка пластмассовая временная (зуб)", price:"600,0"},
            {code: "18.5", text: "Коронка металлопластмассовая (зуб)", price:"1600,0"},
            {code: "18.6", text: "Коронка с облицовкой", price:"850,0"},
            {code: "18.7", text: "Культевая вкладка", price:""},
            {code: "18.7.1", text: "1-корневая", price:"2000,0"},
            {code: "18.7.2", text: "2-х корневая", price:"2500,0"},
            {code: "19", text: "Съемное протезирование", price:""},
            {code: "19.1", text: "Полный (частичный) протез верхней челюсти", price:"8500,0"},
            {code: "19.2", text: "Полный (частичный) протез нижней челюсти", price:"8500,0"},
            {code: "19.3", text: "Съемный протез с литым базисом", price:"18000,0"},
            {code: "19.4", text: "Кламмер", price:"600,0"},
            {code: "19.5", text: "Бюгельный протез системы NEY с замковой фиксацией", price:"25000,0"},
            {code: "", text: "", price:""},
            {code: "20", text: "Отдельные манипуляции", price:""},
            {code: "20.1", text: "Срез коронки", price:""},
            {code: "20.1.1", text: "штампованной", price:"200,0"},
            {code: "20.1.2", text: "цельнолитой ", price:"400,0"},
            {code: "20.1.3", text: "металлокерамической", price:"300,0"},
            {code: "20.2", text: "Фиксация коронки", price:"350,0"},
            {code: "20.2.1", text: "Адгезор", price:"200,0"},
            {code: "20.2.2", text: "Фуджи-Плюс", price:"400,0"},
            {code: "20.2.3", text: "Временная фиксация", price:"150,0"},
            {code: "20.3", text: "Напыление (1 место)", price:"150,0"},
            {code: "20.4", text: "Пайка (1 место)", price:"150,0"},
            {code: "20.5", text: "Оттиск (слепок) альгинатный", price:"350,0"},
            {code: "20.6", text: "Оттиск (слепок) силиконовый", price:"450,0"},
            {code: "20.7", text: "Ложка индивидуальная", price:"500,0"},
            {code: "20.8", text: "Починка съемного протеза приварка зуба, кламмера", price:"700,0"},
            {code: "20.9", text: "Перебазировка (коррекция)", price:"1000,0"},
            {code: "", text: "", price:""}
          ]
        },
        {
          title: "ПРЕЙСКУРАНТ НА УСЛУГИ ТЕРАПЕВТИЧЕСКОЙ СТОМАТОЛОГИИ",
          showTable: false,
          headerTable:[
            "№ п/п (код услуги по прейскуранту)", "Терапевтическая стоматология", "Ценаза 1 ед. усл., руб."
          ],
          data: [
 {code:"1", text:"Общие виды работ:", price:""},
 {code:"1.1", text:"Прием первичного стоматологического больного (осмотр, консультация, оформление амбулаторной карты, составление комплексного плана лечения)", price:"-"},
 {code:"1.2", text:"Оформление выписки из амбулаторной карты стоматологического больного", price:"500,0"},
 {code:"2", text:"Анестезия:", price:""},
 {code:"2.1", text:"Аппликационная", price:"100,0"},
 {code:"2.2", text:"Внутриротовая карпульная анестезия (инфильтрационная, проводниковая, интралигаментарная)", price:"250,0"},
 {code:"", text:"Терапевтическая Стоматология", price:""},
 {code:"3", text:"Лечение неосложненного кариеса (без стоимости пломбы)", price:"350,0"},
 {code:"", text:"Лечение осложненного кариеса (без стоимости пломбы)", price:"450"},
 {code:"4", text:"Наложение прокладки", price:""},
 {code:"4.1", text:"Изолирующая ионосит", price:"200,0"},
 {code:"4.2", text:"Лечебная кальцимол", price:"200,0"},
 {code:"4.3", text:"Vitremer", price:"300,0"},
 {code:"4.4", text:"Жидкотекучий Filtek", price:"300,0"},
 {code:"5", text:"Лечение пульпита (периодонтита)", price:""},
 {code:"5.1", text:"Наложение девитализирующей пасты (депульпин VOCO)", price:"150,0"},
 {code:"5.2", text:"Импрегнация корневых каналов", price:""},
 {code:"5.2.1", text:"Крезопат", price:"150,0"},
 {code:"5.2.2", text:"Резодент", price:"150,0"},
 {code:"5.2.3", text:"Форфенан", price:"150,0"},
 {code:"5.3", text:"Эндодонтическая и медикаментозная обработка", price:""},
 {code:"5.3.1", text:"1 – канальный зуб", price:"300"},
 {code:"5.3.2", text:"2 – канальный зуб", price:"380"},
 {code:"5.3.3", text:"3 – канальный зуб", price:"460"},
 {code:"5.3.4", text:"4 – канальный зуб", price:"540"},
 {code:"5.3.5", text:"Машинная обработка 1-ого канала Pro Taper", price:"100"},
 {code:"5.3.6", text:"Временная пломба", price:"50"},
 {code:"6", text:"Пломбирование каналов", price:""},
 {code:"6.1", text:"Эндометазон, акросил", price:""},
 {code:"6.1.1", text:"1 – канальный зуб", price:"180,0"},
 {code:"6.1.2", text:"2 – канальный зуб", price:"280,0"},
 {code:"6.1.3", text:"3 – канальный зуб", price:"380,0"},
 {code:"6.1.4", text:"4 – канальный зуб", price:"480,0"},
 {code:"6.2", text:"Каласепт", price:""},
 {code:"6.2.1", text:"1 – канальный зуб", price:"100,0"},
 {code:"6.2.2", text:"2 – канальный зуб", price:"150,0"},
 {code:"6.2.3", text:"3 – канальный зуб", price:"200,0"},
 {code:"6.2.4", text:"4 – канальный зуб", price:"250,0"},
 {code:"6.3", text:"Гуттаперчивый штифт", price:""},
 {code:"6.3.1", text:"1 – канальный зуб", price:"200,0"},
 {code:"6.3.2", text:"2 – канальный зуб", price:"300,0"},
 {code:"6.3.3", text:"3 – канальный зуб", price:"400,0"},
 {code:"6.3.4", text:"4 – канальный зуб", price:"500,0"},
 {code:"7", text:"Распломбирование 1-го канала", price:""},
 {code:"7.1", text:"Паста", price:"150,0"},
 {code:"7.2", text:"Цемент", price:"500,0"},
 {code:"7.3", text:"Резорцин", price:"250,0"},
 {code:"7.4", text:"Извлечение инородного тела из канала", price:"500,0"},
 {code:"8", text:"Постановка штифта с фиксацией", price:""},
 {code:"8.1", text:"Анкерный", price:"400,0"},
 {code:"8.2", text:"Титановый", price:"500,0"},
 {code:"8.3", text:"Стекловолоконный", price:"600 ,0"},
 {code:"9", text:"Ретракция десны", price:"150,0"},
 {code:"10", text:"Коагуляция десны", price:"100,0"},
 {code:"12", text:"Шлифовка, полировка пломбы", price:"150,0"},
 {code:"13", text:"Удаление старой пломбы", price:"150,0"},
 {code:"14", text:"Материал для пломбирования", price:""},
 {code:"14.1", text:"FILTEK (светоотверждаемый композит)", price:""},
 {code:"14.1.1", text:" Пришеечный кариес", price:"600,0"},
 {code:"14.1.2", text:"Разрушение до 1/3 коронки", price:"700,0"},
 {code:"14.1.3", text:"Разрушение до 1/2 коронки", price:"1050,0"},
 {code:"14.1.4", text:" Разрушение до 2/3 коронки", price:"1150,0"},
 {code:"14.2", text:" FILTEK SUPRIM (светоотверждаемый композит)", price:"760,0"},
 {code:"14.2.2", text:"Разрушение до 1/3 коронки", price:"870,0"},
 {code:"14.2.3", text:"Разрушение до 1/2 коронки", price:"1050,0"},
 {code:"14.2.4", text:"Разрушение до 2/3 коронки", price:"1210,0"},
 {code:"14.3", text:"ВОССТАНОВЛЕНИЕ АНАТОМИЧЕСКОЙ ФОРМЫ ЗУБА", price:""},
 {code:"14.3.1", text:"Фронт", price:"2500,0"},
 {code:"14.3.2", text:"Моляры, премоляры", price:"3500,0"},
 {code:"14.4", text:"Vitremer", price:""},
 {code:"14.4.1", text:"Разрушение до 1/3 коронки", price:"350,0"},
 {code:"14.4.2", text:"Разрушение до 1/2 коронки", price:"500,0"},
 {code:"14.4.3", text:"Разрушение до 2/3 коронки", price:"600,0"},
 {code:"14.4.4", text:"Под коронку", price:"800,0"},
 {code:"14.5", text:"АДГЕЗИВНЫЙ МОСТ", price:""},
 {code:"14.5.1", text:"Фронт", price:"8000,0"},
 {code:"14.5.2", text:"Моляры, премоляры", price:"8500,0"},
 {code:"14.6", text:"ШИНИРОВАНИЕ (1 Зуб)", price:"700,0"},
 {code:"15", text:"Профилактика", price:""},
 {code:"15.1", text:"СНЯТИЕ ЗУБНОГО КАМНЯ + ЧИСТКА ПАСТАМИ", price:""},
 {code:"15.1.1", text:"6-ти фронтальных зубов", price:"600,0"},
 {code:"15.1.2", text:"Со всех зубов одной челюсти", price:"1500,0"},
 {code:"15.1.3", text:"Аппликация лекарственных веществ на десны", price:"100,0"},
 {code:"15.1.4", text:"Кюретаж закрытый в области одного зуба", price:"50,0"},
 {code:"15.1.5", text:"М/о десневого кармана", price:"50,0"},
 {code:"15.1.6", text:"Обработка зубов «Бифлюорид» (1 посещение)", price:"70,0"},
 {code:"", text:"Рентгенография ( Визиограф X-GENIUS)", price:""},
 {code:"15.1.7", text:"Диагностический рентген-снимок", price:"200,0"},
 {code:"15.1.8", text:"Распечатка рентген-снимка", price:"50,0"}
  ]
        },
        { title: "ПРЕЙСКУРАНТ НА УСЛУГИ ХИРУРГИЧЕСКОЙ СТОМАТОЛОГИИ",
          showTable: false,
          headerTable:[
            "№ п/п (код услуги по прейскуранту)", "Хирургическая Стоматология", "Стоимость 1 процедуры руб.\n"
          ],
          data: [
            {code:"1", text:"Общие виды работ:", price:""},
            {code:"21", text:"Осмотр, консультация стоматолога", price:"бесплатно"},
            {code:"22", text:"Внутриротовая карпульная анестезия (инфильтрационная, проводниковая, интралигаментарная)", price:"250,0"},
            {code:"23", text:"Удаление зуба", price:""},
            {code:"23.1", text:"- удаление 1 степени сложности", price:"500,0"},
            {code:"23.2", text:"- удаление 2 степени сложности", price:"600,0"},
            {code:"23.3", text:"- удаление 3 степени сложности", price:"700,0"},
            {code:"23.4", text:"- удаление ретинированного, полуретинированного зубов", price:"1700"},
            {code:"24", text:"Лечебная повязка", price:""},
            {code:"24.1", text:"- альвожил, альвостаз, йодоформ", price:"100,0"},
            {code:"24.2", text:"- коллапол", price:"500,0"},
            {code:"25", text:"Перевязка", price:"100,0"},
            {code:"26", text:"Лечение альвеолита", price:"500,0"},
            {code:"27", text:"Иссечение разрастания десны или капюшона (перикоронарит)", price:"500,0"},
            {code:"28", text:"Разрез при периостите", price:"500,0"},
            {code:"29", text:"Вскрытие пародонтального абсцесса", price:"550,0"},
            {code:"30", text:"Операция резекции верхушки корня", price:"1300,0"},
            {code:"31", text:"Наложение одного шва", price:"100,0"},
            {code:"32", text:"Снятие одного шва", price:"100,0"},
            {code:"33", text:"Операция коррекции уздечки", price:"1250,0"},
            {code:"34", text:"Удаление острых краев лунки (экзостозов) 1 зуб", price:"500,0"},
            {code:"35", text:"Иссечение новообразований в полости рта", price:"1500,0"},
            {code:"36", text:"Мембрана остеопластическая", price:"3000,0"},
            {code:"37", text:"Костная стружка «Остеон»", price:"3000,0"},
            {code:"38", text:"Вправление вывиха нижней челюсти", price:"500,0"},
            {code:"", text:"ДИАГНОСТИКА", price:""},
            {code:"1", text:"Рентгенография 1 снимок (диагностический)/повторный при лечении", price:"200,0"},
  ]
        }
      ]
    }
  }
}
</script>
