# nuxt-bootstrap

## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out [Nuxt.js docs](https://nuxtjs.org).


# nuxt docs --- concepts temdeglel

Vue-n app-d SSR hiih bolomjiig olgdog framework

Advantage:
- SSR
- SEO (head, title, meta zergiig control hiihed sain)
- Simple page routing

Features:
- Vue-router, vuex, vue-meta zereg n bundle hiigdtsn baidag.
- Universal uu SPA yu gedgee songoj bolno
- UI, Backend framework-uudiig songoj bolno

Directories:
- layouts: navbar,header,main, footer zereg aguulj bolno
- assets: less, sass, jss, imgs, fonts file ene dotor bairlana.
- middleware: huudas render hiigdehees omno ajillah custom functionuudiig end bichij bolno 
- pages: tuhain web-n huudasnuud ene hesegt baina. automatic route hiideg
- components: component-uuda end bichij bolno 
- plugins: plugins
- static: ene dotor bga file-uud root dir dr bga met hadgalagddg. robots.txt zereg file uud hadgalj bolno
- store: vuex store file ene dotor aguulagdana

head method:
- ene dotor tuhain page-n title, meta zergiig bichih bolomjtoi

nuxt.config.js:
- mode: universal spa gedgiig tohiruulna
- head: title,meta,link
- axios: host, token etc tohiruulj bolno
- build: build hiihed tohiruulah zvils
- alias: js, css alias uudiig todorhoilno
- css: global aar todorhoiloh css file module library zergiig tohiruulna
- dev: dev/production mode zergiig todorhoilno
- env: tuhain project ajillahad shaardagdah orchnii huwisagchiig todorhoilno. runtime environment variables huwid runtime config shaardlagatai.
- dir: nuxt.js directory nernvvdiig dahin todorhoiloh bolomj olgodog.
- srcDir: nuxt.js app-n assets,components, layouts, pages zereg directory-iin bairshliig solih, uur directory dotor bagtslasan bol ene tohirgoog
          hiij todorhoilno. jisheelbel srcDir: 'client/' gewel deerh pages, plugins, layouts zergiig client directory dotroos haina.
- server: nuxt.js app-n serveriin holboltuudiig todorhoiloh bolomjiig olgodog.
- router: nuxt.js default vue router tohirgoog ene hesegt overwrite hiih bolomjtoi
- plugins: vue app ajillahaas omno ajillah js plugins todorhoilno.
- modules: nuxtjs module uuriin project dree nemeh eswel nemegdsen bol ene hesegt tohiruulagdana.
- modulesDir: module directory haana bairlahiig zaaj ogno.
- loading: nuxt.js heregledeg loading component-g customize hiih bolomj olgono.
- generate: 
- runtimeconfig: .env-g ilvv hurdan bogood ayulgvi ajilluulahin tuld nuxt deer nemegdsn. root dir deeer .env orgotgoltei file bh l ym bol automatic-r
                  process.env boldog bogood nuxt.config/serverMiddleware bolon busad import hiisen file ruu handah bolomjtoi boldog. public bolon private gej 2 runtime config baigaa

Nuxt context:
- env*: nuxt.config.js file deer todorhoilogddg env variables //obj
- error: error garwal error page haruulna. store luu err msg ywuulna //function
- store: vuex store tohiruulagdsn bwl ajillana. Vuex store instance 
- res && req: http response && request from nodejs server 
- beforeNuxtRender(fn): client tald renderlegdsen __nuxt__ variable oorchilno. ansync baij boldog //function
- nuxtState: hydration hiihees omno client tald baih nuxtstate objectiin handah erh. universal mode bh vyin l heregjdeg. BeforeNuxtRender ashiladag pluginuudad heregte  // obj
- from: route haanaas navigate hiisen 
- params: route.params-n alias  //obj
- query: route.query-n alias  //obj
- route: vue router instance. nuxt n pages dir dotor baigaa .vue orgotgoltoi fail bvreer automatically route vvsgedeg.
- $config: Access runtime config
- isDev* &&  isHMR: dev mode dr bnu vgvi yu gedgiig shalgana. && webpack hot module reload-s duudagdsn replacement-g method bnu middleware bnu gedgiig shalgana //boolean
- app: root Vue instance options
- redirect: status code-s shaltgaalt oor route rvv redirect hiine. //function

### Source : https://nuxtjs.org/

# vue-bootstrap

Bootstrap vue ni bootstrap v4 ashiglasan bogood vvnii tuslamjtai responsive web app hylbaraad hiih bolomjtoi. Bootstrap bol responsive, mobile first site hiideg hamgiin aldartai framework. modular uchir import hiihed l hangalttai.

- components: Bootstrap vue-n gargaj ogson componentvvd
- directives: hover, popover, scrollspy, toggle, tooltip visible gesen directive-uud baigaa tus2 uuriin gesen zoriulaltuudtai.

size props:
- sm: small
- lg: large
- w: width
- h: height 

spacing classes:
- m: margin
- p: padding

- t: margin-top/padding-top etc hereglene
- b: bottom
- l: left
- r: right
- x: left, right hoyulang n 
- y: top, bottom hoyulang n

- 0: margin, padding utgiig 0 gej ogoh vyd // $spacer * 0
- 1: .25
- 2: .5
- 3:
- 4: 1.5
- 5: 3

- example: mt-0 {margin-top: 0}, px-2 {padding-left: ($spacer * 0.5), padding-right: ($spacer * 0.5) }, p-3 {padding: $spacer} ...
- mx-auto: horizontal center hiideg. 
