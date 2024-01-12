<!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">

        <!--========== BOX ICONS ==========-->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/boxicons@latest/css/boxicons.min.css">

        <!--========== CSS ==========-->
        <link rel="stylesheet" href="assets/css/styles.css">

        <title>Responsive resume cv</title>
    </head>
    <body>
        <!--========== HEADER ==========-->
        <header class="l-header" id="header">
            <nav class="nav db-container">
                <a href="#" class="nav__logo">Dervieux</a>

                <div class="nav__menu" id="nav-menu">
                    <ul class="nav__list">

                        <li class="class__item">
                            <a href="#home" class="nav__link">
                                <i class="bx bx-home-alt nav__icon"></i>Acceuil
                            </a>
                        </li>

                        <li class="class__item">
                            <a href="#profile" class="nav__link">
                                <i class="bx bx-user nav__icon"></i>Profil
                            </a>
                        </li>

                        <li class="class__item">
                            <a href="#education" class="nav__link">
                                <i class="bx bx-book nav__icon"></i>Formation
                            </a>
                        </li>

                        <li class="class__item">
                            <a href="#skills" class="nav__link">
                                <i class="bx bxs-receipt nav__icon"></i>Compétences
                            </a>
                        </li>

                        <li class="class__item">
                            <a href="#experience" class="nav__link">
                                <i class="bx bx-briefcase-alt nav__icon"></i>Experience
                            </a>
                        </li>

                        <li class="class__item">
                            <a href="#certificates" class="nav__link">
                                <i class="bx bx-award nav__icon"></i>Diplômes
                            </a>
                        </li>

                        <li class="class__item">
                            <a href="#references" class="nav__link">
                                <i class="bx bx-link-external nav__icon"></i>Bénévolat
                            </a>
                        </li>

                    </ul>
                </div>

                <div class="nav__toggle" id="nav-toggle">
                    <i class="bx bx-grid-alt"></i>
                </div>
            </nav>  
        </header>

        <main class="l-main bd-container">
            <!-- All elements within this div, is generated in PDF -->
            <div class="resume" id="area-cv">
                <div class="resume__left">
                    <!--========== HOME ==========-->
                    <section class="home" id="home">
                        <div class="home__container section bd-grid">
                            <div class="home__data bd-grid">
                                <img src="assets/img/woman.png" alt="" class="home__img">

                                <h1 class="home__title">DERVIEUX <b>MANON</b></h1>
                                <h3 class="home__profession"><!-- Web developper --></h3>

                                <div>
                                    <a download="" href="assets/pdf/ResumeCv.pdf" class="home__button-movil">Télécharger</a>
                                </div>
                            </div>

                            <div class="home__address bd-grid">
                                <span class="home__information">
                                    <i class="bx bx-map home__icon"></i>Lyon - France
                                </span>

                                <span class="home__information">
                                    <i class="bx bx-envelope-open home__icon"></i>manon.dervieux1992@gmail.com
                                </span>

                                <span class="home__information">
                                    <i class="bx bx-phone home__icon"></i>06-14-81-82-34
                                </span>

                                <span class="home__information">
                                    <i class="bx bx-cake home__icon"></i>01 / 10 / 1992
                                </span>
                            </div>
                        </div>

                        <!-- Theme change button -->
                        
                        <i class="bx bx-moon change-theme" title="Theme" id="theme-button"></i>

                        <!-- Button to generate and download the pdf. -->
                        <i class="bx bx-download generate-pdf" title="Generate PDF" id="resume-button"></i>
                    </section>          
                    
                    <!--========== SOCIAL ==========-->
                    <!-- <section class="social section">
                        <h2 class="section-title">Médias sociaux</h2>

                        <div class="social__container bd-grid">
                            <a href="" target="_blank" class="social__link">
                                <i class="bx bxl-linkedin-square social__icon"></i> www.linkedin.com/in/manon-dervieux
                            </a>
                        </div>
                        
                    </section> -->

                    <!--========== PROFILE ==========-->
                    <!-- <section class="profile section" id="profile">
                        <h2 class="section-title">Profil</h2>

                        <p class="profile__description">Je suis une femme de 31 ans. Je viens de finir ma formation de développeur web Full-Stack spécialité React.</p>
                    </section>
                     -->
                    <!--========== EDUCATION ==========-->
                    <section class="education section" id="education">
                        <h2 class="section-title">Formation</h2>
                        
                        <div class="education__container bd-grid">
                            <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <span class="education__line"></span>
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">DEVELOPPEUR FULLSTACK <br>SPECIALITE REACT</h3>
                                    <span class="education__studies">Ecole O'Clock</span>
                                    <span class="education__year">2023 - 2023</span>
                                </div>
                            </div>

                            <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <span class="education__line"></span>
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">SECRETAIRE MEDICALE</h3>
                                    <span class="education__studies">CNED</span>
                                    <span class="education__year">2021 - 2022</span>
                                </div>
                            </div>

