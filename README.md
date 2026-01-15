<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shoyguer - Game Developer</title>
    <meta name="description" content="Programmer, Game Designer and Godot Plugin Creator">
    
    <link rel="icon" type="image/x-icon" href="media/favicon/favicon.ico">
    <link rel="icon" type="image/png" sizes="32x32" href="media/favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="media/favicon/favicon-16x16.png">
    <link rel="apple-touch-icon" sizes="180x180" href="media/favicon/apple-touch-icon.png">
    <link rel="manifest" href="media/favicon/site.webmanifest">
    
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Kanit:wght@300;400;500&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="css/variables.css?v=1.0.23">
    <link rel="stylesheet" href="css/reset.css?v=1.0.23">
    <link rel="stylesheet" href="css/animations.css?v=1.0.23">
    <link rel="stylesheet" href="css/components.css?v=1.0.23">
    <link rel="stylesheet" href="css/layout.css?v=1.0.23">
    <link rel="stylesheet" href="css/responsive.css?v=1.0.23">
    <link rel="stylesheet" href="css/resume.css?v=1.0.23">
</head>
<body>
    
    <div id="header-placeholder"></div>

    <section id="home" class="hero-banner">
        <div class="hero-bg-parallax"></div>
        <canvas id="bg-canvas"></canvas>
        <div class="banner-content">
            <div class="banner-left fade-in">
                <ul class="hero-roles-list scroll-reveal">
                    <li data-i18n="hero.role1">Programmer.</li>
                    <li data-i18n="hero.role2">Game Designer.</li>
                    <li data-i18n="hero.role3">UI Designer.</li>
                </ul>
            </div>
            <div class="banner-center">
            </div>
            <div class="banner-right scroll-reveal">
                <a href="contact.html" class="btn btn-contact" data-i18n="hero.cta">Contact me</a>
                <p data-i18n="hero.sub">Need a game developer?</p>
            </div>
        </div>
    </section>

    <main class="main-column">
        <div class="digital-thread"></div>

        <section id="section-profile" class="content-section">
            <div class="hero-unified fade-in">

                <div class="hero-profile-header">
                    <div class="profile-avatar-wrapper">
                        <img src="media/profile.webp" alt="Lucas Melo" class="profile-avatar-large">
                    </div>
                    <div class="hero-header-text">
                        <h1 class="shoyguer-reveal-trigger">
                            <span class="name-part">Lucas</span>
                            <span class="nickname-wrapper">
                                <span class="nickname-content">"<span class="accent-text">Shoyguer</span>"</span>
                            </span>
                            <span class="name-part">Melo</span>
                        </h1>

                        <div class="header-meta-row">
                            <!-- Pronunciation -->
                            <div class="info-item">
                                <svg id="pronunciation-icon" class="detail-icon" style="cursor: pointer;" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" aria-label="Play pronunciation"><path d="M11 5L6 9H2v6h4l5 4V5z"/><path d="M15.54 8.46a5 5 0 0 1 0 7.07"/><path d="M19.07 4.93a10 10 0 0 1 0 14.14"/></svg>
                                <span>/ʃɔɪ.ɡər/ • “Shoy-guer”</span>
                            </div>

                            <!-- Languages -->
                            <div class="info-item">
                                <!-- Changed to languages icon (message bubble with text lines) -->
                                <svg class="detail-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 11.5a8.38 8.38 0 0 1-.9 3.8 8.5 8.5 0 0 1-7.6 4.7 8.38 8.38 0 0 1-3.8-.9L3 21l1.9-5.7a8.38 8.38 0 0 1-.9-3.8 8.5 8.5 0 0 1 4.7-7.6 8.38 8.38 0 0 1 3.8-.9h.5a8.48 8.48 0 0 1 8 8v.5z"></path></svg>
                                <span>EN / PT / ES</span>
                            </div>

                            <!-- Location -->
                            <div class="info-item">
                                <svg class="detail-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 0 1 18 0z"></path><circle cx="12" cy="10" r="3"></circle></svg>
                                <span data-i18n="profile.location">Brazil</span>
                            </div>

                            <!-- UTC -->
                            <div class="info-item">
                                <!-- Changed to clock icon -->
                                <svg class="detail-icon" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><circle cx="12" cy="12" r="10"></circle><polyline points="12 6 12 12 16 14"></polyline></svg>
                                <span id="local-time">--:-- UTC-3</span>
                            </div>
                        </div>
                        
                        <div class="gamification-stats fade-in">
                            <div class="stat-level">
                                <span class="label">LVL</span>
                                <span class="value">25</span>
                            </div>
                            <div class="stat-bars">
                                <div class="bar-container prog-bar" title="Programming: 91%">
                                    <div class="bar-fill"></div>
                                </div>
                                <div class="bar-container ui-bar" title="UI Design: 60%">
                                    <div class="bar-fill"></div>
                                </div>
                                <div class="bar-container design-bar" title="Game Design: 74%">
                                    <div class="bar-fill"></div>
                                </div>
                            </div>
                            <div class="class-badge">DEV</div>
                        </div>

                        <div class="social-links-unified">
                            <a href="https://github.com/shoyguer" target="_blank" class="icon-btn" aria-label="GitHub">
                                <img src="https://cdn.simpleicons.org/github/white" alt="GitHub">
                            </a>
                            <a href="https://shoyguer.itch.io/" target="_blank" class="icon-btn" aria-label="Itch.io">
                                <img src="https://cdn.simpleicons.org/itchdotio/FA5C5C" alt="Itch.io">
                            </a>
                            <a href="https://www.linkedin.com/in/lucasfeli74/" target="_blank" class="icon-btn" aria-label="LinkedIn">
                                <img src="https://cdn.jsdelivr.net/npm/simple-icons@v10/icons/linkedin.svg" alt="LinkedIn" class="social-icon">
                            </a>

                            <!-- Email -->
                            <a href="mailto:contact@shoyguer.com" class="social-display-item">
                                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="social-icon-svg"><path d="M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z"></path><polyline points="22,6 12,13 2,6"></polyline></svg>
                                <span>contact@shoyguer.com</span>
                            </a>
                            
                            <!-- Discord (Not clickable) -->
                            <div class="social-display-item">
                                <img src="https://cdn.simpleicons.org/discord/white" alt="Discord">
                                <span>shoyguer</span>
                            </div>

                        </div>
                    </div>
                </div>

                <hr class="hero-separator">

                <div class="tech-stack-section">
                    <div class="tech-section-header">
                        <h3 data-i18n="tech.title">Technologies</h3>
                    </div>
                    <div class="tech-category">
                        <h4 data-i18n="tech.engines">Game Engines</h4>
                        <div class="tech-icons">
                            <a href="https://godotengine.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/godot/godot-original.svg" alt="Godot" title="Godot Engine"></a>
                            <a href="https://gamemaker.io/" target="_blank"><img src="https://cdn.simpleicons.org/gamemaker/FFFFFF" alt="GameMaker" title="GameMaker Studio"></a>
                        </div>
                    </div>

                    <div class="tech-category">
                        <h4 data-i18n="tech.prog">Programming</h4>
                        <div class="tech-icons">
                            <a href="https://learn.microsoft.com/en-us/dotnet/csharp/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" title="C#"></a>
                            <a href="https://isocpp.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" title="C++"></a>
                            <a href="https://www.python.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" title="Python"></a>
                            <a href="https://www.java.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java"></a>
                            <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" title="JavaScript"></a>
                            <a href="https://developer.mozilla.org/en-US/docs/Web/HTML" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" title="HTML5"></a>
                            <a href="https://developer.mozilla.org/en-US/docs/Web/CSS" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" title="CSS3"></a>
                        </div>
                    </div>

                    <div class="tech-category">
                        <h4 data-i18n="tech.tools">Tools</h4>
                        <div class="tech-icons">
                            <a href="https://git-scm.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git"></a>
                            <a href="https://github.com/" target="_blank"><img src="https://cdn.simpleicons.org/github/white" alt="GitHub" title="GitHub"></a>
                            <a href="https://wordpress.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/wordpress/wordpress-plain.svg" alt="WordPress" title="WordPress"></a>
                            <a href="https://firebase.google.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/firebase/firebase-plain.svg" alt="Firebase" title="Firebase"></a>
                            <a href="https://www.salesforce.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/salesforce/salesforce-plain.svg" alt="Salesforce" title="Salesforce"></a>
                            <a href="https://www.mysql.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" title="MySQL"></a>
                            <a href="https://mariadb.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mariadb/mariadb-original.svg" alt="MariaDB" title="MariaDB"></a>
                            <a href="https://www.sqlite.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sqlite/sqlite-original.svg" alt="SQLite" title="SQLite"></a>
                        </div>
                    </div>

                    <div class="tech-category">
                        <h4 data-i18n="tech.design">Design / Art</h4>
                        <div class="tech-icons">
                            <a href="https://www.adobe.com/products/photoshop.html" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-original.svg" alt="Photoshop" title="Adobe Photoshop"></a>
                            <a href="https://www.adobe.com/products/illustrator.html" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/illustrator/illustrator-original.svg" alt="Illustrator" title="Adobe Illustrator"></a>
                            <a href="https://www.figma.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" alt="Figma" title="Figma"></a>
                            <a href="https://www.canva.com/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/canva/canva-original.svg" alt="Canva" title="Canva"></a>
                            <a href="https://www.gimp.org/" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gimp/gimp-original.svg" alt="Gimp" title="GIMP"></a>
                            <a href="https://www.aseprite.org/" target="_blank"><img src="https://cdn.simpleicons.org/aseprite/7D929E" alt="Aseprite" title="Aseprite"></a>
                        </div>
                    </div>

                    <div class="tech-category">
                        <h4 data-i18n="tech.task">Task Management</h4>
                        <div class="tech-icons">
                            <a href="https://clickup.com/" target="_blank"><img src="https://cdn.simpleicons.org/clickup/7B16FF" alt="ClickUp" title="ClickUp"></a>
                            <a href="https://www.atlassian.com/software/jira" target="_blank"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg" alt="Jira" title="Jira"></a>
                            <a href="https://www.notion.so/" target="_blank"><img src="https://cdn.simpleicons.org/notion/white" alt="Notion" title="Notion"></a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <section id="projects" class="content-section">
            <div class="section-header fade-in">
                <h2 data-i18n="projects.title">Game Projects</h2>
                <div class="line"></div>
            </div>
            
            <div class="projects-grid">
                <!-- Shattered Paradise -->
                <a href="https://shattered-paradise.com/" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper perfect-fit">
                        <img src="media/games/shattered_paradise.webp" alt="Shattered Paradise Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status active" data-i18n="projects.current">Current Project</div>
                            <span class="card-year">2025 - <span data-i18n="resume.date.now">Now</span></span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.prog_design">Programmer & Game Designer</p>
                        <h3>Shattered Paradise</h3>
                        <p data-i18n="project.shattered">A tradional roguelike game where you explore a damned world.</p>
                        <div class="card-platforms">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" title="Windows" class="platform-windows">
                        </div>
                        <span class="card-link"><span data-i18n="link.website">Visit Website</span> <span class="arrow">→</span></span>
                    </div>
                </a>

                <!-- Tribe of the Accord -->
                <a href="https://store.steampowered.com/app/2551790/Tribe_of_the_Accord/" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper perfect-fit">
                        <img src="media/games/tribe_of_the_accord.webp" alt="Tribe of the Accord Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status past" data-i18n="projects.past">Past Work</div>
                            <span class="card-year">2024</span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.prog_jr_design">Programmer & Jr Game Designer</p>
                        <h3>Tribe of the Accord</h3>
                        <p data-i18n="project.tribe">A action-adventure game where you play with Adira, a young huntress on a quest to rescue your father.</p>
                        <div class="card-platforms">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" title="Windows" class="platform-windows">
                            <img src="https://cdn.simpleicons.org/linux/FFFFFF" alt="Linux" title="Linux">
                        </div>
                        <span class="card-link"><span data-i18n="link.steam">View on Steam</span> <span class="arrow">→</span></span>
                    </div>
                </a>

                <!-- Fight Life: Legacy -->
                <a href="https://store.steampowered.com/app/4240750/Fight_Life_Legacy/" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper perfect-fit">
                         <img src="media/games/fight_legacy.webp" alt="Fight Life: Legacy Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status past" data-i18n="projects.past">Past Work</div>
                            <span class="card-year">2024 - 2025</span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.prog_design_ui">Programmer, Game Designer & UI Artist</p>
                        <h3>Fight Life: Legacy</h3>
                        <p data-i18n="project.fight">A story-rich visual novel, where your father, a famouse MMA fighter had disappeared mysteriously. So you battle your way to the top of MMA fighters, and investigate what happened to your dad.</p>
                        <div class="card-platforms">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" title="Windows" class="platform-windows">
                            <img src="https://cdn.simpleicons.org/linux/FFFFFF" alt="Linux" title="Linux">
                            <img src="https://cdn.simpleicons.org/android/FFFFFF" alt="Android" title="Android">
                        </div>
                        <span class="card-link"><span data-i18n="link.steam">View on Steam</span> <span class="arrow">→</span></span>
                    </div>
                </a>

                <!-- Turn Based Battle -->
                <a href="https://shoyguer.itch.io/turn-based-battle" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper with-blur-bg" style="background: linear-gradient(135deg, #141117, #2e3a40);">
                        <img src="media/games/turn_based_battle.png" alt="Turn Based Battle Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status past" data-i18n="projects.past">Past Work</div>
                            <span class="card-year">2024</span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.prog_design_ui">Programmer, Game Designer & UI Artist</p>
                        <h3>Ponies and Jellykin</h3>
                        <p data-i18n="project.ponies">A monster-taming, virtual-pet, turn based battle game. You can play here the Turn Based Battle system.</p>
                        <div class="card-platforms">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" title="Windows" class="platform-windows">
                        </div>
                        <span class="card-link"><span data-i18n="link.itch">View on Itch.io</span> <span class="arrow">→</span></span>
                    </div>
                </a>

                <!-- Common Signal -->
                <a href="https://shoyguer.itch.io/common-signal" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper with-blur-bg" style="background: linear-gradient(135deg, #3c051c, #210515);">
                        <img src="media/games/common_signal.png" alt="Common Signal Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status jam" data-i18n="projects.jam">Game Jam</div>
                            <span class="card-year">2021</span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.creator">Creator & Generalist</p>
                        <h3>Common Signal</h3>
                        <p data-i18n="project.common">Space-impact clone, with local multiplayer functionality, made for Opera GX Game in 2021. Made with @ArtwaFam.</p>
                        <div class="card-platforms">
                            <img src="https://img.icons8.com/ios-filled/50/ffffff/internet.png" alt="Web" title="Web Browser">
                        </div>
                        <span class="card-link"><span data-i18n="link.play_itch">Play on Itch.io</span> <span class="arrow">→</span></span>
                    </div>
                </a>

                <!-- Luke n Beth -->
                <a href="https://shoyguer.itch.io/luke-n-beth" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper with-blur-bg" style="background: linear-gradient(135deg, #162c11, #411e0f);">
                        <img src="media/games/luke_n_beth.png" alt="Luke n Beth Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status past" data-i18n="projects.mvp">MVP Project</div>
                            <span class="card-year">2021</span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.creator">Creator & Generalist</p>
                        <h3>Luke n Beth</h3>
                        <p data-i18n="project.luke">MVP project of The Binding of Isaac inspired game, with 2 different characters, and different items.</p>
                        <div class="card-platforms">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" title="Windows" class="platform-windows">
                            <img src="https://img.icons8.com/ios-filled/50/ffffff/internet.png" alt="Web" title="Web Browser">
                        </div>
                        <span class="card-link"><span data-i18n="link.itch">View on Itch.io</span> <span class="arrow">→</span></span>
                    </div>
                </a>

                <!-- Deep in the Treasure -->
                <a href="https://shoyguer.itch.io/deep-in-the-treasure" target="_blank" class="card project-card fade-up" style="text-decoration: none; color: inherit;">
                    <div class="card-image-wrapper with-blur-bg" style="background: linear-gradient(135deg, #383838, #544400);">
                        <img src="media/games/deep_in_the_treasure.png" alt="Deep in the Treasure Gameplay" loading="lazy">
                    </div>
                    <div class="card-content">
                        <div class="card-header-row">
                            <div class="card-status past" data-i18n="projects.uni">University Project</div>
                            <span class="card-year">2018</span>
                        </div>
                        <p class="card-role" data-i18n="projects.role.creator">Creator & Generalist</p>
                        <h3>Deep in the Treasure</h3>
                        <p data-i18n="project.deep">University activity involving oblique launching.
                            The game includes more than 10 different floors, with 4 stages and different types of enemies with different mechanics, scoring system, record, etc.</p>
                        <div class="card-platforms">
                            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/windows8/windows8-original.svg" alt="Windows" title="Windows" class="platform-windows">
                        </div>
                        <span class="card-link"><span data-i18n="link.itch">View on Itch.io</span> <span class="arrow">→</span></span>
                    </div>
                </a>
            </div>
        </section>

        <section id="plugins" class="content-section">
            <div class="section-header fade-in">
                <h2 data-i18n="plugins.title">Godot Plugins</h2>
                <div class="line"></div>
            </div>

            <div class="plugins-grid stagger-children">
                <!-- Stat Pool -->
                <a href="https://github.com/shoyguer/stat-pool" target="_blank" class="plugin-card fade-up">
                    <div class="plugin-header">
                        <div class="plugin-image-wrapper">
                            <img src="media/plugins/stat_pool.webp" alt="Stat Pool Plugin" loading="lazy">
                        </div>
                        <div class="plugin-info">
                            <h3>stat-pool <span class="plugin-badge created" data-i18n="plugins.badge.created">Created</span></h3>
                            <p data-i18n="plugin.statpool">Godot Plugin for handling Stat Pools, such as: Health, Stamina, Mana, Hunger, Skills and even Money systems.</p>
                        </div>
                    </div>
                    <div class="plugin-meta">
                        <div class="plugin-tech">
                            <span class="tag-godot">Godot 4.5</span>
                            <span class="tag-godot">GDExtension</span>
                            <span>Resource</span>
                            <span>Stat Management</span>
                        </div>
                        <div class="plugin-arrow">↗</div>
                    </div>
                </a>

                <!-- Seed -->
                <a href="https://github.com/shoyguer/seed" target="_blank" class="plugin-card fade-up">
                    <div class="plugin-header">
                        <div class="plugin-image-wrapper">
                            <img src="media/plugins/seed.webp" alt="Seed Plugin" loading="lazy">
                        </div>
                        <div class="plugin-info">
                            <h3>seed <span class="plugin-badge created" data-i18n="plugins.badge.created">Created</span></h3>
                            <p data-i18n="plugin.seed">Godot Plugin for handling Seed generation easily. Focused on optimization.</p>
                        </div>
                    </div>
                    <div class="plugin-meta">
                        <div class="plugin-tech">
                            <span class="tag-godot">Godot 4.5</span>
                            <span class="tag-godot">GDExtension</span>
                            <span>RNG</span>
                            <span>Seed Generation</span>
                            <span>RefCounted</span>
                        </div>
                        <div class="plugin-arrow">↗</div>
                    </div>
                </a>

                <!-- Time Tick -->
                <a href="https://github.com/shoyguer/time-tick" target="_blank" class="plugin-card fade-up">
                    <div class="plugin-header">
                        <div class="plugin-image-wrapper">
                            <img src="media/plugins/time_tick.webp" alt="Time Tick Plugin" loading="lazy">
                        </div>
                        <div class="plugin-info">
                            <h3>time-tick <span class="plugin-badge created" data-i18n="plugins.badge.created">Created</span></h3>
                            <p data-i18n="plugin.timetick">Godot Plugin for handling tick system, and time system with custom simple and complex time units, and hierarchies.</p>
                        </div>
                    </div>
                    <div class="plugin-meta">
                        <div class="plugin-tech">
                            <span class="tag-godot">Godot 4.5</span>
                            <span class="tag-godot">GDExtension</span>
                            <span>Modular Time Management System</span>
                            <span>RefCounted</span>
                        </div>
                        <div class="plugin-arrow">↗</div>
                    </div>
                </a>

                <!-- Advanced Button -->
                <a href="https://github.com/shoyguer/advanced-button" target="_blank" class="plugin-card fade-up">
                    <div class="plugin-header">
                        <div class="plugin-image-wrapper">
                            <img src="media/plugins/advanced_button.webp" alt="Advanced Button Plugin" loading="lazy">
                        </div>
                        <div class="plugin-info">
                            <h3>advanced-button <span class="plugin-badge created" data-i18n="plugins.badge.created">Created</span></h3>
                            <p data-i18n="plugin.advbutton">Godot plugin giving you a complete and customizable button, with easy to use label, texture, stylebox and modulation, with interaction implemented out-of-the-box.</p>
                        </div>
                    </div>
                    <div class="plugin-meta">
                        <div class="plugin-tech">
                            <span class="tag-godot">Godot 4.x</span>
                            <span class="tag-godot">GDScript</span>
                            <span>UI</span>
                            <span>Modular Button</span>
                        </div>
                        <div class="plugin-arrow">↗</div>
                    </div>
                </a>

                <!-- SmoothScroll -->
                <a href="https://github.com/SpyrexDE/SmoothScroll" target="_blank" class="plugin-card fade-up">
                    <div class="plugin-header">
                        <div class="plugin-image-wrapper">
                            <img src="media/plugins/smooth_scroll.webp" alt="SmoothScroll Plugin" loading="lazy">
                        </div>
                        <div class="plugin-info">
                            <h3>SmoothScroll <span class="plugin-badge contributed" data-i18n="plugins.badge.contributed">Contributed</span></h3>
                            <p data-i18n="plugin.smoothscroll">Addon for the Godot Game Engine that adds a SmoothScrollContainer.</p>
                        </div>
                    </div>
                    <div class="plugin-meta">
                        <div class="plugin-tech">
                            <span class="tag-godot">Godot 4.x</span>
                            <span class="tag-godot">GDScript</span>
                            <span>UI</span>
                            <span>Scroll</span>
                        </div>
                        <div class="plugin-arrow">↗</div>
                    </div>
                </a>

                <!-- Dialogue Manager 3 -->
                <a href="https://github.com/nathanhoad/godot_dialogue_manager" target="_blank" class="plugin-card fade-up">
                    <div class="plugin-header">
                        <div class="plugin-image-wrapper">
                            <img src="media/plugins/dialogue_manager_3.webp" alt="Dialogue Manager Plugin" loading="lazy">
                        </div>
                        <div class="plugin-info">
                            <h3>Dialogue Manager 3 <span class="plugin-badge contributed" data-i18n="plugins.badge.contributed">Contributed</span></h3>
                            <p data-i18n="plugin.dialogue">A powerful nonlinear dialogue system for Godot.</p>
                        </div>
                    </div>
                    <div class="plugin-meta">
                        <div class="plugin-tech">
                            <span class="tag-godot">Godot 4.x</span>
                            <span class="tag-godot">GDScript</span>
                            <span>Dialogue System</span>
                        </div>
                        <div class="plugin-arrow">↗</div>
                    </div>
                </a>
            </div>
        </section>

        <section id="resume" class="content-section">
            <div class="section-header fade-in">
                <h2 data-i18n="resume.title">Resume</h2>
                <div class="line"></div>
            </div>

            <div class="resume-grid">
                <div class="resume-column stagger-children">
                    <div class="resume-category-title">
                        <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M22 10v6M2 10l10-5 10 5-10 5z"/><path d="M6 12v5c3 3 9 3 12 0v-5"/></svg>
                        <h3 data-i18n="resume.education">Education</h3>
                    </div>

                    <div class="resume-item">
                        <div class="resume-logo">
                            <img src="media/companies/cruzeiro_do_sul.webp" alt="Cruzeiro do Sul">
                        </div>
                        <div class="resume-content">
                            <h4 class="resume-institution-name">Cruzeiro do Sul University</h4>
                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.edu.game_design">Post degree in Game Design</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.jan_2024_dec_2025">Jan 2024 – Dec 2025</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="resume-item">
                        <div class="resume-logo">
                            <img src="media/companies/sao_judas.webp" alt="São Judas Tadeu">
                        </div>
                        <div class="resume-content">
                            <h4 class="resume-institution-name">São Judas Tadeu University</h4>
                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.edu.comp_sci">Bachelor in Computer Science</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.jan_2018_dec_2021">Jan 2018 – Dec 2021</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="resume-item">
                        <div class="resume-logo">
                            <img src="media/companies/etec.webp" alt="ETEC">
                        </div>
                        <div class="resume-content">
                            <h4 class="resume-institution-name">ETEC Takashi Morita</h4>
                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.edu.electronics">Electronics Technician Certificate</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.jan_2015_dec_2017">Jan 2015 – Dec 2017</span>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="resume-column stagger-children">
                    <div class="resume-category-title">
                        <svg class="icon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="2" y="7" width="20" height="14" rx="2" ry="2"/><path d="M16 21V5a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v16"/></svg>
                        <h3 data-i18n="resume.experiences">Experiences</h3>
                    </div>

                    <div class="resume-item">
                        <div class="resume-logo">
                        </div>
                        <div class="resume-content">
                            <h4 class="resume-institution-name">Self-employed</h4>
                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.exp.game_dev">Game Designer & Developer</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.jan_2024_present">Jan 2024 - Present</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="resume-item">
                        <div class="resume-logo">
                            <img src="media/companies/gentrop.webp" alt="Gentrop">
                        </div>
                        <div class="resume-content">
                            <h4 class="resume-institution-name">Gentrop</h4>
                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.exp.solution_analyst">Solution Analyst</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.may_2022_may_2024">May 2022 - May 2024</span>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="resume-item">
                        <div class="resume-logo">
                            <img src="media/companies/select.webp" alt="SELECT">
                        </div>
                        <div class="resume-content">
                            <h4 class="resume-institution-name">SELECT Humans for Energy</h4>
                            
                            <!-- Role 1 -->
                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.exp.junior_analyst">Junior Development Analyst</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.may_2021_may_2022">May 2021 - May 2022</span>
                                </div>
                            </div>

                            <div class="resume-role-group">
                                <span class="resume-role-title" data-i18n="resume.exp.intern">IT Intern</span>
                                <div class="resume-date">
                                    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"><rect x="3" y="4" width="18" height="18" rx="2" ry="2"></rect><line x1="16" y1="2" x2="16" y2="6"></line><line x1="8" y1="2" x2="8" y2="6"></line><line x1="3" y1="10" x2="21" y2="10"></line></svg>
                                    <span data-i18n="resume.date.may_2019_may_2021">May 2019 - May 2021</span>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </section>

    </main>

    <div id="footer-placeholder"></div>
    
    <script src="js/translations.js?v=1.0.23"></script>
    <script src="js/localization.js?v=1.0.23"></script>
    <script src="js/hero-effects.js?v=1.0.23"></script>
    <script src="js/animations.js?v=1.0.23"></script>
    <script src="js/navigation.js?v=1.0.23"></script>
    <script src="js/card-effects.js?v=1.0.23"></script>
    <script src="js/pronunciation.js?v=1.0.23"></script>
</body>
</html>
