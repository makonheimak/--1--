## index.html (Главная)

html:5>body#top>header.header>h1.logo{Докучаевск}+nav.nav>ul>li*6>a[href="index.html"]{Item$}+main.main.home-page>section.hero>h2{Общее описание города}+p.hero-text+aside.promo[aria-label="Важная информация"]>h3+p+address+article.featured>h2+dl>dt*2+dd*2+blockquote>cite+section.gallery-section>h2+div.gallery-grid>figure.gallery-item*5>img+figcaption+section.news-section>h2+div.news-list>article.news-item*3>h3+time+p+footer.footer>p

## about.html (О разработчике)

html:5>body>header>h1{О разработчике}+nav.nav>ul>li*6>a{...}+main.about-page>h2{Информация о разработчике}+section.profile>div.profile-photo>img[alt="Фото разработчика"]+div.profile-info>h2+div.bio>h3+p+div.contacts>h3+p+section.skills>h2+div.skill*5>label+progress

## history.html (История)

html:5>body>header>h1{История}+nav.nav>ul>li*6>a+main>h2{Хронология важнейших событий}+p.intro+div.table-wrap>table.timeline>caption+thead>tr>th*3+tbody>tr*10>td*3+section.history-details>h3>details*4>summary+p+footer>p

## infrastructure.html (Инфраструктура)

html:5>body>header>h1{Инфраструктура}+nav.nav>ul>li*6>a+main>h2{Географическое положение}+p.geo+section.map-section>h3+p.muted+div.map-wrapper>iframe+section.admin-division>h3+p+section.transport>h3+p+h4+div.table-wrap>table.transport-table>caption+thead>tr>th*7+tbody>tr*12>td*7+section.transport-details>h4>details*3+footer>p

## culture.html (Культура)

html:5>body>header>h1{Культура}+nav.nav>ul>li*6>a+main>section.intro>h2+p+section.culture-block.theaters>h3+p.places+ul.places-list>li*3>h4+p+section.culture-block.museums>h3+p+section.culture-block.festivals>h3+ul.places-list>li*2+section.culture-block.figures>h3+div.figures-grid>article.figure-card*3>img+div.figure-card-body>h4+p.role+p.bio+footer>p

## contact.html (Контакты)

html:5>body>header>h1{Контакты}+nav.nav>ul>li*6>a+main>h2{Форма обратной связи}+form#contact(action="mailto:you@example.com" method="post" enctype="text/plain")>fieldset>legend{Отправить сообщение}+label[for=name]+input#name[type=text required]+label[for=email]+input#email[type=email required]+label[for=subject]+input#subject[list=subjects]+datalist#subjects>option*4+label[for=message]+textarea#message+button[type=submit]{Отправить}+output#result+address>p*2+footer>p