<!--                             <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <span class="education__line"></span>
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">BTS COMPTABILITE</h3>
                                    <span class="education__studies">CNED</span>
                                    <span class="education__year">2020 - 2021</span>
                                </div>
                            </div> -->

                            <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <span class="education__line"></span>
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">LICENCE LANGUE CHINOISE</h3>
                                    <span class="education__studies">UNIVERSITE RENNES 2</span>
                                    <span class="education__year">2016 - 2020</span>
                                </div>
                            </div>

                            <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <span class="education__line"></span>
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">DUL Japonais</h3>
                                    <span class="education__studies">UNIVERSITE RENNES 2</span>
                                    <span class="education__year">2014 - 2017</span>
                                </div>
                            </div>

                            <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <span class="education__line"></span>
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">LICENCE PSYCHOLOGIE</h3>
                                    <span class="education__studies">UNIVERSITE RENNES 2</span>
                                    <span class="education__year">2011 - 2017</span>
                                </div>
                            </div>

                            <div class="education__content">
                                <div class="education__time">
                                    <span class="education__rounder"></span>
                                    <!-- <span class="education__line"></span> -->
                                </div>

                                <div class="education__data bd-grid">
                                    <h3 class="education__title">BAC LITTERRAIRE</h3>
                                    <span class="education__studies">Lycée Saint-Julien</span>
                                    <span class="education__year">2010</span>
                                </div>
                            </div>

                        </div>
                    </section>


                    <!--========== SKILLS  ==========-->
                    <section class="skills section" id="skills">
                        <h2 class="section-title">Compétences</h2>

                        <div class="skills__content bd-grid">
                            <ul class="skills__data">
                                <li class="skills__name">
                                    <span class="skills__circle"></span> Ponctuelle
                                </li>

                                <li class="skills__name">
                                    <span class="skills__circle"></span> Souriante
                                </li>

                                <li class="skills__name">
                                    <span class="skills__circle"></span> Autonome
                                </li>

                                
                            </ul>

                            <ul class="skills__data">
                                <li class="skills__name">
                                    <span class="skills__circle"></span> Organisée
                                </li>

                                <li class="skills__name">
                                    <span class="skills__circle"></span> Curieuse
                                </li>

                            </ul>
                        </div>
                    </section>

                    <!--========== LANGUAGES ==========-->
                    <section class="languages section">
                        <h2 class="section-title">Langues</h2>

                        <div class="languages__container">
                            <ul class="languages__content bd-grid">
                                <li class="languages__name">
                                    <span class="languages__circle"></span>Anglais
                                </li>

                                <li class="languages__name">
                                    <span class="languages__circle"></span>Japonais
                                </li>

                                <li class="languages__name">
                                    <span class="languages__circle"></span>Chinois
                                </li>
                            </ul>
                        </div>
                    </section>

                </div>

                <div class="resume__right">
                    <!--========== EXPERIENCE ==========-->
                    <section class="experience section" id="experience">
                        <h2 class="section-title">Experience</h2>

                        <div class="experience__container bd-grid">

                            <div class="experience__content">
                                <div class="experience__time">
                                    <span class="experience__rounder"></span>
                                    <span class="experience__line"></span>
                                </div>

                                <div class="experience__data bd-grid">
                                    <h3 class="experience__title">Vendeuse en Boutique</h3>
                                    <span class="experience__company">Octobre 2022 | Jeff de Bruges | CDI</span>
                                    <p class="experience__description">Vente de produits en boutique. Tenue du magasin, approvisionnement en rayon, préparation des produits.</p>
                                </div>
                            </div>

                            <div class="experience__content">
                                <div class="experience__time">
                                    <span class="experience__rounder"></span>
                                    <span class="experience__line"></span>
                                </div>

                                <div class="experience__data bd-grid">
                                    <h3 class="experience__title">Secrétaire médicale</h3>
                                    <span class="experience__company">De Janvier à Mars 2022 | Centre Hospitalier de Condrieu, SSIAD | Stage</span>
                                    <p class="experience__description">Stage dans le service de soins à domicile. Tâches principales : tenir les dossiers médicaux, gérer les tournées, les réunions, stocks du service. Dans un autres service: gestion des appels, transports de patients, comptes-rendus médicaux.</p>
                                </div>
                            </div>

                            <div class="experience__content">
                                <div class="experience__time">
                                    <span class="experience__rounder"></span>
                                    <!-- <span class="experience__line"></span> -->
                                </div>

                                <div class="experience__data bd-grid">
                                    <h3 class="experience__title">Employé polyvalent de cuisine</h3>
                                    <span class="experience__company">Juillet 2021 | Restalliance | Intérim</span>
                                    <p class="experience__description">Travail en restauration collective dans un centre de soins à Saint-Prim. Tavail en plonge, service, préparation de certains plats.</p>
                                </div>
                            </div>

                        </div>
                    </section>

                    <!--========== CERTIFICATES ==========-->
                    <section class="certificate section" id="certificates">
                        <h2 class="section-title">Diplômes</h2>

                        <div class="certificate__container bd-grid">
                            <div class="certificate__content">
                                <h3 class="certificate__title">Certification Développeur FullStack - Front-end (Back-end en cours) (2023)</h3>
                                <p class="certificate__description">Certification attestant de mon niveau en développement web. Seule la partie Front-end est pour le moment validée.</p>
                            </div>

                            <div class="certificate__content">
                                <h3 class="certificate__title">Certification secrétariat médicale (2023)</h3>
                                <p class="certificate__description">Permet la pratique de secrétaire médicale dans diverses structures.</p>
                            </div>

                            <div class="certificate__content">
                                <h3 class="certificate__title">DUL Japonais</h3>
                                <p class="certificate__description">Diplôme en langue japonaise. Obtenu à l'université Rennes 2.</p>
                            </div>

                            <div class="certificate__content">
                                <h3 class="certificate__title">BAC Littéraire</h3>
                                <p class="certificate__description">Baccalairéat littéraire, spécialité anglais.</p>
                            </div>
                        </div>
                    </section>

                    <!--========== REFERENCES ==========-->
                    <section class="references section" id="references">
                        <h2 class="section-title">Bénévolat</h2>

                        <div class="certificate__content">
                            <h3 class="certificate__title">UFB (Urgence Fourrières Bretagne)</h3>
                            <p class="certificate__description">Famille d'acceuil de transition entre la sortie de fourrière et le départ en famille d'adoption ou en association.</p>
                        </div>

                       <!--  <div class="references__container bd-grid">
                            <div class="references__content bd-grid">
                                <span class="references__subtitle">UFB (Urgence Fourrières Bretagne)</span>
                                <h3 class="references__title">Famille d'acceuil transitionnelle</h3>
                                <ul class="references__contact">
                                    <li>Phone: 999 - 777 - 666</li>
                                    <li>Email: user@email.com</li>
                                </ul>
                            </div>

                        </div> -->
                    </section>


                    
                    <!--========== INTERESTS ==========-->
                    <section class="interests section">
                        <h2 class="section-title">Loisirs</h2>
                        
                        <div class="interests__container bd-grid">
                            <div class="interests__content">
                                <i class="bx bx-headphone interests__icon"></i>
                                <span class="interests__name">Musique</span>
                            </div>

                            <div class="interests__content">
                                <i class="bx bxs-joystick interests__icon"></i>
                                <span class="interests__name">Jeux vidéos</span>
                            </div>

                            <div class="interests__content">
                                <i class="bx bx-book interests__icon"></i>
                                <span class="interests__name">Lecture</span>
                            </div>

                            <div class="interests__content">
                                <i class="bx bxs-leaf interests__icon"></i>
                                <span class="interests__name">Plantes</span>
                            </div>
                        </div>
                    </section>
                </div>
            </div>        
        </main>

        <!--========== SCROLL TOP ==========-->
        
        <a href="#" class="scrolltop" id="scroll-top">
            <i class="bx bx-up-arrow-alt scrolltop__arrow"></i>
        </a>

        <!--========== HTML2PDF ==========-->
        <script src="assets/js/html2pdf.bundle.min.js"></script>

        <!--========== MAIN JS ==========-->
        <script src="assets/js/main.js"></script>
        
    </body>
