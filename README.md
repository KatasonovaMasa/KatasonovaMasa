<h1>Добро пожаловать!</br> 
  Hi there, I'm Mariya <img src="https://github.com/blackcater/blackcater/raw/main/images/Hi.gif" height="32"/></h1>
<h2>Im  QA Engineer:sunglasses:</h2>
<h2> :trophy:  My tools and technology:</h2>

![This is an image](/design/icons/Java.png)![This is an image](/design/icons/Gradle.png)![This is an image](/design/icons/Intelij_IDEA.png)![This is an image](/design/icons/Selenide.png)![This is an image](/design/icons/Selenoid.png)![This is an image](/design/icons/JUnit5.png)![This is an image](/design/icons/Jenkins.png)![This is an image](/design/icons/Allure_Report.png)![This is an image](/design/icons/AllureTestOps.png)![This is an image](/design/icons/Telegram.png)![This is an image](/design/icons/Jira.png)</br>
## :trophy: My education:

|<img width="30%" title="Northwest Public Service Academy" src="/design/icons/cropped-cropped-cropped-site_logo_color_ru.png">|[RANHIGS](https://www.ranepa.ru/)| Manager (2007)|
|:-|:-|:-|
|<img width="20%" title="QAGuru.png" src="design/icons/QAGuru.png">|[qa.guru](https://qa.guru)| <h3>Automation QA Engineer (2023)</h3>|

![Native1331 GitHub stats](https://github-readme-stats.vercel.app/api?username=Native1331)

<h1>:star2: My certificates:</h1></a>
<a href="https://drive.google.com/file/d/12PQPcQSeRExTkMAkppkgnvdqhEJ23U5P/view?usp=sharing"><h2> QA Guru</h2></a>
<a href=""><h2> Software Testing</h2></a>



## Дипломная работа выпускницы школы автотестирования "QA GURU"! <a href="https://github.com/Native1331/HeadHunterTests">Ссылка на проект</a>

# Проект по автоматизации тестирования для  Head Hunter, сайта поиска работодателя и работника	:star2:
## <a target="_blank" href="https://spb.hh.ru/">Веб сайт Head Hunter</a>

![This is an image](design/pictures/hh.jpeg)

## :clipboard:: Содержание:

- <a href="#trophy-технологии-и-инструменты">Технологии и инструменты</a>
- <a href="#heavy_check_mark-реализованные-проверки">Реализованные проверки</a>
- <a href="#clipboard_mark-сборка-в-Jenkins">Сборка в Jenkins</a>
- <a href="#computer-запуск-из-терминала">Запуск из терминала</a>
- <a href="#chart_with_downwards_trend-allure-отчет">Allure отчет</a>
- <a href="#bar_chart-интеграция-с-allure-testops">Интеграция с Allure TestOps</a>
- <a href="#chart_with_upwards_trend-интеграция-с-jira">Интеграция с Jira</a>
- <a href="#iphone-отчет-в-telegram">Отчет в Telegram</a>
- <a href="#movie_camera-видео-примеры-прохождения-тестов">Видео примеры прохождения тестов</a>

## :trophy:Технологии и инструменты

![This is an image](/design/icons/Java.png)![This is an image](/design/icons/Gradle.png)![This is an image](/design/icons/Intelij_IDEA.png)![This is an image](/design/icons/Selenide.png)![This is an image](/design/icons/Selenoid.png)![This is an image](/design/icons/JUnit5.png)![This is an image](/design/icons/Jenkins.png)![This is an image](/design/icons/Allure_Report.png)![This is an image](/design/icons/AllureTestOps.png)![This is an image](/design/icons/Telegram.png)![This is an image](/design/icons/Jira.png)</br>

В данном проекте автотесты написаны на <code>Java</code> с использованием <code>Selenide</code> для UI-тестов.

В качестве библиотеки для модульного тестирования используется <code>JUnit 5</code>.

Для автоматизированной сборки проекта используется <code>Gradle</code>.

<code>Selenoid</code> выполняет запуск браузеров в контейнерах <code>Docker</code>.

<code>Allure Report</code> формирует отчет о запуске тестов.

<code>Jenkins</code> выполняет запуск тестов.

После завершения прогона отправляются уведомления с помощью бота в <code>Telegram</code>.


## 	:heavy_check_mark: Реализованные проверки</br>
Наличия раздела "Сервисы для соискателей" на главной странице</br>
Выбора города (на примере Санкт-Петербурга)</br>
Поиск вакансий "Тестировщик" и "Аналитик"</br>
Поиск вакансии "Тестировщик" и "Аналитик в городе Санкт-Петербурге</br>

## :clipboard: Сборка в Jenkins
### <a target="_blank" href="https://jenkins.autotests.cloud/job/HeadHunter3/">Сборка в Jenkins</a>

![This is an image](design/pictures/jenkins.jpeg)


###  :clipboard: Параметры сборки в Jenkins:
Сборка в Jenkins

- browser (браузер, по умолчанию chrome)
- version (версия браузера, по умолчанию 99.0)
- size (размер окна браузера, по умолчанию 1920x1080)
- threads (количество потоков)
- необходимо добавить файл credentials.properties (содержащий в себе логины и пароли, пример в папке resources)

## :computer: Запуск из терминала
Локальный запуск:
```
gradle clean test
```

Удаленный запуск:
```
clean
test
-Dbrowser=${BROWSER}
-DbrowserVersion=${BROWSER_VERSION} 
-Dsize=${BROWSER_SIZE}
```

## :chart_with_downwards_trend: Allure отчет
- ### Главный экран отчета

![This is an image](design/pictures/allure.jpeg)


- ### Страница с проведенными тестами

![This is an image](design/pictures/allure1.jpeg)

## :bar_chart: Интеграция с Allure TestOps
- ### Экран с результатами запуска тестов

![This is an image](design/pictures/allureTestsOp.jpeg)

- ### Страница с тестами в TestOps

![This is an image](design/pictures/AllureTestOps1.jpeg)

## :chart_with_upwards_trend:	 Интеграция с Jira
- ### Страница с задачей в Jira

![This is an image](design/pictures/jira.jpeg)


## 	:iphone: Отчет в Telegram

![This is an image](design/pictures/telegram.jpeg)


## :movie_camera: Видео примеры прохождения тестов






https://user-images.githubusercontent.com/83497921/180842190-123c8f3d-a1af-4363-aa5b-ef48283e3013.mp4




:heart: <a target="_blank" href="https://qa.guru">qa.guru</a><br/>
:blue_heart: <a target="_blank" href="https://t.me/qa_automation">t.me/qa_automation</a>




  

  
  
