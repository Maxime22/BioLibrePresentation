# BioLibre

Biolibre is a website (blog) to share positive articles with people and making their life easier. So the goal is to learn things or at least to have a good time. It is implemented with Symfony 5 (a french PHP framework), Bootstrap and it will then be gradually implemented with React.js (notably cause I worked during one year with these technologies in a startup and I love them).

Please find the website here : https://www.biolibre.fr/

If you have any questions, notably if you are a technical recruiter and you want to have access to the real BioLibre git (which is in private), contact me on the following address : sabouretmaxime@gmail.com

Here is the list of what I did for now and what I expect to do in the next few months :

- [x] Symfony 4.3 installation
- [x] Symfony 5.0 update (01/02/2020)
- [x] Do not have config, .env, public files on the git
- [x] Create an configure on the site a webmail with the domain name
- [x] Create and implement the entities (superThemeRepository, theme, category, contact, comments, user...)
- [x] Create submission form for the user (2 passwords check + email validation + remember me)
- [x] Create an isActive parameter for the user to ban the users who didn't activate their account
- [x] Create a global analysis entity
- [x] Number of viewers (AJAX calls from the base template, number of visits managed by the session storage)
- [x] Number of connected people (AJAX call from the base template)
- [x] My own log system with monolog.yaml config, logs implemented in the controllers
- [x] Home page, theme page, article page
- [x] Most viewed articles (nb_views in article entity with AJAX call to fill it)
- [x] Contact us mail form
- [x] Admin interface
- [x] Create, modify and delete all entities in the admin
- [x] User roles management my super admin
- [x] A user with the role writer can only see his own articles and can't delete them, he can add categories
- [x] Comments reporting
- [x] Translation available on all the site (trad attributes for each entity), in english for now, it is possible to write an article just in french but not translations will be available then
- [x] Dedicated server (online.net)
- [x] Website online managed from the git in local
- [x] HTTPS with certbot
- [x] Website dev.biolibre.fr to test before prod
- [x] Responsive for mobile and tablets (approximately)
- [x] Mixpanel
- [x] Improving metas
- [x] Reorganise articles in excel to write them
- [x] Netflix carrousel on the main page
- [x] Logo refont
- [x] SFTP Filezilla management for pictures
- [x] Propose other articles linked to the article in lecture
- [x] Write articles
- [x] Searchbar
- [x] Profile page for people to share their social networks and their website
- [x] Webpack Encore implementation with for CSS and js files, better for React inclusion
- [x] Lazy load with vanilla-lazyload
- [x] React.js implementation on some pages with the site in API gradually (maybe not totally because of the SEO), notably paging
- [ ] Test implementation (in Symfony with Php Unit and React.js with Jest)
- [ ] Little games in JS in the website
- [ ] Make a mobile app in React Native