</html>



<!-- CSS -->

/*===== GOOGLE FONTS =====*/
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');

/*===== VARIABLES CSS =====*/
:root {
  --header-height: 3rem;
  
  /*========== Colors ==========*/
  --title-color: #0B0A0A;
  --text-color: #403A3A;
  --text-color-light: #707070;
  --container-color: #FAFAFA;
  --container-color-alt: #F0EFEF;
  --body-color: #FCFCFC;

  /*========== Font and typography ==========*/
  --body-font: 'Poppins', sans-serif;
  --h1-font-size: 1.5rem;
  --h2-font-size: 1.25rem;
  --h3-font-size: 1rem;
  --normal-font-size: .938rem;
  --small-font-size: .875rem;
  --smaller-font-size: .813rem;

  /*========== Font weight ==========*/
  --font-medium: 500;
  --font-semi-bold: 600;

  /*========== Margenes ==========*/
  --mb-1: .5rem;
  --mb-2: 1rem;
  --mb-3: 1.5rem;

  /*========== z index ==========*/
  --z-tooltip: 10;
  --z-fixed: 100;
}

/*========== BASE ==========*/

*,::before,::after{
  box-sizing: border-box;
}

html{
  scroll-behavior: smooth;
}

/*========== Variables Dark theme ==========*/

