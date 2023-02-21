#It's my project to technopark.

<!DOCTYPE html>
<html lang="en">
  <head>
    <link rel="Stylesheet" href="Main.css" />
  <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Главная страница</title>
    <style>*{
    -webkit-margin:0;         
    -moz-margin:0;
    -o-margin:0;
    -ms-margin:0;
    margin: 0;
    -webkit-padding: 0;
    -o-padding:0;
    -ms-padding: 0;
    -moz-padding:0;
    padding:0;
}
.gl{
    font-family:monospace;
    font-size:25px ;
    margin-left: 0;
    padding: 10px 30px 10px 30px;
    background: linear-gradient(to right, #F6EFD2, #CEAD78);
    font-weight: 700;
}
nav {
    display: inline;
    margin: 70px;
    border: 3px solid rgba(178, 181, 184,0.7);
    font-size: 20px;
    font-family:monospace;
    border-bottom-right-radius: 30px;
   
}
body{
  background-repeat: no-repeat;
    background-size: cover;
    overflow: scroll;
    background-image: url(IMG_20230207_175931.jpg);
} 
select{

    -moz-appearance: none;
    -webkit-appearance: none;
    -o-appearance: none;
    -ms-appearance:none;
    appearance: none;
    font-size: 20px;
    -o-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    -ms-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    -moz-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    -webkit-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    background:linear-gradient(to right, #F6EFD2, #CEAD78);
    float:right;
    padding: 0 10px 10px 10px;
    -ms-border-bottom-left-radius: 30px;
    -o-border-bottom-left-radius: 30px;
    -webkit-border-bottom-left-radius: 30px;
    -moz-border-bottom-left-radius: 30px;
    border-bottom-left-radius: 30px;
}

div{
   position: relative;
    width: 500px;
    height: auto;
    text-align: center;
    border:3px solid white;
    border-radius: 15px;
    margin-left: 400px;
    margin-top: 200px;
    font-size: xx-large;
    -o-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    -ms-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    -moz-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    -webkit-background:linear-gradient(to right, #F6EFD2, #CEAD78);
    background: linear-gradient(to right, #F6EFD2, #CEAD78);
    right: 400px;
    bottom: 100px;
}
.Proj{
    color: yellow;
}
.Txt{
    color:#30313b;
    
}</style>
  </head>
  <body>
    <header>
      <nav class="gl">Герои-освободители города Костюковичи</nav>
      <select name=" Список имен" class="names" id="list" onchange="window.location.href = this.options[this.selectedIndex].value">
        <option value="" onclick=" window.location.href = 'Main.html'"selected  >Главная страница</option>
        <option value="Margelov_HTML.html" onclick=" window.location.href = 'Margelov_HTML.html'" class="Margelov">Маргелов Василий Филиппович</option>
        <option value="Skugar_HTML.html" class="Skugar" onclick="window.location.href = 'Skugar_HTML.html'">Скугарь Владимир Антонович</option>
        <option value="Sudilovskiy_HTML.html" class="Sudilovskiy" onclick="window.location.href = 'Sudilovskiy_HTML.html'">Судиловский Николай Петрович</option>
        <option value="Vorontsov_HTML.html" class="Vorontsov" onclick="window.location.href = 'Vorontsov_HTML.html'">Воронцов Александр Никифорович</option>
        <option value="Zinkovich_HTML.html" class="Zinkovich" onclick="window.location.href = 'Zinkovich_HTML.html'">Зинькович Митрофан Иванович</option>
        <option value="Avchachev_Html.html" class="Avchachev" onclick="window.location.href = 'Avchachev_Html.html'">Авхачев Феодосий Михайлович</option>
      </select>
    </header>
    <main>
      <div class="Text-block">
      <p class="Txt"></p>
    </div>
    <!-- <a class="Button"><?xml version="1.0" encoding="UTF-8"?>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" width="50" height="50"><g id="_01_align_center" data-name="01 align center"><path d="M7.412,24,6,22.588l9.881-9.881a1,1,0,0,0,0-1.414L6.017,1.431,7.431.017l9.862,9.862a3,3,0,0,1,0,4.242Z"/></g></svg></a> -->
    </main>
    <script>
      const Txt=document.querySelector('.Txt');
Txt.innerHTML='...<br>Вякі праляцяць за вякамі,<br>Пазбыўшы вайну назаўжды,<br>I, можа, гранёны мой камень<br>Грудку пазайздросціць тады, —<br>Калі ўжо ні сына, ні мужа<br>Ніхто не пакліча ў бядзе<br>I памяці колкая ружа<br>На зорку яго не ўпадзе;<br>Калі з безназоўных пазіцый<br>Скрозь каскі прабецца імгла,<br>А лес ёй насення пазычыць,<br>А сонца — агню і святла.<br>Я мог бы сасной ці вярбою<br>Шумець паміж дрэў дарагіх...<br><br>Але не згаджацца са мною<br>Ёсць права такое ў жывых.<p style="color:blue;">Ардадзь Куляшоў</p>'
 </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="Avchachev_Css.css" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>*{
    margin: 0;
    padding:0;
}
p{
    border-radius: 10px;
     text-shadow:2px 0 3px #ebf8e1,3px 0 3px #fcfaa7; 
     font-family: monospace;
     line-height: 40px;
     font-weight: 700;
     font-size: 25px;
}
h1{
font-family: monospace;
font-weight: 700;
font-size: 25px;
}
body{
    text-align: center;
    background: linear-gradient(0.25turn, #3f87a6, #ebf8e1, #f69d3c);
}
img[alt="Авхачев Феодосий Михайлович на фото"]{
    float: left;
}
.img-2{
    background-image: url(https://upload.wikimedia.org/wikipedia/ru/6/65/%D0%90%D0%B2%D1%85%D0%B0%D1%87%D1%91%D0%B2%2C_%D0%A4%D0%B5%D0%B4%D0%BE%D1%81_%D0%9C%D0%B8%D1%85%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D0%B8%D1%87.jpg);
    width: 300px;
    height: 300px;
    float: right;
    background-repeat: no-repeat;
    margin-left: 5px;
}

select{
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    font-size: 20px;
    background:linear-gradient(to right, #F6EFD2, #CEAD78);;
    float:right;
    padding: 0 10px 10px 10px;
}
a{
    font-size: 23px;
    font-family: monospace;
   float: left;
}
h1.underline{
    text-decoration: underline;
}
</style>
    <title>Авхачев</title>
  </head>
  <body>
    <img
      src="IMG_20230207_175839.jpg"
      alt="Авхачев Феодосий Михайлович на фото"
      width="300px"
      height="300px"
      title="Авхачев Феодосий Михайлович на фото"
    />
    <select name=" Список имен" id="list">
      <option value="" onclick=" window.location.href = '../Main_Part/Main.html'"  >Главная страница</option>
      <option value="Margelov_HTML.html" onclick=" window.location.href = 'Margelov_HTML.html';" class="Margelov" >Маргелов Василий Филиппович</option>
      <option value="Skugar'_HTML.html" class="Skugar" onclick="window.location.href = 'Skugar_HTML.html'" >Скугарь Владимир Антонович</option>
      <option value="Sudilovskiy_HTML.html" class="Sudilovskiy" onclick="window.location.href = 'Sudilovskiy_HTML.html'" >Судиловский Николай Петрович</option>
      <option value="Vorontsov_HTML.html" class="Vorontsov" onclick="window.location.href = 'Vorontsov_HTML.html'" >Воронцов Александр Никифорович</option>
      <option value="Zinkovich_HTML.html" class="Zinkovich" onclick="window.location.href = 'Zinkovich_HTML.html'" >Зинькович Митрофан Иванович</option>
      <option value="Avchachev_Html.html" class="Avchachev" onclick="window.location.href = 'Avchachev_Html.html'" selected>Авхачев Феодосий Михайлович</option>
    </select>
    <h1 class="underline">Феодосий Миха́йлович Авхачёв</h1>
    <p>
      (4 сентября 1909 — 17 ноября 1993) — советский офицер, танкист, участник
      Великой Отечественной войны, Герой Советского Союза (1946). Майор.
      Биография Родился 4 (17) сентября 1909 года в деревне Мошевое ныне
      Костюковичского района Могилёвской области (Белоруссия). Белорус. В
      марте-августе 1930 года работал в Донбассе — чернорабочий на шахте № 22 в
      посёлке Снежное (ныне в Донецкой области). В 1930—1931 годах работал в
      Кривбассе — чернорабочий на шахте имени Розы Люксембург Колачевского
      рудника (ныне не существует, территория Терновского района города Кривой
      Рог Днепропетровской области). В мае-октябре 1931 года – колхозник в
      колхозе имени К. Е. Ворошилова в родной деревне. В армии с октября 1931
      года. Служил в пехоте (в Белорусском военном округе). В мае 1932 года
      окончил полковую школу, в ноябре 1932 года — бронетанковые курсы. До мая
      1938 года служил командиром танка танкового батальона стрелковой дивизии
      (в Белорусском военном округе). В ноябре 1938 года окончил курсы
      автотехников в Смоленске. Служил политруком автороты и политруком танковой
      роты (в Западном и Прибалтийском особых военных округах). Участник
      Великой Отечественной войны: в июне-июле 1941 — политрук роты 10-го
      танкового полка 5-й танковой дивизии. Воевал на Северо-Западном фронте.
      Участвовал в оборонительных боях в Литве и Белоруссии. С июля 1941 —
      политрук учебной танковой роты (в Московском военном округе), в октябре
      1941 — октябре 1942 — политрук учебной роты 9-го отдельного учебного
      танкового полка (в городе Владимир). В феврале 1943 года окончил Курсы
      усовершенствования офицерского состава при Военной академии механизации и
      моторизации. В феврале-августе 1943 года находился в резерве Управления
      бронетанковых и механизированных войск Степного военного округа. В
      сентябре 1943 — январе 1944 — заместитель командира батальона 35-го
      учебного танкового полка (в городе Горький, ныне Нижний Новгород). В
      качестве опытного специалиста в июне 1944 года был откомандирован для
      оказания помощи в Войско Польское. Командир 3-го танкового батальона
      1-й польской танковой бригады капитан Ф. М. Авхачёв воевал на 1-м и 2-м
      Белорусском фронтах.
    </p>
      <div class="img-2" title="Авхачев Феодосий Михайлович"></div>
      
      <p>
      Участвовал в Варшавско-Познанской,
      Восточно-Померанской и Берлинской операциях. За отличие в штурме города
      Меркиш-Фридлянд (ныне Мирославец, Польша) награждён орденом Красного
      Знамени (25 марта 1945). В боях за город Нойштадт (ныне Вейхерово)
      танки батальона капитана Ф. М. Авхачёва поддерживали действия 326-го
      гвардейского стрелкового полка 101-й гвардейской стрелковой дивизии.
      Совершив обходной манёвр, танкисты с севера ворвались в город и помогли
      стрелковым соединениям штурмовать его. Особо отличился в марте 1945
      года в боях за город Гдыня (ныне Польша), в котором находились крупный
      гарнизон, порт и базы снабжения вермахта. Танковый батальон под его
      командованием одним из первых ворвался в город, уничтожил 11 орудий
      противника, захватил 20 паровозов, около 100 вагонов с грузом, 5 складов с
      продовольствием, около 350 автомашин, а также 30 мотоциклов. Указом
      Президиума Верховного Совета СССР от 15 мая 1946 года «за умелое
      командование батальоном и личное мужество и героизм, проявленные в боях»,
      майору Авхачёву Федосу Михайловичу присвоено звание Героя Советского Союза
      с вручением ордена Ленина и медали «Золотая Звезда». После войны до мая
      1946 года продолжал командовать танковым батальоном в Войске Польском. В
      июле 1947 года окончил Ленинградскую высшую офицерскую бронетанковую
      школу. С июля 1947 года майор Ф. М. Авхачёв — в запасе. В 1948—1950
      годах работал заместителем председателя правления кооперативной фабрики
      «Спартак» (производство спортивного инвентаря), в 1950—1953 годах —
      председателем правления артели «Трикотажник». В 1953—1954 годах — старший
      товаровед хозяйственного управления Министерства автомобильного транспорта
      и шоссейных дорог СССР. В 1954—1962 годах — управляющий конторы
      материально-технического снабжения «Райтехснаб» Советского (с 1960 года —
      Фрунзенского) района города Москвы, в октябре — ноябре 1962 — старший
      товаровед ремонтно-строительного треста Фрунзенского района Москвы. Затем
      работал в Ремонтно-строительном тресте Краснопресненского района Москвы:
      старшим товароведом строительного управления № 1 (в 1962—1964 годах) и
      старшим инженером по оборудованию строительного управления № 2 (в марте —
      мае 1964 года). В 1964—1969 годах работал управляющим конторы
      материально-технического снабжения Краснопресненского района. Жил в
      Москве. Умер 17 ноября 1993 года. Похоронен на Митинском кладбище в
      Москве.
    </p>
<a href="http://wiki.mogilev.by/index.php/%D0%90%D0%92%D0%A5%D0%90%D0%A7%D0%95%D0%92_%D0%A4%D0%B5%D0%B4%D0%BE%D1%81_%D0%9C%D0%B8%D1%85%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2%D0%B8%D1%87">Смотреть на википедии:Авхачев Феодосий Михайлович</a>
    <div class="img-1"></div>
  </body>
</html>



