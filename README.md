# goiteens-homework-last-adaptive
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WEB studio</title>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@700&family=Roboto:wght@400;500;700;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="node_modules/modern-normalize/modern-normalize.css">    
    <!-- Зовнішній файл стилю -->
    <link rel="stylesheet" href="./css/main.min.css">
</head>
<body>
    <!-- Шапка -->
    <header>
        <div class="container header-nav ">
            <a class="logo" href="./"><span>Web</span>Studio</a>
            <!-- Кнопка мобільного меню -->
            <button 
                    type="button" 
                    class="mobile-button" 
                    data-menu-button 
                    aria-expanded="false">
                <svg width="40" 
                    height="40" 
                    aria-label="Перекмикач мобільного меню">
                    <use class="mobile-close" href="./img/symbol-defs.svg#close40px"></use>
                    <use class="mobile-open" href="./img/symbol-defs.svg#menu40px"></use>
                </svg>
            </button>
    
            <div class="mobile-menu" id="mobile-menu" data-menu>
                <div>
                    <nav class="navigation">             
                    <ul class="nav-list">               
                        <li class="list-item"><a class="link current" href="./">Студія</a></li>
                        <li class="list-item"><a class="link" href="./portfolio.html" target="_blank" rel="noopener noreferer">Портфоліо</a></li>
                        <li class="list-item"><a class="link" href="">Контакти</a></li>
                    </ul> 
                    </nav>
            </div>
                <div>
                    <div class="contacts">
                        <ul class="contacts-list">
                    <li class="contacts-item">
                        <a class="contacts-link" href="mailto:info@devstudio.com">
                            <svg class="contact-icon" width="16" height="12">
                                <use href="./img/symbol-defs.svg#icon-email" ></use>
                            </svg>                
                        info@devstudio.com
                        </a>
                    </li>
                    <li class="contacts-item"><a class="contacts-link" href="tel:+380961111111">
                        <svg class="contact-icon" width="10" height="16">
                            <use href="./img/symbol-defs.svg#icon-phonen"></use>
                        </svg>
                        +38 096 111 11 11</a></li>
                        </ul>
                    </div>
                    <ul class="networks-list">
                        <li class="networks-item">
                            <a href="" rel="noopener, noreferrer" class="networks-link">
                                Instagram
                            </a>
                        </li>
                        <li class="networks-item">
                            <a href="" rel="noopener, noreferrer" class="networks-link">
                                Twitter
                            </a>
                        </li>
                        <li class="networks-item">
                            <a href="" rel="noopener, noreferrer" class="networks-link">
                                Facebook
                            </a>
                        </li>
                        <li class="networks-item">
                            <a href="" rel="noopener, noreferrer" class="networks-link">
                                Linkedin
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
        </header>
    <!-- Основна секція -->
    <main>
    <!-- Секція герой -->
        <section class="hero">
            <div class="container">
                <h1 class="hero-title">ефективні рішення для                     
                </br> 
                вашого бізнесу
                </h1>
            <button type="button" class="hero-button" data-modal-open>Замовити послугу</button>
            </div>
            <!-- Модальне вікно -->
            <div class="backdrop is-hidden" data-modal>
                <div class="modal">
                    <button type="button" class="modal-button" data-modal-close></button>
                    <!-- Форма модального вікна -->
                    <form class="form js-speaker-form" autocomplete="on">
                        <h3 class="title">Залиште свої дані, ми Вам зателефонуємо</h3>
                        <ul class="fields">
                            <li class="field">
                                <label for="user-name">Ім'я</label>
                                    <input 
                                        class="form-field" 
                                        type="text" 
                                        name="user-name" 
                                        id="user-name" >
                                <svg class="form-icon" width="18" height="18">
                                    <use href="./img/icons/"></use>
                                </svg>
                            </li>
                            <li class="field">
                                <label for="user-tel">Телефон</label>
                                    <input 
                                        class="form-field" 
                                        type="tel" 
                                        name="user-tel" 
                                        id="user-tel" 
                                        autofocus >        
                                <svg class="form-icon" width="18" height="18">
                                    <use href="./img/symbol-defs.svg#icon-phonen"></use>
                                </svg>
                            </li>
                            <li class="field">
                                <label for="user-mail">Пошта</label>
                                    <input 
                                        class="form-field" 
                                        type="email" 
                                        name="user-mail" 
                                        id="user-mail">
                                <svg width="18" height="18" class="form-icon">
                                    <use href="./img/symbol-defs.svg#icon-email"></use>
                                </svg>
                            </li>
                            <li class="field">
                                <label for="comments">Коментарі</label>
                                    <textarea 
                                        class="textarea" 
                                        name="comments" 
                                        id="comments"
                                        rows="10" 
                                        placeholder="Введіть коментар">
                            </textarea>
                            </li>
                        </ul>
                        <div class="checkbox">
                            <label class="field-label" for="checkbox">
                                <input class="field-checkbox" type="checkbox" name="checkbox" id="checkbox" value="checkbox"/>
                                <svg class="checkbox-icon" width="16" height="15">
                                    <use href="./img/icons/close_40px.svg"></use>
                                </svg>
                                Погоджуюсь з розсилкою і приймаю 
                               <a href="./" >Умови договору</a> 
                            </label>
                        </div>
                            
                            <button type="submit" class="hero-button btn">Надіслати</button>
                    
                    </form>
                </div>
            </div>
        </section>
        
            <section class="section">
            <div class="container">
                <h2 class="visually-hidden">Особливості</h2>
            <ul class="features">
                <li class="features-item">
                    <div class="features-icon">
                        <svg  class="icon" width="65" height="70">
                        <use href="./img/icons.svg#icon-Vector-1"></use>
                    </svg>
                    </div>
                    <h3 class="title ">УВАГА ДО ДЕТАЛЕЙ</h3>
                    <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, a nemo perferendis quia accusamus temporibus repellat sequi architecto, et fugit in similique nam ipsa adipisci quae rerum quo tempora illo!</p>
                </li>
                <li class="features-item">
                    <div class="features-icon">
                        <svg  class="icon"width="65" height="70">
                        <use href="./img/icons.svg#icon-Clock"></use>
                    </svg>
                    </div>
                    <h3 class="title">ПУНКТУАЛЬНІСТЬ</h3>
                    <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, a nemo perferendis quia accusamus temporibus repellat sequi architecto, et fugit in similique nam ipsa adipisci quae rerum quo tempora illo!</p>
                </li>
                <li class="features-item">
                    <div class="features-icon">
                        <svg class="icon" width="70" height="53">
                        <use href="./img/icons.svg#icon-diagram"></use>
                    </svg>
                    </div>
                    <h3 class="title">ПЛАНУВАННЯ</h3>
                    <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, a nemo perferendis quia accusamus temporibus repellat sequi architecto, et fugit in similique nam ipsa adipisci quae rerum quo tempora illo!</p>
                </li>
                <li class="features-item">
                    <div class="features-icon">
                        <svg class="icon" width="55" height="60">
                        <use href="./img/icons.svg#icon-astronaut"></use>
                    </svg>
                    </div>
                    <h3 class="title">СУЧАСНІ ТЕХНОЛОГІЇ</h3>
                    <p class="text">Lorem ipsum dolor sit amet consectetur adipisicing elit. Officiis, a nemo perferendis quia accusamus temporibus repellat sequi architecto, et fugit in similique nam ipsa adipisci quae rerum quo tempora illo!</p>
                </li>                
            </ul>
            </div>
        </section>
    <!-- Секція наша команда -->
        <section class="section our-team">
            <div class="container">
                <h2 class="section-title">Наша команда</h2>
            <ul class="team">
                <li class="team-link">
                    <img src="./img/Ігор Демяненко.jpg" alt="Дем'яненко Шгор">
                    <p class="name">Ігор Дем’яненко</p>
                    <p class="position">Product Designer</p>
                    <ul class="social-network-list">
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-instagram-2"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li  class="network-item">
                            <a class="social-link" href="" >
                                <svg class="social-icon" width="20" height="16">
                                        <use href="./img/symbol-defs.svg#icon-Group"></use>
                                    </svg> 
                                </a> 
                            </li>
                        <li  class="network-item" > 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-facebook-1"></use></svg>
                                 </a> 
                                </li>
                        <li  class="network-item" > 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-linkedin-1--"></use></svg> 
                                    </a> 
                    </ul>
                
                <li class="team-link">
                    <img src="./img/Ольга Репіна.jpg" alt="Ольга Репіна">
                    <p class="name">Ольга Репіна</p>
                    <p class="position">Frontend Developer</p>
                    <ul class="social-network-list">
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-instagram-2"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="16">
                                    <use href="./img/symbol-defs.svg#icon-Group"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-facebook-1"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-linkedin-1--"></use>
                                </svg> 
                            </a> 
                        </li>
                    </ul>
                </li>
                <li class="team-link">
                    <img src="./img/Микола Тарасов.jpg" alt="Микола Тарасов">
                    <p class="name">Микола Тарасов</p>
                    <p class="position">Marketing</p>
                    <ul class="social-network-list">
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-instagram-2"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="16">
                                    <use href="./img/symbol-defs.svg#icon-Group"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-facebook-1"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-linkedin-1--"></use>
                                </svg> 
                            </a> 
                        </li>
                    </ul>
                </li>
                <li class="team-link">
                    <img src="./img/Микола Єрмаков.jpg" alt="Михайло Єрмаков">
                    <p class="name">Михайло Єрмаков</p>
                    <p class="position">UI Designer</p>
                    <ul class="social-network-list">
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-instagram-2"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="16">
                                    <use href="./img/symbol-defs.svg#icon-Group"></use>
                                     </svg>
                                     </a>
                                    </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-facebook-1"></use>
                                </svg> 
                            </a> 
                        </li>
                        <li class="network-item"> 
                            <a class="social-link" href=""> 
                                <svg class="social-icon" width="20" height="20">
                                    <use href="./img/symbol-defs.svg#icon-linkedin-1--"></use>
                                </svg> 
                            </a> 
                        </li>
                    </ul>
                </li>
            </ul>
            </div>
        </section>   
        <!-- Постійні клієнти -->
        <section class="section">
            <div class="container">
                <h2 class="section-title">Постійні клієнти</h2>
                <ul class="customers">
                    <li class="customers-item">
                        <a href="" class="customers-link">
                            <svg class="customers-icon" width="440" height="490">
                                <use href="./img/symbol-defs.svg#icon-Client-1"></use>    
                            </svg>
                        </a>
                    </li>
                    <li class="customers-item">
                        <a href="" class="customers-link">
                            <svg class="customers-icon" width="400" height="520">
                                <use href="./img/symbol-defs.svg#icon-Client-2"></use>    
                            </svg>
                        </a>
                    </li>
                    <li class="customers-item">
                        <a href="" class="customers-link">
                            <svg class="customers-icon" width="410" height="420">
                                <use href="./img/symbol-defs.svg#icon-Client-3"></use>    
                            </svg>
                        </a>
                    </li>
                    <li class="customers-item">
                        <a href="" class="customers-link">
                            <svg class="customers-icon" width="790" height="420">
                                <use href="./img/symbol-defs.svg#icon-Client-4"></use>    
                            </svg>
                        </a>
                    </li>
                    <li class="customers-item">
                        <a href="" class="customers-link">
                            <svg class="customers-icon" width="590" height="470">
                                <use href="./img/symbol-defs.svg#icon-Client-5"></use>    
                            </svg>
                        </a>
                    </li>
                    <li class="customers-item">
                        <a href="" class="customers-link">
                            <svg class="customers-icon" width="880" height="450">
                                <use href="./img/symbol-defs.svg#icon-Client-6"></use>    
                            </svg>
                        </a>
                    </li>
                </ul>
           </div>
        </section>     
    </main>
        <!-- Футер -->
        <footer class="footer">
            <div class="container footer-container">
                <!-- Лого та контакти -->
                <div class="footer-contacts">
                <a class="footer-logo" href=""><span>Web</span>Studio</a>
                    <addres class="addres">
                                <p class="footer-address">м. Київ, пр-т Лесі Українки, 26</p>
                            <ul class="footer-contacts">
                                <li class="link"><a class="footer-contacts-link" href="mailto:info@devstudio.com">info@devstudio.com</a></li>
                                <li class="link"><a class="footer-contacts-link" href="tel:+380961111111">+38 096 111 11 11</a></li>
                            </ul>
                    </addres>
            </div>
            <!-- Приєднуйтесь -->
            <div class="join">
                <b class="join-networks">Приєднуйтесь</b>
                <ul class="social-network-list">
                    <li class="network-item"> 
                        <a class="social-link" href=""> 
                            <svg class="social-icon" width="20" height="20">
                                <use href="./img/symbol-defs.svg#icon-instagram-2"></use>
                            </svg> 
                        </a> 
                    </li>
                    <li  class="network-item">
                        <a class="social-link" href="" >
                            <svg class="social-icon" width="20" height="16">
                                    <use href="./img/symbol-defs.svg#icon-Group"></use>
                                </svg> 
                            </a> 
                        </li>
                    <li  class="network-item" > 
                        <a class="social-link" href=""> 
                            <svg class="social-icon" width="20" height="20">
                                <use href="./img/symbol-defs.svg#icon-facebook-1"></use></svg>
                             </a> 
                            </li>
                    <li  class="network-item" > 
                        <a class="social-link" href=""> 
                            <svg class="social-icon" width="20" height="20">
                                <use href="./img/symbol-defs.svg#icon-linkedin-1--"></use></svg> 
                                </a> 
                </ul>
            </div>
        </div>
</footer>
<script src="/form.js" type="module"></script>
<script src="./modal.js" type="module"></script>
<script src="./mobile-menu.js" type="module"></script>
</body>
</html>