<html>
  <head>
    <title> Резюме Арзамасцевой Татьяны </title>
      <style type="text/css">
        IMG.photo{
         float: left;
         padding-left: 10px;
         padding-right: 20px;
         padding-bottom: 10px;
        }
        table {
          width: 100%;
          border: 1px solid #000000;
          border-spacing: 5px 5px;
        }
        TD {
          background: #FFD700;
          border: 1px solid #000000;
          padding: 5px;
          width: 15%;
        }
        .container {
          display: flex;
          align-items: center;
          margin-top: 210px;
        }
        .email {
          margin-right: auto;
        }
        .telegram {
          margin-left: 20px;
        }
        #info {
            display: none;
        }
        </style>
  </head>
  <body onload="calculateAge()"   bgcolor="#90EE90" >
    <img src="фото_паспорт.jpg" width="150" height="200" 
      alt="Иллюстрация" class="photo">
    <h2> <i> <b>Арзамасцева Татьяна </b></i> </h2>
    <p> <b> Дата рождения:</b> 08.10.2004 (20 лет)</p>
    <p> <b> Телефон: </b> +7 (951) 480-24-53 </p>
    <p> <b> Адрес: </b> Россия, г. Челябинск, ул. Кирова д. 23А кв. 36 </p>
    <p> <b> Опыт работы: </b> Отсутствует </p>
    <p> <b> О себе: </b> Учусь на специальности "Прикладная математика и информатика" на втором курсе ЮУрГУ. </p>
    <h2> <i> <b> Знание языков: </b></i> </h2>
    <table>
      <tr><td></td><td>HTML</td><td>JavaScript</td><td>С#</td><td>C++</td><td>Python</td></tr>
      <tr><td>Отличное владение</td><td></td><td></td><td></td><td></td><td></td></tr>
      <tr><td>Хорошее владение</td><td></td><td></td><td></td><td></td><td></td></tr>
      <tr><td>Среднее владение</td><td>+</td><td></td><td>+</td><td>+</td><td>+</td></tr>
      <tr><td>Плохое владение</td><td></td><td>+</td><td></td><td></td><td></td></tr>
    </table>

    <div class="container">
      <div class="email">
        <label> Почта: </label>
        <input placeholder="zedrokarz@yandex.ru">
        </div>

      <div class="telegram">
        <label> Телеграм: </label>
        <input placeholder="@cedrrrrr">
      </div>
    </div>
  
    <h3 align = "center" class="clickable" id="toggleButton"> Узнать меня подробнее </h3>
    <div id="info">
      <blockquote> Здравствуйте! Меня зовут Татьяна Арзамасцева, мне 20 лет. Я студентка МФТИ-группы 2 курса "Прикладной математики и информатики". Мне нравится получать знания и знакомиться с различными интересными людьми. В свободное от учёбы время люблю проводить время с близкими людьми, смотреть фильмы, читать книги и заниматься творчеством. Раньше я очень хотела пойти на направление, связанное с искусством и литературой, но, к сожалению или счастью, не сложилось. Сейчас я нахожусь в поиске самого лучшего айти-направления для себя.</blockquote>
    </div>
      <script>
        const toggleButton = document.getElementById('toggleButton');
        const info = document.getElementById('info');
        toggleButton.addEventListener('click', () => {
            if (info.style.display === 'none' || info.style.display === '') {
                info.style.display = 'block';
                window.scrollTo({top: info.offsetTop});
            } else {
                info.style.display = 'none';
            }
        });
    </script>
  </body>  
</html>