body.dark-theme{
  --title-color: #F2F2F2;
  --text-color: #BFBFBF;
  --container-color: #212121;
  --container-color-alt: #181616;
  --body-color: #2B2B2B;
}

/*========== Button Dark/Light ==========*/

.change-theme{
  position: absolute;
  right: 0;
  top: 2.2rem;
  display: flex;
  color: var(--text-color);
  font-size: 1.2rem;
  cursor: pointer;
}

.change-theme:hover{
  color: var(--title-color);
}

/*========== Font size variables to scale cv ==========*/


body.scale-cv{
  --h1-font-size: .938rem;
  --h2-font-size: .938rem;
  --h3-font-size: .875rem;
  --normal-font-size: .813rem;
  --small-font-size: .75rem;
  --smaller-font-size: .688rem;

}
/*========== Generate PDF button ==========*/

.generate-pdf{
  display: none;
  position: absolute;
  top: 2.2rem;
  left: 0;
  font-size: 1.2rem;
  color: var(--text-color);
  cursor: pointer;
}

.generate-pdf:hover{
  color: var(--title-color);
}

/*========== Classes modified to reduce size and print on A4 sheet ==========*/

.scale-cv .change-theme,
.scale-cv .generate-pdf{
  display: none;
}

.scale-cv .bd-container{
  max-width: 595px;
}

.scale-cv .section{
  padding: 1.5rem 0 .80rem;
}

.scale-cv .section-title{
  margin-bottom: .75rem;
}

.scale-cv .resume__left,
.scale-cv .resume__right{
  padding: 0 1rem;
}

.scale-cv .home__img{
  width: 90px;
  height: 90px;
}

.scale-cv .home__container{
  gap: 1.5rem;
}

.scale-cv .home__data{
  gap: .25rem;
}

.scale-cv .home__address,
.scale-cv .home__container{
  gap: .75rem;
}

.scale-cv .home__icon,
.scale-cv .social__icon,
.scale-cv .interests__icon{
  font-size: 1rem;
}

.scale-cv .education__container,
.scale-cv .experience__container,
.scale-cv .certificate__container{
  gap: 1rem;
}

.scale-cv .education__time,
.scale-cv .experience__time{
  padding-right: .5rem;
}

.scale-cv .education__rounder,
.scale-cv .experience__rounder{
  width: 11px;
  height: 11px;
  margin-top: .22rem;
}

.scale-cv .education__line,
.scale-cv .experience__line{
  width: 1px;
  height: 110%;
  transform: translate(5px, 0);
}

