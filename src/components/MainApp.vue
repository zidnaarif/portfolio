<template>
        <!--=============== HEADER PROFILE ===============-->
        <header class="profile container">
            <!-- theme -->
            <i class="ri-moon-line change-theme" id="theme-button"></i>

            <div class="profile__container grid">
                <div class="profile__data">
                    <div class="profile__border">
                        <div class="profile__perfil">
                            <img src="/assets/img/perfil.png" alt="">
                        </div>
                    </div>

                    <h2 class="profile__name">Muh. Zidna Arif A.</h2>
                    <h3 class="profile__profession">Digital Marketing Enthusiast & Web Developer</h3>
                    
                    <ul class="profile__social">
                        <a href="https://linkedin.com/in/zidna-arif" target="_blank" class="profile__social-link">
                            <i class="ri-linkedin-box-line"></i>
                        </a>
                        <a href="https://github.com/zidnaarif" target="_blank" class="profile__social-link">
                            <i class="ri-github-fill"></i>
                        </a>
                        <a href="https://instagram.com/zidna.arif" target="_blank" class="profile__social-link">
                            <i class="ri-instagram-line"></i>
                        </a>
                    </ul>
                </div>

                <div class="profile__info grid">
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">28</h3>
                        <p class="profile__info-description">Years <br> old</p>
                    </div>
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">+6</h3>
                        <p class="profile__info-description">Completed <br> projects</p>
                    </div>
                    <div class="profile__info-group">
                        <h3 class="profile__info-number">4</h3>
                        <p class="profile__info-description">Active <br> courses</p>
                    </div>
                </div>

                <div class="profile__buttons">
                    <a download="" href="https://drive.google.com/file/d/1uexQ6qSvnTqionPJGnhazfnX_IF2hsdN/view?usp=sharing" class="button button__small">
                        Download CV <i class="ri-download-line"></i>
                    </a>

                    <div class="profile__buttons-small">
                        <a href="https://api.whatsapp.com/send?phone=6285780007158&text=Hello, Zidna." target="_blank" class="button button__small button__gray">
                            <i class="ri-whatsapp-line"></i>
                        </a>

                        <a href="mailto:zidna.arif@gmail.com" target="_blank" class="button button__small button__gray">
                            <i class="ri-mail-send-line"></i>
                        </a>
                    </div>
                </div>

            </div>
        </header>

        <!--=============== MAIN ===============-->
        <main class="main">
            <section class="filters container">
                <!--=============== FILTERS TABS ===============-->
                <ul class="filters__content">
                    <button class="filters__button filter-tab-active" data-target="#projects">
                        Projects
                    </button>

                    <button class="filters__button" data-target="#skills">
                        Skills
                    </button>
                </ul>

                <div class="filters__sections">
                    <!--=============== PROJECTS ===============-->
                    <div class="projects__content grid filters__active" data-content id="projects">
                        <article class="projects__card">
                            <img src="/assets/img/project-seo.jpg" alt="" class="projects__img">
                            
                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Ragasport.id</span>
                                    <h3 class="projects__title">SEO & SEM</h3>
                                    <a href="https://ragasport.id" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                </div>
                            </div>
                        </article>
                        <article class="projects__card">
                            <img src="/assets/img/project-vue.jpg" alt="" class="projects__img">
                            
                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Dekoruma</span>
                                    <h3 class="projects__title">Vue.js Single Page App</h3>
                                    <a href="http://dekoruma.zidna.my.id" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                    <a href="https://github.com/zidnaarif/148_WPA_zidna" class="projects__button button button__small">
                                        <i class="ri-github-fill"></i>
                                    </a>
                                </div>
                            </div>
                        </article>
                        <article class="projects__card">
                            <img src="/assets/img/project-html.jpg" alt="" class="projects__img">
                            
                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">WeFix.</span>
                                    <h3 class="projects__title">HTML & CSS Website</h3>
                                    <a href="http://wefix.zidna.my.id" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                    <a href="https://github.com/zidnaarif/dicoding-html" class="projects__button button button__small">
                                        <i class="ri-github-fill"></i>
                                    </a>
                                </div>
                            </div>
                        </article>
                        <article class="projects__card">
                            <img src="/assets/img/project-blog.jpg" alt="" class="projects__img">
                            
                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Droidtube.com</span>
                                    <h3 class="projects__title">Blogger Website</h3>
                                    <a href="http://droidtube.com" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                    <a href="#" class="projects__button button button__small">
                                        <i class="ri-github-fill"></i>
                                    </a>
                                </div>
                            </div>
                        </article>
                        <article class="projects__card">
                            <img src="/assets/img/project-bootstrap.jpg" alt="" class="projects__img">
                            
                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">Company Profile</span>
                                    <h3 class="projects__title">Bootstrap 5.2 Web</h3>
                                    <a href="http://bootstrap.zidna.my.id" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                    <a href="https://github.com/zidnaarif/bootstrap-company-profile" class="projects__button button button__small">
                                        <i class="ri-github-fill"></i>
                                    </a>
                                </div>
                            </div>
                        </article>
                        <article class="projects__card">
                            <img src="/assets/img/project-port.jpg" alt="" class="projects__img">
                            
                            <div class="projects__modal">
                                <div>
                                    <span class="projects__subtitle">My Portfolio</span>
                                    <h3 class="projects__title">Portfolio Website</h3>
                                    <a href="http://zidna.my.id" class="projects__button button button__small">
                                        <i class="ri-link"></i>
                                    </a>
                                    <a href="https://github.com/zidnaarif/portfolio" class="projects__button button button__small">
                                        <i class="ri-github-fill"></i>
                                    </a>
                                </div>
                            </div>
                        </article>
                    </div>

                    <!--=============== SKILLS ===============-->
                    <div class="skills__content grid" data-content id="skills">
                        <div class="skills__area">
                            <h3 class="skills__title">
                                Digital Marketing
                            </h3>

                            <div class="skills__box">
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Search Engine Optimization</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Google Ads</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                    
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Google Analytics</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>

                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Google Tag Manager</h3>
                                            <span class="skills__level">Advanced</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Google Search Console</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">SEO Tools (Semrush, Ubbersuggest, Screepy)</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="skills__area">
                            <h3 class="skills__title">
                                Frontend Developer
                            </h3>

                            <div class="skills__box">
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">HTML</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">CSS</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                    
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Javascript</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>
                                </div>

                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Vue</h3>
                                            <span class="skills__level">Basic</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">React</h3>
                                            <span class="skills__level">Beginner</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Bootstrap</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                        <div class="skills__area">
                            <h3 class="skills__title">
                                Backend Developer
                            </h3>

                            <div class="skills__box">
                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">PHP</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>

                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">MySQL</h3>
                                            <span class="skills__level">Advanced</span>
                                        </div>
                                    </div>
                                </div>

                                <div class="skills__group">
                                    <div class="skills__data">
                                        <i class="ri-checkbox-circle-line"></i>

                                        <div>
                                            <h3 class="skills__name">Delphi</h3>
                                            <span class="skills__level">Intermediate</span>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </section>
        </main>

        <!--=============== FOOTER ===============-->
        <footer class="footer container">
            <span class="footer__copy">
                &#169; Zidna Arif. All rights reserved.
            </span>            
        </footer>

</template>