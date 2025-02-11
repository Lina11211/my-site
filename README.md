<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Портфолио - Приют для животных</title>
    <!-- Подключение CSS Bootstrap -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
    <!-- Подключение собственных стилей -->
    <link rel="stylesheet" href="css/тк4.css">
</head>
<body>

    <!-- Шапка сайта (Navbar) -->
    <header>
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <div class="container">
                <!-- Логотип или название сайта -->
                <a class="navbar-brand" href="#">Приют для животных</a>
                <!-- Кнопка для мобильных устройств -->
                <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                    <span class="navbar-toggler-icon"></span>
                </button>
                <!-- Меню навигации -->
                <div class="collapse navbar-collapse" id="navbarNav">
                    <ul class="navbar-nav">
                        <li class="nav-item">
                            <a class="nav-link active" aria-current="page" href="#">Главная</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">О нас</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Животные</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link" href="#">Контакты</a>
                        </li>
                    </ul>
                </div>
            </div>
        </nav>
    </header>

    <!-- Блок контента с приветствием и изображением -->
    <section class="py-5">
        <div class="container text-center">
            <div class="row">
                <!-- Текстовый блок -->
                <div class="col-md-6">
                    <h1>Добро пожаловать в наш приют "Комочек счастья"!</h1>
                    <p>Приют "Комочек счастья"
Приют "Комочек счастья" — это место, где каждый день наполняется любовью и заботой о бездомных животных. Основанный с целью помочь животным, оказавшимся в трудной ситуации, приют стал настоящим домом для многих пушистиков, которые ищут свою семью.
Миссия приюта заключается в том, чтобы предоставить временное убежище, медицинскую помощь и, конечно, заботу. Здесь работают волонтеры, которые с большим энтузиазмом ухаживают за питомцами, обеспечивая им не только физические, но и эмоциональные потребности.
Услуги и программы
В приюте "Комочек счастья" предлагаются различные программы:
Устройство животных в новые семьи: Каждый год приют помогает многим животным найти любящих хозяев.
Волонтерство: Любой желающий может стать волонтером и помочь с уходом за животными.
Образовательные программы: Приют проводит занятия для детей и взрослых, чтобы повысить осведомленность о проблемах бездомных животных и важности ответственного обращения с питомцами.
Как помочь
Если вы хотите поддержать приют, вы можете:
Принести корм или медикаменты.
Сделать финансовый взнос для помощи в лечении и уходе за животными.
Участвовать в акциях по сбору средств и помощи.
Приют "Комочек счастья" — это не просто место для временного проживания животных, это настоящая семья, где каждый питомец чувствует заботу и любовь. Присоединяйтесь к нашей миссии и помогите сделать мир лучше для наших пушистых друзей!</p>
                </div>
                <!-- Изображение -->
                <div class="col-md-6">
                    <img src="https://sun9-74.userapi.com/impg/f6lNdnW_xkmGhWooV0uYMp3GReFsoNqdrOmX5Q/Y86sqFyZwiw.jpg?size=500x500&quality=95&sign=deba11bce6aace04fc1d31f620c8e64f&type=album" class="img-fluid" alt="Приют для животных">
                </div>
            </div>
        </div>
    </section>

    <!-- Секция с каруселью изображений -->
    <section class="py-5">
        <div class="container">
            <div id="carouselExample" class="carousel slide" data-bs-ride="carousel">
                <div class="carousel-inner">
                    <!-- Первый слайд (активный) -->
                    <div class="carousel-item active">
                        <img src="https://img.gazeta.ru/files3/369/14626369/upload-Depositphotos_212586712_XL-pic_32ratio_900x600-900x600-34087.jpg" alt="Котики и собачки">
                    </div>
                    <!-- Второй слайд -->
                    <div class="carousel-item">
                        <img src="https://cdn.culture.ru/images/448c3be3-ce67-5a08-a87b-ed783ba8e540" class="d-block w-100" alt="Домашние животные">
                    </div>
                    <!-- Третий слайд -->
                    <div class="carousel-item">
                        <img src="https://image.winudf.com/v2/image1/Y29tLlB1cHBpZXNMaXZlV2FsbHBhcGVySERIUV9zY3JlZW5fM18xNTY2OTk1ODY1XzA5NQ/screen-3.jpg?fakeurl=1&type=.jpg="Собака">
                    </div>
                </div>
                <!-- Кнопки управления каруселью -->
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
                    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Предыдущий</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
                    <span class="carousel-control-next-icon" aria-hidden="true"></span>
                    <span class="visually-hidden">Следующий</span>
                </button>
            </div>
        </div>
    </section>

    <!-- Секция с карточками животных -->
    <section class="py-5">
        <div class="container">
            <div class="row">
                <!-- Карточка 1 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://i.pinimg.com/736x/bb/ec/0d/bbec0d29972b47c83f1dae4207741c74.jpg" class="card-img-top" alt="Котенок">
                        <div class="card-body">
                            <h5 class="card-title">Милка</h5>
                            <p class="card-text">Ласковый и игривый котенок.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
                <!-- Карточка 2 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://avatars.mds.yandex.net/get-znatoki/1506847/2a000001833b9a157d1edf27184a0086fa54/orig" class="card-img-top" alt="Собака">
                        <div class="card-body">
                            <h5 class="card-title">Шеги</h5>
                            <p class="card-text">Дружелюная собака.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
                <!-- Карточка 3 -->
                <div class="col-md-4">
                    <div class="card">
                        <img src="https://avatars.mds.yandex.net/i?id=c8484a6baf03dd3031a9d77eaaf83d8a_l-5236455-images-thumbs&n=13" class="card-img-top" alt="Кролик">
                        <div class="card-body">
                            <h5 class="card-title">Харми</h5>
                            <p class="card-text">Спокойный сторожевой пес.</p>
                            <a href="#" class="btn btn-primary">Подробнее</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Секция с формой для связи -->
    <section class="py-5">
        <div class="container">
            <h2>Свяжитесь с нами</h2>
            <form>
                <!-- Поле для имени -->
                <div class="mb-3">
                    <label for="name" class="form-label">Ваше имя</label>
                    <input type="text" class="form-control" id="name">
                </div>
                <!-- Поле для email -->
                <div class="mb-3">
                    <label for="email" class="form-label">Ваш email</label>
                    <input type="email" class="form-control" id="email">
                </div>
                <!-- Поле для сообщения -->
                <div class="mb-3">
                    <label for="message" class="form-label">Сообщение</label>
                    <textarea class="form-control" id="message" rows="3"></textarea>
                </div>
                <!-- Кнопка отправки формы -->
                <button type="submit" class="btn btn-primary">Отправить</button>
            </form>
        </div>
    </section>

    <!-- Подвал сайта -->
    <footer class="bg-light py-4">
        <div class="container text-center">
            <p>Адрес: ул. Московское шоссе, д. 120</p>
            <p>Телефон: +7 (937) 999-00-99</p>
            <p>Email: info@mail.ru</p>
        </div>
    </footer>

    <!-- Подключение JS Bootstrap -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