.scale-cv .education__data,
.scale-cv .experience__data{
  gap: .25rem;
}

.scale-cv .skills__name{
  margin-bottom: var(--mb-1);
}

.scale-cv .interests__container{
  column-gap: 2.5rem;
}

body{
  margin: 0 0 var(--header-height) 0;
  padding: 0;
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  background-color: var(--body-color);
  color: var(--text-color);
}

h1,h2,h3,ul,p{
  margin: 0;
}

h1,h2,h3{
  color: var(--title-color);
  font-weight: var(--font-medium);
}

ul{
  padding: O;
  list-style: none;
}

a{
  text-decoration: none;
}

img{
  max-width: 100%;
  height: auto;
}

/*========== CLASS CSS ==========*/

.section{
  padding: 1.5rem 0;
}

.section-title{
  font-size: var(--h2-font-size);
  color: var(--title-color);
  font-weight: var(--font-semi-bold);
  text-transform: uppercase;
  letter-spacing: .35rem;
  text-align: center;
  margin-bottom: var(--mb-3);
}

/*========== LAYOUT ==========*/

.bd-container{
  max-width: 968px;
  width: calc(100% - 3rem);
  margin-left: var(--mb-3);
  margin-right: var(--mb-3);
}

.bd-grid{
  display: grid;
  gap: 1.5rem;
}

.l-header{
  width: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: var(--z-fixed);
  background-color: var(--body-color);
  box-shadow: 0 -1px 4px rgba(0,0,0,.1);
  transition: .3s;
}

/*========== NAV ==========*/

.nav{
  height: var(--header-height);
  display: flex;
  justify-content: space-between;
  align-items: center;
}

@media screen and (max-width: 968px){
  .nav__menu{
    position: fixed;
    bottom: -100%;
    left: 0;
    width: 100%;
    padding: 2rem 1.5rem;
    background-color: var(--body-color);
    box-shadow: 0 1px 4px rgba(0,0,0,.1);
    border-radius: 1rem 1rem 0 0;
    z-index: var(--z-fixed);
    transition: .3s;
  }
}

.nav__logo,
.nav__toggle{
  color: var(--title-color);
  font-weight: var(--font-medium);
  padding: 1rem;
}

.nav__toggle{
  font-size: 1.2rem;
  cursor: pointer;
}

.nav__item{
  text-align: center;
}

.nav__list{
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
}

.nav__link{
  display: flex;
  flex-direction: column;
  font-size: var(--smaller-font-size);
  color: var(--text-color-light);
  font-weight: var(--font-medium);
}
  
.nav__link:hover{
  color: var(--title-color);
 
}

.nav__icon{
  font-size: 1.2rem;
  margin-bottom: var(--mb-1);
}

/* Show menu */

.show-menu{
  bottom: var(--header-height);
}

/* Active menu link */

.active-link{
  color: var(--title-color);
}

/*========== HOME ==========*/

.home{
  position: relative;
}

.home__container{
  gap: 3rem;
}

.home__data{
  gap: .5rem;
  text-align: center;
}

.home__img{
  width: 120px;
  height: 120px;
  border-radius: 50%;
  justify-self: center;
  margin-bottom: var(--mb-1);
}

.home__title{
  font-size: var(--h1-font-size);
}

.home__profession{
  font-size: var(--normal-font-size);
  margin-bottom: var(--mb-1);
}

.home__address{
  gap: 1rem;
}

.home__information{
  display: flex;
  align-items: center;
  font-size: var(--small-font-size);
}

.home__icon{
  font-size: 1.2rem;
  margin-right: .25rem;
}

.home__button-movil{
  display: inline-block;
  border: 2px solid var(--text-color);
  color: var(--title-color);
  padding: 1rem 2rem;
  border-radius: .25rem;
  transition: .3s;
  font-weight: var(--font-medium);
  margin-top: var(--mb-3);
}

.home__button-movil:hover{
  background-color: var(--text-color);
  color: var(--container-color);
}



/*========== SOCIAL ==========*/

.social__container{
  grid-template-columns: max-content;
  gap: 1rem;
}

.social__link{
  display: inline-flex;
  align-items: center;
  font-size: var(--small-font-size);
  color: var(--text-color);
}

