$primary-text-color: #757575;
$title-text-color: #000000;
$accent-color: #2196f3;
$primary-white-color: #ffffff;

body { background-color: #ffffff; color: \$primary-text-color; font-family: Roboto, sans-serif;
font-style: normal; font-weight: normal; font-size: 14px; letter-spacing: 0.03rem; }

a { text-decoration: none; color: \$primary-text-color; font-style: normal; }

ul { list-style-type: none; padding-left: 0; margin-top: 0; margin-bottom: 0; }

.page-header { border-bottom: 1px solid #ececec; }

h1, h2 { padding: 0; margin: 0; }

h3 { padding: 0; margin: 0; font-weight: bold; font-size: 14px; line-height: 1.2; text-transform:
uppercase; }

a { padding: 0; margin: 0; }

section { margin-bottom: 94px; }

p { margin: 0; line-height: 1.7; }

.container, .container-advantages, .container-whot-do-we, .container-team, .container-customers,
.container-footer, .container-portfolio { margin-left: auto; margin-right: auto; width: 1200px;
padding-left: 15px; padding-right: 15px; }

.container { display: flex; align-items: center; }

.box-advantages, .box-whot-do-we, .box-team, .list-icon, .fooret-box { display: flex;
justify-content: space-between; }

.fooret-box { align-items: center; }

.logo, .logo-footer { color: \$title-text-color; font-family: Raleway; font-style: normal;
font-weight: bold; font-size: 26px; line-height: 1.2; }

.logo { margin-right: 85px; }

.address-nav-icon { display: inline-flex; align-items: center; margin-right: 10px; fill:
\$primary-text-color;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.link:hover, .link:focus, .link.current, .address-nav-link:hover, .address-nav-link:focus { color:
\$accent-color; }

.link.current::after { content: '';

position: absolute; left: 0; bottom: 0;

display: block; width: 100%; height: 4px; background-color: #2196f3; border-radius: 2px; }

.address-nav-link:hover .address-nav-icon, .address-nav-link:focus .address-nav-icon { fill:
\$accent-color; }

.hero { display: flex; flex-direction: column; align-items: center; justify-content: center;
max-width: 1600px; min-height: 600px; margin-left: auto; margin-right: auto; background-color:
rgb(47, 48, 58, 0.8); background-image: linear-gradient(to right, rgba(47, 48, 58, 0.8), rgba(47,
48, 58, 0.8)), url(../image/Headerimg.jpg); background-repeat: no-repeat; background-position:
center; background-size: cover; }

.hero-title { color: \$primary-white-color; font-weight: 900; font-size: 44px; line-height: 1.35;
text-align: center; text-transform: uppercase; letter-spacing: 0.06rem; margin-top: auto;
margin-bottom: 30px; }

.hero-button, .button-subscribe, .modal-send { display: block; border: 0; border-radius: 4px;
padding: 10px 32px; min-width: 200px; margin: 0 auto;

background-color: $accent-color;
  color: $primary-white-color; box-shadow: 0px 4px 4px rgba(0, 0, 0,
0.15); font-weight: bold; font-size: 16px; line-height: 1.9; text-align: center; }

.hero-button { margin-bottom: auto; }

.box-advantages-item { width: 270px; margin-bottom: 30px; }

.box-advantages-item::before { display: block; content: ''; height: 120px; background-size: 70px;
background-repeat: no-repeat; background-position: center; border-radius: 4px; padding: 25px 100px;
background-color: #f5f4fa; }

.icon-antenna::before { background-image: url(../image/antenna1.svg); }

.icon-clock::before { background-image: url(../image/clock1.svg); }

.icon-diagram::before { background-image: url(../image/diagram1.svg); }

.icon-astronaut::before { background-image: url(../image/astronaut1.svg); }

.title-advantages { color: \$title-text-color; margin-top: 30px; margin-bottom: 10px; }

.link { position: relative; display: block; padding-top: 32px; padding-bottom: 32px; color:
\$title-text-color; font-weight: 500; line-height: 1.2;

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.address-nav-link + .address-nav-link { margin-left: 30px; }

.address-nav { margin-left: auto; }

.address-nav-link { color: \$primary-text-color;

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.section-title { color: \$title-text-color; font-weight: bold; font-size: 36px; line-height: 1.2;
text-align: center; padding-bottom: 50px; }

.box-whot-do-we-item { position: relative; width: 370px; height: 294px; background-color:
\$primary-white-color; box-shadow: 0px 2px 1px rgba(0, 0, 0, 0.2), 0px 1px 1px rgba(0, 0, 0, 0.14),
0px 1px 3px rgba(0, 0, 0, 0.12); border-radius: 0px 0px 4px 4px; }

.section-whot-do-we-text { position: absolute; bottom: 0; left: 0; width: 100%; padding-top: 25px;
padding-bottom: 25px; background-color: rgba(47, 48, 58, 0.8); color: \$primary-white-color;
font-weight: bold; text-align: center; line-height: 1.5; text-transform: uppercase; }

.section-team { background: #f5f4fa; padding-top: 94px; padding-bottom: 94px; }

.box-team-item { width: 270px; padding-bottom: 24px; box-shadow: 0px 2px 1px rgba(0, 0, 0, 0.2), 0px
1px 1px rgba(0, 0, 0, 0.14), 0px 1px 3px rgba(0, 0, 0, 0.12); border-radius: 0px 0px 4px 4px; }

.name { margin-top: 30px; text-transform: none;

color: \$title-text-color; font-weight: 500; font-size: 16px; line-height: unset; text-align:
center; }

.team-text { margin-top: 10px; margin-bottom: 16px; text-align: center; font-size: 16px;
line-height: 1.2; }

.social-list { display: flex; justify-content: center; }

.social-item + .social-item { margin-left: 10px; }

.social-link { display: flex; justify-content: center; align-items: center; width: 44px; height:
44px; border-radius: 50%;

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1), background-color 250ms cubic-bezier(0.4, 0,
0.2, 1); }

.social-icon { fill: #afb1b8;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.social-link:hover, .social-link:focus { background-color: \$accent-color; }

.social-link:hover .social-icon, .social-link:focus .social-icon { fill: #ffffff; }

.list-icon-link { display: flex; justify-content: center; align-items: center; width: 170px; height:
90px; border: 1px solid #afb1b8; border-radius: 4px;

transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1), fill 250ms cubic-bezier(0.4, 0, 0.2,
1); }

.social-icon-customers { fill: #afb1b8;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.list-icon-link:hover, .list-icon-link:focus { border-color: \$accent-color; }

.list-icon-link:hover .social-icon-customers, .list-icon-link:focus .social-icon-customers { fill:
\$accent-color; }

// Footer

footer { background-color: #2f303a; }

.container-footer { padding-top: 45px; padding-bottom: 21px; }

.footer-title { color: \$primary-white-color; text-align: left; margin-bottom: 20px; }

.logo-footer { display: block; margin-bottom: 20px; }

.logo-web { color: $accent-color;
}
.logo-studio-white {
  color: $primary-white-color; }

.address-link { display: block; margin-top: 9px; }

.address-map { color: \$primary-white-color; }

.social-list-footer { display: flex; justify-content: center; }

.social-item-footer + .social-item-footer { margin-left: 10px; }

.social-link-footer { display: flex; justify-content: center; align-items: center; width: 44px;
height: 44px; background-color: rgba(255, 255, 255, 0.1); border-radius: 50%;

transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.social-icon-footer { fill: #ffffff;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.social-link-footer:hover, .social-link-footer:focus { background-color: \$accent-color; }

.input-subscribe { width: 358px; height: 50px; padding: 15px 16px; background: #2f303a; border: 1px
solid rgba(255, 255, 255, 0.3); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15); border-radius: 4px;
margin-right: 12px; font-size: 16px; color: rgba(255, 255, 255, 0.6); }

.input-subscribe::placeholder { font-size: 16px; color: rgba(255, 255, 255, 0.6); }

.button-subscribe { display: inline-flex; align-items: center; }

.button-subscribe::after { content: ''; width: 24px; height: 24px; margin-left: 10px;
background-image: url(../image/iconsend.svg); background-size: contain; }

// /_ Portfolio _/

.portfolio-title { display: none; }

.container-portfolio { padding-top: 93px; padding-bottom: 93px; }

.portfolio-button-list { display: flex; justify-content: center; margin-bottom: 50px; }

.portfolio-button-item + .portfolio-button-item { margin-left: 8px; }

.button-portfolio { padding: 6.2px 22px; background-color: #f5f4fa; border: 0; color:
\$title-text-color; border-radius: 4px; font-weight: 500; font-size: 16px; line-height: 1.64;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1), color 250ms cubic-bezier(0.4, 0,
0.2, 1); }

.button-portfolio.current, .button-portfolio:hover, .button-portfolio:focus { background-color:
$accent-color;
  color: $primary-white-color; }

.portfolio-list { display: flex; flex-wrap: wrap; }

.portfolio-link { line-height: 0; }

.portfolio-card { background: #ffffff; border: 1px solid #eeeeee; }

.portfolio-link:hover .portfolio-card { box-sizing: border-box; box-shadow: 1px 4px 6px rgba(0, 0,
0, 0.16), 0px 4px 4px rgba(0, 0, 0, 0.06), 0px 1px 1px rgba(0, 0, 0, 0.12); }

.portfolio-overlay { position: relative; overflow: hidden; }

.portfolio-item { width: calc((100% - 60px) / 3); margin-right: 30px; margin-bottom: 30px; }

.portfolio-item:nth-child(3n) { margin-right: 0; }

.portfolio-item:nth-last-child(-n + 3) { margin-bottom: 0; }

.portfolio-text-about { position: absolute; top: 0; left: 0; padding: 63px 24px; background-color:
$accent-color;
  color: $primary-white-color\$; font-size: 18px; line-height: 1.6;

transform: translateY(calc(100% + 1px)); transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.portfolio-link:hover .portfolio-text-about { transform: translateY(0); }

.portfolio-text { padding: 20px 24px; }

.portfolio-caption { color: \$title-text-color; font-weight: bold; font-size: 18px; line-height: 2;
}

.portfolio-kind { margin-top: 4px; font-size: 16px; line-height: 1.9; }

// /_ Modal _/

.backdrop { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0,
0, 0, 0.2); transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1), visibility 250ms
cubic-bezier(0.4, 0, 0.2, 1); }

.backdrop.is-hidden { opacity: 0; visibility: hidden; pointer-events: none; }

.modal-to-order { position: absolute; top: 50%; left: 50%; width: 528px; padding: 20px 20px;
transform: translate(-50%, -50%); background-color: \$primary-white-color; box-shadow: 0px 2px 1px
rgba(0, 0, 0, 0.2), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 1px 3px rgba(0, 0, 0, 0.12); border-radius:
4px; }

.modal-label { margin-bottom: 30px; font-family: Roboto; font-style: normal; font-weight: bold;
font-size: 20px; line-height: 23px; text-align: center; letter-spacing: 0.03rem;

color: \$title-text-color; }

.form-field { position: relative; }

.form-field:nth-child(-n + 3) { margin-bottom: 28px; }

.form-input, .comment { width: 100%; margin: 0; padding: 11px 16px 11px 42px; outline: none; font:
inherit; border-radius: 4px; border: 1px solid rgba(33, 33, 33, 0.2); font-size: 12px; color:
\$primary-text-color; transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.comment { resize: none; }

.form-input:focus, .comment:focus, .form-input:not(:placeholder-shown),
.comment:not(:placeholder-shown) { border: 1px solid \$accent-color; }

.form-label, .form-label-comment { position: absolute; font-size: 12px; line-height: 14px;
letter-spacing: 0.01rem; transform: translateY(-50%);

transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.form-label { top: 50%; left: 42px; }

.form-label-comment { top: 12px; left: 16px; transform: translateY(0%);

transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.form-input:focus + .form-label, .form-input:not(:placeholder-shown) + .form-label { color:
\$accent-color; transform: translateY(-40px) translateX(-26px); }

.comment:focus + .form-label-comment { color: \$accent-color; transform: translateY(-32px); }

.icon-modal { position: absolute; top: 50%; left: 16px;

transform: translateY(-50%);

display: inline-block; width: 18px; height: 18px; fill: \$title-text-color; transition: fill 250ms
cubic-bezier(0.4, 0, 0.2, 1); }

.form-input:focus ~ .icon-modal, .form-input:not(:placeholder-shown) ~ .icon-modal { fill:
\$accent-color; }

.modal-close { position: absolute; padding: 4.5px; top: 8px; right: 8px; width: 30px; height: 30px;
outline: none; background-color: \$primary-white-color; border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 50%; }

.close-icon { color: \$accent-color; transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.modal-close:hover .close-icon, .modal-close:focus .close-icon { fill: \$accent-color; }

.form-checkbox { margin-top: 20px; margin-bottom: 30px; display: flex; justify-content: center;
align-items: center; }

.checkbox-label { display: inline-flex; justify-content: center; align-items: center; font-size:
14px; line-height: 24px; }

.checkbox-link { margin-left: 5px; color: \$accent-color; text-decoration-line: underline; }

.checkbox { position: absolute; width: 1px; height: 1px; margin: -1px; border: 0; padding: 0; clip:
rect(0 0 0 0); overflow: hidden; }

.checkbox-label::before { content: ' '; display: inline-block; width: 16px; height: 16px;
margin-right: 8px;

border: 2px solid #2a2a2a; border-radius: 2px;

transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.checkbox:checked ~ .checkbox-label::before { transform: scale(1.1); border-color: transparent;
background-color: \$accent-color; background-image: url(../image/iconCheck.svg); background-size:
contain; background-origin: border-box; }

Cnfhjt

:root { --primary-text-color: #757575; --title-text-color: #000000; --accent-color: #2196f3;
--primary-white-color: #ffffff; --color1: #212121; }

body { background-color: #ffffff; color: var(--primary-text-color); font-family: Roboto, sans-serif;
font-style: normal; font-weight: normal; font-size: 14px; letter-spacing: 0.03rem; }

a { text-decoration: none; color: var(--primary-text-color); font-style: normal; }

ul { list-style-type: none; padding-left: 0; margin-top: 0; margin-bottom: 0; }

.page-header { border-bottom: 1px solid #ececec; }

h1, h2 { padding: 0; margin: 0; }

h3 { padding: 0; margin: 0; font-weight: bold; font-size: 14px; line-height: 1.2; text-transform:
uppercase; }

a { padding: 0; margin: 0; }

section { margin-bottom: 94px; }

p { margin: 0; line-height: 1.7; }

.container, .container-advantages, .container-whot-do-we, .container-team, .container-customers,
.container-footer, .container-portfolio { margin-left: auto; margin-right: auto; width: 1200px;
padding-left: 15px; padding-right: 15px; }

.container { display: flex; align-items: center; }

.box-advantages, .box-whot-do-we, .box-team, .list-icon, .fooret-box { display: flex;
justify-content: space-between; }

.fooret-box { align-items: center; }

.logo, .logo-footer { color: var(--title-text-color); font-family: Raleway; font-style: normal;
font-weight: bold; font-size: 26px; line-height: 1.2; }

.logo { margin-right: 85px; }

.address-nav-icon { display: inline-flex; align-items: center; margin-right: 10px; fill:
var(--primary-text-color);

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.link:hover, .link:focus, .link.current, .address-nav-link:hover, .address-nav-link:focus { color:
var(--accent-color); }

.link.current::after { content: '';

position: absolute; left: 0; bottom: 0;

display: block; width: 100%; height: 4px; background-color: #2196f3; border-radius: 2px; }

.address-nav-link:hover .address-nav-icon, .address-nav-link:focus .address-nav-icon { fill:
var(--accent-color); }

.hero { display: flex; flex-direction: column; align-items: center; justify-content: center;
max-width: 1600px; min-height: 600px; margin-left: auto; margin-right: auto; background-color:
rgb(47, 48, 58, 0.8); background-image: linear-gradient(to right, rgba(47, 48, 58, 0.8), rgba(47,
48, 58, 0.8)), url(../image/Headerimg.jpg); background-repeat: no-repeat; background-position:
center; background-size: cover; }

.hero-title { color: var(--primary-white-color); font-weight: 900; font-size: 44px; line-height:
1.35; text-align: center; text-transform: uppercase; letter-spacing: 0.06rem; margin-top: auto;
margin-bottom: 30px; }

.hero-button, .button-subscribe, .modal-send { display: block; border: 0; border-radius: 4px;
padding: 10px 32px; min-width: 200px; margin: 0 auto;

background-color: var(--accent-color); color: var(--primary-white-color); box-shadow: 0px 4px 4px
rgba(0, 0, 0, 0.15); font-weight: bold; font-size: 16px; line-height: 1.9; text-align: center; }

.hero-button { margin-bottom: auto; }

.box-advantages-item { width: 270px; margin-bottom: 30px; }

.box-advantages-item::before { display: block; content: ''; height: 120px; background-size: 70px;
background-repeat: no-repeat; background-position: center; border-radius: 4px; padding: 25px 100px;
background-color: #f5f4fa; }

.icon-antenna::before { background-image: url(../image/antenna1.svg); }

.icon-clock::before { background-image: url(../image/clock1.svg); }

.icon-diagram::before { background-image: url(../image/diagram1.svg); }

.icon-astronaut::before { background-image: url(../image/astronaut1.svg); }

.title-advantages { color: var(--title-text-color); margin-top: 30px; margin-bottom: 10px; }

.link { position: relative; display: block; padding-top: 32px; padding-bottom: 32px; color:
var(--title-text-color); font-weight: 500; line-height: 1.2;

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.address-nav-link + .address-nav-link { margin-left: 30px; }

.address-nav { margin-left: auto; }

.address-nav-link { color: var(--primary-text-color);

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.section-title { color: var(--title-text-color); font-weight: bold; font-size: 36px; line-height:
1.2; text-align: center; padding-bottom: 50px; }

.box-whot-do-we-item { position: relative; width: 370px; height: 294px; background-color:
var(--primary-white-color); box-shadow: 0px 2px 1px rgba(0, 0, 0, 0.2), 0px 1px 1px rgba(0, 0, 0,
0.14), 0px 1px 3px rgba(0, 0, 0, 0.12); border-radius: 0px 0px 4px 4px; }

.section-whot-do-we-text { position: absolute; bottom: 0; left: 0; width: 100%; padding-top: 25px;
padding-bottom: 25px; background-color: rgba(47, 48, 58, 0.8); color: var(--primary-white-color);
font-weight: bold; text-align: center; line-height: 1.5; text-transform: uppercase; }

.section-team { background: #f5f4fa; padding-top: 94px; padding-bottom: 94px; }

.box-team-item { width: 270px; padding-bottom: 24px; box-shadow: 0px 2px 1px rgba(0, 0, 0, 0.2), 0px
1px 1px rgba(0, 0, 0, 0.14), 0px 1px 3px rgba(0, 0, 0, 0.12); border-radius: 0px 0px 4px 4px; }

.name { margin-top: 30px; text-transform: none;

color: var(--title-text-color); font-weight: 500; font-size: 16px; line-height: unset; text-align:
center; }

.team-text { margin-top: 10px; margin-bottom: 16px; text-align: center; font-size: 16px;
line-height: 1.2; }

.social-list { display: flex; justify-content: center; }

.social-item + .social-item { margin-left: 10px; }

.social-link { display: flex; justify-content: center; align-items: center; width: 44px; height:
44px; border-radius: 50%;

transition: color 250ms cubic-bezier(0.4, 0, 0.2, 1), background-color 250ms cubic-bezier(0.4, 0,
0.2, 1); }

.social-icon { fill: #afb1b8;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.social-link:hover, .social-link:focus { background-color: var(--accent-color); }

.social-link:hover .social-icon, .social-link:focus .social-icon { fill: #ffffff; }

.list-icon-link { display: flex; justify-content: center; align-items: center; width: 170px; height:
90px; border: 1px solid #afb1b8; border-radius: 4px;

transition: border-color 250ms cubic-bezier(0.4, 0, 0.2, 1), fill 250ms cubic-bezier(0.4, 0, 0.2,
1); }

.social-icon-customers { fill: #afb1b8;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.list-icon-link:hover, .list-icon-link:focus { border-color: var(--accent-color); }

.list-icon-link:hover .social-icon-customers, .list-icon-link:focus .social-icon-customers { fill:
var(--accent-color); }

/_ Footer _/

footer { background-color: #2f303a; }

.container-footer { padding-top: 45px; padding-bottom: 21px; }

.footer-title { color: var(--primary-white-color); text-align: left; margin-bottom: 20px; }

.logo-footer { display: block; margin-bottom: 20px; }

.logo-web { color: var(--accent-color); } .logo-studio-white { color: var(--primary-white-color); }

.address-link { display: block; margin-top: 9px; }

.address-map { color: var(--primary-white-color); }

.social-list-footer { display: flex; justify-content: center; }

.social-item-footer + .social-item-footer { margin-left: 10px; }

.social-link-footer { display: flex; justify-content: center; align-items: center; width: 44px;
height: 44px; background-color: rgba(255, 255, 255, 0.1); border-radius: 50%;

transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.social-icon-footer { fill: #ffffff;

transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.social-link-footer:hover, .social-link-footer:focus { background-color: var(--accent-color); }

.input-subscribe { width: 358px; height: 50px; padding: 15px 16px; background: #2f303a; border: 1px
solid rgba(255, 255, 255, 0.3); box-shadow: 0px 4px 4px rgba(0, 0, 0, 0.15); border-radius: 4px;
margin-right: 12px; font-size: 16px; color: rgba(255, 255, 255, 0.6); }

.input-subscribe::placeholder{ font-size: 16px; color: rgba(255, 255, 255, 0.6); }

.button-subscribe { display: inline-flex; align-items: center; }

.button-subscribe::after { content: ''; width: 24px; height: 24px; margin-left: 10px;
background-image: url(../image/iconsend.svg); background-size: contain; }

/_ Portfolio _/ .portfolio-title { display: none; }

.container-portfolio { padding-top: 93px; padding-bottom: 93px; }

.portfolio-button-list { display: flex; justify-content: center; margin-bottom: 50px; }

.portfolio-button-item + .portfolio-button-item { margin-left: 8px; }

.button-portfolio { padding: 6.2px 22px; background-color: #f5f4fa; border: 0; color:
var(--title-text-color); border-radius: 4px; font-weight: 500; font-size: 16px; line-height: 1.64;
transition: background-color 250ms cubic-bezier(0.4, 0, 0.2, 1), color 250ms cubic-bezier(0.4, 0,
0.2, 1); }

.button-portfolio.current, .button-portfolio:hover, .button-portfolio:focus { background-color:
var(--accent-color); color: var(--primary-white-color); }

.portfolio-list { display: flex; flex-wrap: wrap; }

.portfolio-link { line-height: 0; }

.portfolio-card { background: #ffffff; border: 1px solid #eeeeee; }

.portfolio-link:hover .portfolio-card { box-sizing: border-box; box-shadow: 1px 4px 6px rgba(0, 0,
0, 0.16), 0px 4px 4px rgba(0, 0, 0, 0.06), 0px 1px 1px rgba(0, 0, 0, 0.12); }

.portfolio-overlay { position: relative; overflow: hidden; }

.portfolio-item { width: calc((100% - 60px) / 3); margin-right: 30px; margin-bottom: 30px; }

.portfolio-item:nth-child(3n) { margin-right: 0; }

.portfolio-item:nth-last-child(-n + 3) { margin-bottom: 0; }

.portfolio-text-about { position: absolute; top: 0; left: 0; padding: 63px 24px; background-color:
var(--accent-color); color: var(--primary-white-color); font-size: 18px; line-height: 1.6;

transform: translateY(calc(100% + 1px)); transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.portfolio-link:hover .portfolio-text-about { transform: translateY(0); }

.portfolio-text { padding: 20px 24px; }

.portfolio-caption { color: var(--title-text-color); font-weight: bold; font-size: 18px;
line-height: 2; }

.portfolio-kind { margin-top: 4px; font-size: 16px; line-height: 1.9; }

/_ Modal _/

.backdrop { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background-color: rgba(0,
0, 0, 0.2); transition: opacity 250ms cubic-bezier(0.4, 0, 0.2, 1), visibility 250ms
cubic-bezier(0.4, 0, 0.2, 1); }

.backdrop.is-hidden { opacity: 0; visibility: hidden; pointer-events: none; }

.modal-to-order { position: absolute; top: 50%; left: 50%; width: 528px; padding: 20px 20px;
transform: translate(-50%, -50%); background-color: var(--primary-white-color); box-shadow: 0px 2px
1px rgba(0, 0, 0, 0.2), 0px 1px 1px rgba(0, 0, 0, 0.14), 0px 1px 3px rgba(0, 0, 0, 0.12);
border-radius: 4px; }

.modal-label { margin-bottom: 30px; font-family: Roboto; font-style: normal; font-weight: bold;
font-size: 20px; line-height: 23px; text-align: center; letter-spacing: 0.03rem;

color: var(--title-text-color); }

.form-field { position: relative; }

.form-field:nth-child(-n + 3) { margin-bottom: 28px; }

.form-input, .comment { width: 100%; margin: 0; padding: 11px 16px 11px 42px; outline: none; font:
inherit; border-radius: 4px; border: 1px solid rgba(33, 33, 33, 0.2); font-size: 12px; color:
var(--primary-text-color); transition: border 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.comment { resize: none; }

.form-input:focus, .comment:focus, .form-input:not(:placeholder-shown),
.comment:not(:placeholder-shown) { border: 1px solid var(--accent-color); }

.form-label, .form-label-comment { position: absolute; font-size: 12px; line-height: 14px;
letter-spacing: 0.01rem; transform: translateY(-50%);

transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.form-label { top: 50%; left: 42px; }

.form-label-comment { top: 12px; left: 16px; transform: translateY(0%);

transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.form-input:focus + .form-label, .form-input:not(:placeholder-shown) + .form-label { color:
var(--accent-color); transform: translateY(-40px) translateX(-26px); }

.comment:focus + .form-label-comment { color: var(--accent-color); transform: translateY(-32px); }

.icon-modal { position: absolute; top: 50%; left: 16px;

transform: translateY(-50%);

display: inline-block; width: 18px; height: 18px; fill: var(--title-text-color); transition: fill
250ms cubic-bezier(0.4, 0, 0.2, 1); }

.form-input:focus ~ .icon-modal, .form-input:not(:placeholder-shown) ~ .icon-modal { fill:
var(--accent-color); }

.modal-close { position: absolute; padding: 4.5px; top: 8px; right: 8px; width: 30px; height: 30px;
outline: none; background-color: var(--primary-white-color); border: 1px solid rgba(0, 0, 0, 0.1);
border-radius: 50%; }

.close-icon { color: var(--accent-color); transition: fill 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.modal-close:hover .close-icon, .modal-close:focus .close-icon { fill: var(--accent-color); }

.form-checkbox { margin-top: 20px; margin-bottom: 30px; display: flex; justify-content: center;
align-items: center; }

.checkbox-label { display: inline-flex; justify-content: center; align-items: center; font-size:
14px; line-height: 24px; }

.checkbox-link { margin-left: 5px; color: var(--accent-color); text-decoration-line: underline;

}

.checkbox { position: absolute; width: 1px; height: 1px; margin: -1px; border: 0; padding: 0; clip:
rect(0 0 0 0); overflow: hidden; }

.checkbox-label::before { content: ' '; display: inline-block; width: 16px; height: 16px;
margin-right: 8px;

border: 2px solid #2a2a2a; border-radius: 2px;

transition: transform 250ms cubic-bezier(0.4, 0, 0.2, 1); }

.checkbox:checked ~ .checkbox-label::before { transform: scale(1.1); border-color: transparent;
background-color: var(--accent-color); background-image: url(../image/iconCheck.svg);
background-size: contain; background-origin: border-box; }
