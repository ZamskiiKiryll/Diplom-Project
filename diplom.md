            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
                <title></title>
                <style>
                *{
                    margin: 0px;
                    padding: 0px;
                    font-family:"Roboto";
                }
                body{
                    max-width: 1280px;
                    margin: auto;
                }
               
                .size{
                    margin: auto;
                    max-width: 1080px;
                }
                .size2{
                    margin: auto;
                    max-width:880px ;
                }
                .logo{
                    padding: 0px;
                }
                .head {
                    padding-top: 15px;
                    display: flex;
                    justify-content:space-between;
                }
                ul{
                    display: flex;
                    list-style-type: none;
                } 
                li a {
                    text-decoration: none;
                    color: black;
                }
                li a:hover{
                    color:#009ccc;
                    text-decoration: none;
                }
                li {
                    margin: 0px 15px;
                    line-height: 40px;
                }
                .art2 a{
                    text-decoration: none;
                }
                .dipl {
                    background-image: url(Слой21.png);
                    background-repeat: no-repeat;
                    background-position:right;
                    background-size:contain;
                }
                .art1{
                    margin: 5px;
                    padding: 25px 0px;
                }
                .dipl {
                    margin: 0px;
                    padding: 40px 0px 15px 0px;
                }
            
                .but1,
                .but2,
                .but3
                    {
                    outline: none;
                    background-color:#009ccc;
                    font-size: 14px;
                    color: white;
                    font-weight: 400;
                    text-align: center;
                }
                .but1:hover,
                .but2:hover,
                .but3:hover{
                    background-color:white;
                    color:#009ccc;
                   
                }
                .but1{
                    width: 115px;
                    height: 35px;
                }
                .but2{
                    width: 185px;
                    height: 35px;
                }
                .but3{ 
                    width: 115px;
                    height: 30px;
                    border-radius: 3px;
                    text-align: center;
                }
                .diplom{
                    background-image: url(dip.png);
                    background-repeat: no-repeat;
                    background-size: cover;
                }
                .sprav{
                    background-image: url(sprav.png);
                    background-size: cover;
                    background-repeat: no-repeat;   
                }
                .svidet{
                    background-image: url(svidet.png);
                    background-size: cover;
                    background-repeat: no-repeat;    
                }
                .atest{
                    background-image: url(atest.png);
                    background-size: cover;
                    background-repeat: no-repeat; 
                }
                
              
                .diplom:hover,
                .svidet:hover,
                .sprav:hover,
                .atest:hover {
                    transform: scale(1.3);
                }
                h1{
                    font-size: 24px;
                    color:#231f20;
                    font-weight: 400;
                    text-align: left;
                }
                .zak p {
                    font-size: 14px;
                    line-height: 18px;
                    color: #231f20;
                    font-weight: 400;
                    padding: 0px;
                }
                .art2 p {
                    line-height: 150px;
                    font-size: 30px;
                    color:#ffffff;
                    font-weight: 400;
                    text-align: center;
                }
                .img p {
                    font-size: 14px;
                    color:black;
                    
                    font-weight: 400;
                    text-align: center;
                    padding-top: 5px;
                }
                .img {
                    text-align: center;
                }
                .art4 p{
                    font-size: 14px;
                    color:#252122;
                    
                    font-weight: 400;
                }
                .art4 h2{
                    font-size: 30px;
                    color: #009ccc;
                    font-weight: 400;
                    text-align: center;
                }
                .art3 {
                    text-align: center;
                    margin: 5px;
                    padding: 50px 0px;
                }
                .art3 h2{
                    font-size: 30px;
                    color: #231f20;
                    font-weight: 700;
                    text-align: center;
                }
                .otzyv p{
                    font-size: 14px;
                    color: #000000;
                    font-weight: 400;
                    text-align: left;
                }
                #ns{
                    font-size: 14px;
                    color: #000000;
                    font-weight: 700;
                    text-align: left;
                    margin: 0px;
                }
                #dol{
                    font-size: 14px;
                    line-height: 14px;
                    color: #000000;
                    font-weight: 400;
                    text-align: left;
                }
                footer{
                    background-color: rgb(219, 217, 217);
                }
                footer p {
                    padding: 15px 0px 15px 35px;
                    font-size: 14px;
                    line-height: 18px;
                    color: #000000;
                    font-weight: 400;
                }
                .imgleft {
                    text-align: right;
                    margin-top: 50px;
                    padding-right: 60px;
                }
                .imgright {
                    text-align: left;
                    margin-top: 50px;
                    padding-left: 60px;
                }
                .zak{
                    padding: 0px;
                }
                .art2 {
                    margin: 25px 0px;
                    padding: 25px 0px;
                    padding-right: 0px;
                    padding-left: 15px;

                }
                @media (max-width: 980px) {
                    .dipl{
                        background-image:none;
                    }
                    .zak {
                        text-align:center;
                    }
                    h1 {
                        text-align:center;
                    }
                    body{
                    max-width: 980px;
                    margin: auto;
                     }
                    .size{
                    margin: auto;
                    max-width: 980px;
                }

                </style>
            </head>
            <body>
                <header class="size">
                    <div class="head">
                        <div class="logo">
                            <img src="лого.png" alt="лого">
                        </div>
                        <nav class="navigation">
                            <ul>
                                <li> <a href="#"> Документы </a> </li>
                                <li> <a href="#"> Цены</a></li>
                                <li> <a href="#"> Доставка</a></li>
                                <li> <a href="#"> Отзывы</a> </li>
                                <li> <a href="#"> Гаратнии</a> </li>
                                <li> <a href="#"> Контакты </a> </li>
                            </ul>
                        </nav>
                        <button class="but1">Заказать</button>
                    </div>
                </header>
                <section class="contanier size">
                    <div class="row dipl">
                        <div class=" col-lg-6 col-md-12 zak">
                            <h1>ЗАКАЖИ ДИПЛОМ НЕДОРОГО!</h1>
                            <p>Граждане часто сталкиваются с необходимостью в наличии диплома определенной специальности при устройстве на работу. Обучение в ВУЗе требует больших финансовых и временных затрат. 
                                Решением проблемы станет приобретение документа. Узнавая, где можно купить диплом, обратите внимание на нашу компанию. Она заслужила доверие клиентов благодаря качественному предоставлению услуг.
                            </p>
                            <button class="but2"> Подробнее </button>
                        </div>
                    </div>
                </section>
    
                <section class="contanier size">
                    <div class="row art1">
                        <div class="col-lg-3 col-md-6 img">
                            <img src="Слой 13.png" alt="Орден">
                            <p> ГОСЗНАК</p>
                        </div>
                        <div class="col-lg-3 col-md-6 img">
                            <img src="Слой 14.png" alt="Отлично">
                            <p> ГАРАНТИРОВАННОЕ <br> КАЧЕСТВО</p>
                        </div>
                        <div class="col-lg-3 col-md-6  img">
                            <img src="Слой 17.png" alt="Почта">
                            <p> ДОСТАВКА <br> ПО РОССИИ И СНГ</p>
                        </div>
                        <div class="col-lg-3 col-md-6 img">
                            <img src="hand.png" alt="hand">
                            <p>ВЫГОДНО</p>
                        </div>
                    </div>
                </section>
                <section class="contanier size">
                    <div class="row art2">
                        <div class="col-lg-6 col-md-12">
                            <div class="diplom"
                                <a href="#">
                                <p> ДИПЛОМЫ</p>
                                </a>
                            </div>
                        </div>
                        <div class="col-lg-6 col-md-12">
                           <div class="sprav"> 
                                <a href="#">
                                    <p>СПРАВКИ</p>
                                </a>
                            </div>
                        </div>
                        <div class="col-lg-6 col-md-12 ">
                            <div class="svidet">   
                                <a href="#">
                                    <p> СВИДЕТЕЛЬСТВА</p>
                                </a>
                            </div>
                        </div>   
                        <div class="col-lg-6 col-md-12">
                                <div Class="atest">
                                    <a href="#">
                                        <p> АТТЕСТАТЫ</p>
                                </a>
                                </div>
                        </div>
                    </div>
                </section>
                <section class=" contanier size">
                    <div class="art3">
                        <h2> ОТЗЫВЫ О НАС </h2>
                            <div class="row">
                                <div class="col-3 imgleft">
                                    <img src="left.png" alt="left">
                                </div>
                            <div class="col-6 otzyv">
                        
                            <p>Это развивающийся портал контентного наполнения сайтов. Карьерный рост здесь –  престижно для многих копирайтеров и заказчиков. Компания проводит постоянный мониторинг сайтов -конкурентов, а потому
                                динамично развивается с введением чего-то нового, но уже востребованного. 
                            </p>
                            <p>Пока спектр услуг здесь не очень широк – биржи копирайтинга и рерайтинга, магазин статей и новостей – но сайт обещает не останавливаться на достигнутом, а прогрессировать семимильными шагами.
                            </p>
                            <p id="ns"> Иванов Петр Васильевич </p>
                            <p id="dol">Генеральный директор </p>
                            </div>
                                <div class=" col-3 imgright">
                                    <img src="right.png" alt="right">
                                </div>
                            </div>
                            <button class="but3"> ВСЕ ОТЗЫВЫ </button>
                    
                    </div>
                </section>
                <section class="size2">
                    <div class="art4">
                        <h2> ДОКУМЕНТЫ О ВЫСШЕМ ОБРАЗОВАНИИ</h2>
                        <P>В наши дни трудоустройство на любую солидную работу невозможно без ряда соответствующих документов. Среди них документ, подтверждающий высшее образование с уверенностью можно считать главным – именно он позволяет вам работать по определенной специальности и получать соответствующую зарплату. 
                            Жизнь может подкинуть довольно неприятные сюрпризы – например, отчисление с последнего курса или банальную утерю диплома по неосторожности. Восстановить документ вполне реально, но подобная процедура может занять много времени, а порой и денег – просто так уже давно ничего не делается. Все это делает предложения организаций, которые предлагают своим клиентам документы о высшем образовании, очень и очень востребованными. Ведь в наши дни опыт работы решает куда как больше, чем какая-то бумажка, но именно её отсутствие может стать для многих непреодолимой преградой. К счастью, устранить подобную неприятность довольно просто – обратитесь к нам.
                        </P>
                        <p>Множество компаний во всех крупных городах предлагают услуги подобного рода – и столица не исключение. Любые документы о высшем образовании купить в Москве довольно просто – глаза разбегаются от тематических объявлений, как в реальной жизни, так и в Сети. Но не спешите обращаться в первую попавшуюся контору – качество приобретенных дипломов, свидетельств и аттестатов у большинства из них довольно низкое. Заказывать подобные документы нужно у надежной и проверенной временем организации, которая гарантирует качественный результат в оформлении документов любого уровня сложности.
                        </p>
                    </div>
                </section>
                <footer >
                    <p> &copy ООО Дипломзагод <br>
                        +7 (3952) 758-198, info@gmail.com</p>
                </footer>

            </body>
            </html>