.social__link:hover{
  color: var(--title-color);
}

.social__icon{
  font-size: 1.2rem;
  margin-right: .25rem;
}

/*========== PROFILE ==========*/

.profile__description{
  text-align: center;
}

/*========== EDUCATION AND EXPERIENCE ==========*/

.education__content,
.experience__content{
  display: flex;
}

.education__time,
.experience__time{
  padding-right: 1rem;
}

.education__rounder,
.experience__rounder{
  position: relative;
  display: block;
  width: 16px;
  height: 16px;
  background-color: var(--text-color-light);
  border-radius: 50%;
  margin-top: .25rem;
}

.education__line,
.experience__line{
  display: block;
  width: 2px;
  height: 110%;
  background-color: var(--text-color-light);
  transform: translate(7px, 0);
}

.education__data,
.experience__data{
  gap: .5rem;
}

.education__title,
.experience__title{
  font-size: var(--h3-font-size);
}

.education__studies,
.experience__company{
  font-size: var(--small-font-size);
  color: var(--title-color);
}

.education__year{
  font-size: var(--smaller-font-size);
}

/*========== SKILLS AND LANGUAGES ==========*/

.skills__content,
.languages__content{
  grid-template-columns: repeat(2, 1fr);
  padding-left: 0;
}

.languages__content{
  gap: 0;
}

.skills__name,
.languages__name{
  display: flex;
  align-items: center;
  margin-bottom: var(--mb-3);
}

.skills__circle,
.languages__circle{
  display: inline-block;
  width: 5px;
  height: 5px;
  background-color: var(--text-color);
  border-radius: 50%;
  margin-right: .75rem;
}

/*========== CERTIFICATES ==========*/

.certificate__title{
  font-size: var(--h3-font-size);
  margin-bottom: var(--mb-1);
}



/*========== REFERENCES ==========*/

.references__content{
  gap: .25rem;
}

.references__subtitle{
  color: var(--text-color-light);
}

.references__subtitle,
.references__contact{
  font-size: var(--smaller-font-size);
}

.references__title{
  font-size: var(--h3-font-size);
}

/*========== INTERESTS ==========*/

.interests__container{
  grid-template-columns: repeat(3, 1fr);
  margin-top: var(--mb-2);
}

.interests__content{
  display: flex;
  flex-direction: column;
  align-items: center;
}

.interests__icon{
  font-size: 1.5rem;
  color: var(--text-color-light);
  margin-bottom: .25rem;
}



/* Scroll top */

.scrolltop{
  position: fixed;
  right: 1rem;
  bottom: -20%;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: .3rem;
  background-color: var(--container-color-alt);
  border-radius: .4rem;
  z-index: var(--z-tooltip);
  transition: .4s;
  visibility: hidden;
}

.scrolltop__icon{
  font-size: 1.2rem;
  color: var(--text-color);
}

.show-scroll{
  visibility: visible;
  bottom: 5rem;
}

/*========== MEDIA QUERIES ==========*/

/* For small devices, menu two columns */
@media screen and (max-width: 320px) {
  .nav__list{
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem .5rem;
  }
}

/* Classes modified for large screen size */
@media screen and (min-width: 968px) {
  body{
    margin: 3rem 0;
  }

  .bd-container{
    margin-left: auto;
    margin-right: auto;
  }

  .l-header,
  .scrolltop{
    display: none;
  }

  .resume{
    display: grid;
    grid-template-columns: .5fr 1fr;
    background-color: var(--container-color);
    box-shadow: 0 0 8px rgba(13,12,12,.15);
  }

  .resume__left{
    background-color: var(--container-color-alt);
  }

  .resume__left,
  .resume__right{
    padding: 0 1.5rem;
  }

  .generate-pdf{
    display: inline-block;
  }

  .section-title,
  .profile__description{
    text-align: initial;
  }

  .home__container{
    gap: 1.5rem;
  }

  .home__button-movil{
    display: none;
  }

  .languages__content{
    grid-template-columns: repeat(3, max-content);
    column-gap: 3.5rem;
  }

  .interests__container{
    grid-template-columns: repeat(4, max-content);
    column-gap: 3.5rem;
  } 
  .skills__data{
      padding: 0;
    }
}

