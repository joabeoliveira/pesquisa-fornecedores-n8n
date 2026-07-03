# Exported Chat from Chrome DevTools AI Assistance

**Export Timestamp (UTC):** 2026-07-02T23:24:32.200Z

---

## User

extraia por favor o cURL com cookie e CRFS para eu importar para o nó http request do n8n para pesquisar produtos no site americanas.com.br

## AI

### Analyzing data

**Request:**
````
Request URL: https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio

Request headers:
:authority: www.americanas.com.br
:method: GET
:path: /moveis/cadeira/cadeira-de-escritorio
:scheme: https
accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
accept-encoding: gzip, deflate, br, zstd
accept-language: pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7
cache-control: max-age=0
cookie: <redacted>
priority: <redacted>
referer: https://www.americanas.com.br/
sec-ch-ua: <redacted>
sec-ch-ua-mobile: <redacted>
sec-ch-ua-platform: <redacted>
sec-fetch-dest: <redacted>
sec-fetch-mode: <redacted>
sec-fetch-site: <redacted>
sec-fetch-user: <redacted>
upgrade-insecure-requests: 1
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/149.0.0.0 Safari/537.36
````

**Response:**
````
Response headers:
age: 31
cache-control: s-maxage=31536000, stale-while-revalidate=31536000
content-encoding: gzip
content-type: text/html; charset=utf-8
date: Thu, 02 Jul 2026 23:12:20 GMT
etag: <redacted>
server: CloudFront
vary: Accept-Encoding
via: 1.1 7212e65fd1e4df6d4dd22c2288b21f7c.cloudfront.net (CloudFront)
x-amz-cf-id: <redacted>
x-amz-cf-pop: <redacted>
x-cache: <redacted>
x-envoy-upstream-service-time: <redacted>
x-nextjs-cache: <redacted>
x-powered-by: Next.js
x-vtex-janus-router-backend-app: <redacted>

Response body:
<!DOCTYPE html><html dir="ltr" lang="pt-BR"><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><script>var partytown={forward:[...["sendrc"],!window.location.search.includes('gtm_debug=')&&false?'dataLayer.push':null].filter(Boolean)}</script><script type="text/partytown">
            window.VTEX_METADATA = {account:'americanas', renderer: 'faststore'};
            window.sendrc=function(en,ed){window.NavigationCapture&&window.NavigationCapture.sendEvent(en,ed)};
          </script><script type="text/partytown" async="" src="https://io.vtex.com.br/rc/rc.js"></script><script type="text/javascript">
            (function(v,t,e,x,a,f,s){
              f=v.vtexaf=v.vtexaf||function(){(f.q=f.q||[]).push(arguments)}
              ;f.l=+new Date;s=t.createElement(e);s.async=!0;
              s.src=x;a=t.getElementsByTagName(e)[0];
              a.parentNode.insertBefore(s,a)
            })(window,document,'script','https://activity-flow.vtex.com/af/af.js');
          </script><script type="text/javascript">
            window.vtexaf('init', {
              account: 'americanas',
              env: 'vtexcommercestable',
              workspace: 'master'
            });
          </script><script async="">
            (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
            j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
            'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
            })(window,document,'script','dataLayer','GTM-5TPDVK2Z');
          </script><script type="text/javascript" src="https://reviews.konfidency.com.br/americanas/loader.js"></script><link rel="stylesheet" href="https://cdn.privacytools.com.br/public_api/banner/style/xz1N21419101.css?t=1"/><script type="text/javascript" src="https://cdn.privacytools.com.br/public_api/banner/autoblock/v2/kQWG21419101.js?t=1"></script><script type="text/javascript" src="https://cdn.privacytools.com.br/public_api/banner/script/bottom/xz1N21419101.js?t=1"></script><meta name="google-site-verification" content="9BlvZkcfeD56_XPs9GeY7fZaDxy2tXm_v4eQkv0zI6Q"/><script>!(function(w,p,f,c){c=w[p]=w[p]||{};c[f]=(c[f]||[])})(window,'partytown','forward');/* Partytown 0.6.4 - MIT builder.io */
!function(t,e,n,i,r,o,a,d,s,c,p,l){function u(){l||(l=1,"/"==(a=(o.lib||"/~partytown/")+(o.debug?"debug/":""))[0]&&(s=e.querySelectorAll('script[type="text/partytown"]'),i!=t?i.dispatchEvent(new CustomEvent("pt1",{detail:t})):(d=setTimeout(w,1e4),e.addEventListener("pt0",f),r?h(1):n.serviceWorker?n.serviceWorker.register(a+(o.swPath||"partytown-sw.js"),{scope:a}).then((function(t){t.active?h():t.installing&&t.installing.addEventListener("statechange",(function(t){"activated"==t.target.state&&h()}))}),console.error):w())))}function h(t){c=e.createElement(t?"script":"iframe"),t||(c.setAttribute("style","display:block;width:0;height:0;border:0;visibility:hidden"),c.setAttribute("aria-hidden",!0)),c.src=a+"partytown-"+(t?"atomics.js?v=0.6.4":"sandbox-sw.html?"+Date.now()),e.body.appendChild(c)}function w(t,n){for(f(),t=0;t<s.length;t++)(n=e.createElement("script")).innerHTML=s[t].innerHTML,e.head.appendChild(n);c&&c.parentNode.removeChild(c)}function f(){clearTimeout(d)}o=t.partytown||{},i==t&&(o.forward||[]).map((function(e){p=t,e.split(".").map((function(e,n,i){p=p[i[n]]=n+1<i.length?"push"==i[n+1]?[]:p[i[n]]||{}:function(){(t._ptf=t._ptf||[]).push(i,arguments)}}))})),"complete"==e.readyState?u():(t.addEventListener("DOMContentLoaded",u),t.addEventListener("load",u))}(window,document,navigator,top,window.crossOriginIsolated);document.currentScript.dataset.partytown="";</script><meta name="generated-at" content="2026-07-02T22:41:32.581Z"/><title>Cadeira Para Escritório Ergonômica, Presidente, Giratória e Mais: Promoção | Americanas</title><meta name="robots" content="index,follow"/><meta name="description" content="Na Americanas, você encontra cadeira de escritório ergonômica, presidente, giratória, preta, branca, rosa e muito mais em promoção. Confira!"/><meta property="og:title" content="Cadeira Para Escritório Ergonômica, Presidente, Giratória e Mais"/><meta property="og:description" content="Na Americanas, você encontra cadeira de escritório ergonômica, presidente, giratória, preta, branca, rosa e muito mais em promoção. Confira!"/><meta property="og:url" content="https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio"/><meta property="og:type" content="website"/><link rel="canonical" href="https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio"/><script type="application/ld+json">{"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","position":1,"item":"https://www.americanas.com.br/moveis","name":"Móveis"},{"@type":"ListItem","position":2,"item":"https://www.americanas.com.br/moveis/cadeira","name":"Cadeira"},{"@type":"ListItem","position":3,"item":"https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio","name":"Cadeira de escritório"}]}</script><link rel="preload" as="image" imageSrcSet="/_next/static/media/listIcon.4d69f34d.svg 1x, /_next/static/media/listIcon.4d69f34d.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLoginIconMobile.b078e2d1.svg 1x, /_next/static/media/storeLoginIconMobile.b078e2d1.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLogoIcon.0f542fa4.svg 1x, /_next/static/media/storeLogoIcon.0f542fa4.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLoginIcon.0af75623.svg 1x, /_next/static/media/storeLoginIcon.0af75623.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeFrontIcon.759623b8.svg 1x, /_next/static/media/storeFrontIcon.759623b8.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeWhishListIcon.0ddddf87.svg 1x, /_next/static/media/storeWhishListIcon.0ddddf87.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeCartIcon.46c2c513.svg 1x, /_next/static/media/storeCartIcon.46c2c513.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeRegionIcon.aaf1e87a.svg 1x, /_next/static/media/storeRegionIcon.aaf1e87a.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/modalCloseIcon.8bacd3b4.svg 1x, /_next/static/media/modalCloseIcon.8bacd3b4.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/linkIcon.dbb70f32.svg 1x, /_next/static/media/linkIcon.dbb70f32.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLinkIcon.7f5bb130.svg 1x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/greyHamburguerIcon.54572277.svg 1x, /_next/static/media/greyHamburguerIcon.54572277.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/greyArrowDownIcon.80ce865c.svg 1x, /_next/static/media/greyArrowDownIcon.80ce865c.svg 2x" fetchPriority="high"/><meta name="next-head-count" content="26"/><link rel="preconnect" href="https://americanas.vtexassets.com"/><link rel="dns-prefetch" href="https://americanas.vtexassets.com"/><meta name="storefront" content="fast_store"/><link rel="preconnect" href="https://fonts.googleapis.com"/><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous"/><link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&amp;family=Roboto+Flex:opsz,wght@8..144,100..1000&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet"/><noscript><link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&amp;family=Roboto+Flex:opsz,wght@8..144,100..1000&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet"/></noscript><link rel="preload" href="/_next/static/css/ddb4d27f04be367b.css" as="style"/><link rel="stylesheet" href="/_next/static/css/ddb4d27f04be367b.css" data-n-g=""/><link rel="preload" href="/_next/static/css/db6d65a93881bcc8.css" as="style"/><link rel="stylesheet" href="/_next/static/css/db6d65a93881bcc8.css" data-n-p=""/><link rel="preload" href="/_next/static/css/05b6df3951ba7e9e.css" as="style"/><link rel="stylesheet" href="/_next/static/css/05b6df3951ba7e9e.css" data-n-p=""/><link rel="preload" href="/_next/static/css/718d49681a48458e.css" as="style"/><link rel="stylesheet" href="/_next/static/css/718d49681a48458e.css" data-n-p=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/_next/static/chunks/polyfills-c67a75d1b6f99dc8.js"></script><script src="/_next/static/chunks/webpack-8e916de0c5788241.js" defer=""></script><script src="/_next/static/chunks/main-5611a9fe26819d2e.js" defer=""></script><script src="/_next/static/chunks/pages/_app-07b5522414db2dad.js" defer=""></script><script src="/_next/static/chunks/c78d26b1-fe043233b220ebfb.js" defer=""></script><script src="/_next/static/chunks/7102-be0000d0682872ec.js" defer=""></script><script src="/_next/static/chunks/6407-35ffec1a99a0fa9e.js" defer=""></script><script src="/_next/static/chunks/3105-37e4e05718827456.js" defer=""></script><script src="/_next/static/chunks/pages/%5B...slug%5D-c77cbab19ef9873c.js" defer=""></script><script src="/_next/static/WwoTUivG1rQUIEzlp3jMD/_buildManifest.js" defer=""></script><script src="/_next/static/WwoTUivG1rQUIEzlp3jMD/_ssgManifest.js" defer=""></script></head><body class="theme"><div id="__next"><a class="SkipToMai... <truncated>

Response status: 200 
Network request status: finished
````

**Timing:**
````
Queued at (timestamp): 0 s
Started at (timestamp): 1 ms
Queueing (duration): 1 ms
Connection start (stalled) (duration): 0.6 ms
Request sent (duration): 0.3 ms
Waiting for server response (duration): 19 ms
Content download (duration): 0.8 ms
Duration (duration): 23 ms
````

**Request initiator chain:**
````
- URL: https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/media/listIcon.4d69f34d.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLoginIconMobile.b078e2d1.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLogoIcon.0f542fa4.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLoginIcon.0af75623.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeFrontIcon.759623b8.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeWhishListIcon.0ddddf87.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeCartIcon.46c2c513.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeRegionIcon.aaf1e87a.svg
	- URL: https://www.americanas.com.br/_next/static/media/modalCloseIcon.8bacd3b4.svg
	- URL: https://www.americanas.com.br/_next/static/media/linkIcon.dbb70f32.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLinkIcon.7f5bb130.svg
	- URL: https://www.americanas.com.br/_next/static/media/greyHamburguerIcon.54572277.svg
	- URL: https://www.americanas.com.br/_next/static/media/greyArrowDownIcon.80ce865c.svg
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/css/ddb4d27f04be367b.css
		- URL: https://www.americanas.com.br/_next/static/media/libras.163216a6.svg
	- URL: https://www.americanas.com.br/_next/static/css/db6d65a93881bcc8.css
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/css/05b6df3951ba7e9e.css
	- URL: https://www.americanas.com.br/_next/static/css/718d49681a48458e.css
	- URL: https://www.americanas.com.br/_next/static/chunks/webpack-8e916de0c5788241.js
		- URL: https://www.americanas.com.br/_next/static/chunks/4791.8f065baab1f06aee.js
		- URL: https://www.americanas.com.br/_next/static/chunks/816.cce46a8dccd3ab2b.js
		- URL: https://www.americanas.com.br/_next/static/chunks/8748.227a2e0e5b7efdb7.js
	- URL: https://www.americanas.com.br/_next/static/chunks/main-5611a9fe26819d2e.js
		- URL: <redacted cross-origin initiator URL>
		- URL: https://www.americanas.com.br/_next/data/WwoTUivG1rQUIEzlp3jMD/pt-BR/nossas-lojas.json?chave=prf_hs_0_dt_1_00_nossas-lojas
		- URL: https://www.americanas.com.br/_next/data/WwoTUivG1rQUIEzlp3jMD/pt-BR/account.json?slug=account
		- URL: https://www.americanas.com.br/_next/static/media/arrowDownIcon.1e927531.svg
		- URL: https://www.americanas.com.br/_next/static/media/gridActiveIcon.fa859fba.svg
		- URL: https://www.americanas.com.br/_next/static/media/listInactiveIcon.6e9744d5.svg
		- URL: https://www.americanas.com.br/_next/static/media/addCartIcon.264a0d59.svg
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: https://www.americanas.com.br/_next/static/media/filterIcon.94fecf70.svg
		- URL: https://www.americanas.com.br/_next/static/css/db6d65a93881bcc8.css
		- URL: https://www.americanas.com.br/_next/static/css/05b6df3951ba7e9e.css
		- URL: https://www.americanas.com.br/_next/static/css/718d49681a48458e.css
	- URL: https://www.americanas.com.br/_next/static/chunks/pages/_app-07b5522414db2dad.js
		- URL: https://www.americanas.com.br/api/graphql?operationName=getOrderFormQueryInsiderQuery&operationHash=2faa81800c5ebc3282bda7f9d1947c81e3f1cdc9&variables=%7B%22variables%22%3A%7B%7D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=getSession&operationHash=1c54b7ca41364b8f206cf32e342dd2bf2dcb0cca
		- URL: https://www.americanas.com.br/api/graphql?operationName=getSession&operationHash=1c54b7ca41364b8f206cf32e342dd2bf2dcb0cca
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateCartMutation&operationHash=c2b3f8bff73ebf6ac79d758c66cabbc21ba9fcc0
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateSession&operationHash=8c3a5999496e227f167e9dc79697e6c478d48a9e
		- URL: https://www.americanas.com.br/api/graphql?operationName=CMSPages&operationHash=1482ea84ad6401f01cba58fbfc44e2297be50efb
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=getCategoryTree&operationHash=d0fa96900d0595c43a19b5a8f1095679e4212ef3
		- URL: https://www.americanas.com.br/api/graphql?operationName=getCategoryTree&operationHash=d0fa96900d0595c43a19b5a8f1095679e4212ef3
	- URL: https://www.americanas.com.br/_next/static/chunks/c78d26b1-fe043233b220ebfb.js
	- URL: https://www.americanas.com.br/_next/static/chunks/7102-be0000d0682872ec.js
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/6407-35ffec1a99a0fa9e.js
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/3105-37e4e05718827456.js
	- URL: https://www.americanas.com.br/_next/static/chunks/pages/%5B...slug%5D-c77cbab19ef9873c.js
	- URL: https://www.americanas.com.br/_next/static/WwoTUivG1rQUIEzlp3jMD/_buildManifest.js
	- URL: https://www.americanas.com.br/_next/static/WwoTUivG1rQUIEzlp3jMD/_ssgManifest.js
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/icons.svg
	- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/media/BannerTopAboveHeaderDesktop.c31d6fb9.webp
	- URL: https://www.americanas.com.br/_next/static/media/accessible.ded633c6.svg
	- URL: https://www.americanas.com.br/~partytown/partytown-sandbox-sw.html?1783033966805
	- URL: https://www.americanas.com.br/api/graphql?operationName=getOrderFormQueryInsiderQuery&operationHash=2faa81800c5ebc3282bda7f9d1947c81e3f1cdc9&variables=%7B%22variables%22%3A%7B%7D%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
	- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
````

### Answer

Este é um pedido `GET` para a página de categoria de cadeiras de escritório. O servidor utiliza Next.js (via VTEX FastStore) e entregou o conteúdo em apenas 23ms, indicando um hit no cache da CloudFront.

### Análise de Tempo e Status
*   **Status**: 200 OK. O servidor processou a solicitação com sucesso.
*   **Performance**: O tempo de espera (TTFB) de 19ms é excelente, resultado da distribuição via CDN.
*   **Cache**: O header `age: 31` e `x-nextjs-cache` sugerem que você recebeu uma versão pré-renderizada e armazenada em cache.

### cURL para n8n
Como os dados de `cookie` e `csrf` foram omitidos (redigidos) no seu log por segurança, você deve copiar os valores reais do seu navegador. 

**Nota**: Para "pesquisar" produtos programaticamente, o endpoint de **GraphQL** listado no seu rastro de iniciadores (`/api/graphql`) com a operação `ClientProductGalleryQuery` é mais eficiente do que baixar o HTML da página inteira.

Abaixo, o cURL da requisição selecionada:


`````sh
curl 'https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio' \
  -H 'accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8' \
  -H 'user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/149.0.0.0 Safari/537.36' \
  -H 'cookie: [COLE_AQUI_SEUS_COOKIES_REDAZIDOS]' \
  --compressed
`````


**Sugestões para o n8n:**
*   **Cookies**: O site da Americanas utiliza proteção contra bots. Se o n8n falhar com 403, você precisará atualizar o header `cookie` e garantir que o `user-agent` seja idêntico ao de um navegador real.
*   **CSRF**: Nesta requisição `GET` específica de página pública, não há um header `x-csrf-token` explícito. Se for realizar buscas via POST no GraphQL, procure pelo header `x-vtex-api-appkey` ou tokens dinâmicos gerados nos cookies da sessão.

## User

detalhe melhor sobre a busca via postno graphQL como faço isso?

## AI

### Analyzing data

**Request:**
````
Request URL: https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio

Request headers:
:authority: www.americanas.com.br
:method: GET
:path: /moveis/cadeira/cadeira-de-escritorio
:scheme: https
accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
accept-encoding: gzip, deflate, br, zstd
accept-language: pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7
cache-control: max-age=0
cookie: <redacted>
priority: <redacted>
referer: https://www.americanas.com.br/
sec-ch-ua: <redacted>
sec-ch-ua-mobile: <redacted>
sec-ch-ua-platform: <redacted>
sec-fetch-dest: <redacted>
sec-fetch-mode: <redacted>
sec-fetch-site: <redacted>
sec-fetch-user: <redacted>
upgrade-insecure-requests: 1
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/149.0.0.0 Safari/537.36
````

**Response:**
````
Response headers:
age: 31
cache-control: s-maxage=31536000, stale-while-revalidate=31536000
content-encoding: gzip
content-type: text/html; charset=utf-8
date: Thu, 02 Jul 2026 23:12:20 GMT
etag: <redacted>
server: CloudFront
vary: Accept-Encoding
via: 1.1 7212e65fd1e4df6d4dd22c2288b21f7c.cloudfront.net (CloudFront)
x-amz-cf-id: <redacted>
x-amz-cf-pop: <redacted>
x-cache: <redacted>
x-envoy-upstream-service-time: <redacted>
x-nextjs-cache: <redacted>
x-powered-by: Next.js
x-vtex-janus-router-backend-app: <redacted>

Response body:
<!DOCTYPE html><html dir="ltr" lang="pt-BR"><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><script>var partytown={forward:[...["sendrc"],!window.location.search.includes('gtm_debug=')&&false?'dataLayer.push':null].filter(Boolean)}</script><script type="text/partytown">
            window.VTEX_METADATA = {account:'americanas', renderer: 'faststore'};
            window.sendrc=function(en,ed){window.NavigationCapture&&window.NavigationCapture.sendEvent(en,ed)};
          </script><script type="text/partytown" async="" src="https://io.vtex.com.br/rc/rc.js"></script><script type="text/javascript">
            (function(v,t,e,x,a,f,s){
              f=v.vtexaf=v.vtexaf||function(){(f.q=f.q||[]).push(arguments)}
              ;f.l=+new Date;s=t.createElement(e);s.async=!0;
              s.src=x;a=t.getElementsByTagName(e)[0];
              a.parentNode.insertBefore(s,a)
            })(window,document,'script','https://activity-flow.vtex.com/af/af.js');
          </script><script type="text/javascript">
            window.vtexaf('init', {
              account: 'americanas',
              env: 'vtexcommercestable',
              workspace: 'master'
            });
          </script><script async="">
            (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
            j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
            'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
            })(window,document,'script','dataLayer','GTM-5TPDVK2Z');
          </script><script type="text/javascript" src="https://reviews.konfidency.com.br/americanas/loader.js"></script><link rel="stylesheet" href="https://cdn.privacytools.com.br/public_api/banner/style/xz1N21419101.css?t=1"/><script type="text/javascript" src="https://cdn.privacytools.com.br/public_api/banner/autoblock/v2/kQWG21419101.js?t=1"></script><script type="text/javascript" src="https://cdn.privacytools.com.br/public_api/banner/script/bottom/xz1N21419101.js?t=1"></script><meta name="google-site-verification" content="9BlvZkcfeD56_XPs9GeY7fZaDxy2tXm_v4eQkv0zI6Q"/><script>!(function(w,p,f,c){c=w[p]=w[p]||{};c[f]=(c[f]||[])})(window,'partytown','forward');/* Partytown 0.6.4 - MIT builder.io */
!function(t,e,n,i,r,o,a,d,s,c,p,l){function u(){l||(l=1,"/"==(a=(o.lib||"/~partytown/")+(o.debug?"debug/":""))[0]&&(s=e.querySelectorAll('script[type="text/partytown"]'),i!=t?i.dispatchEvent(new CustomEvent("pt1",{detail:t})):(d=setTimeout(w,1e4),e.addEventListener("pt0",f),r?h(1):n.serviceWorker?n.serviceWorker.register(a+(o.swPath||"partytown-sw.js"),{scope:a}).then((function(t){t.active?h():t.installing&&t.installing.addEventListener("statechange",(function(t){"activated"==t.target.state&&h()}))}),console.error):w())))}function h(t){c=e.createElement(t?"script":"iframe"),t||(c.setAttribute("style","display:block;width:0;height:0;border:0;visibility:hidden"),c.setAttribute("aria-hidden",!0)),c.src=a+"partytown-"+(t?"atomics.js?v=0.6.4":"sandbox-sw.html?"+Date.now()),e.body.appendChild(c)}function w(t,n){for(f(),t=0;t<s.length;t++)(n=e.createElement("script")).innerHTML=s[t].innerHTML,e.head.appendChild(n);c&&c.parentNode.removeChild(c)}function f(){clearTimeout(d)}o=t.partytown||{},i==t&&(o.forward||[]).map((function(e){p=t,e.split(".").map((function(e,n,i){p=p[i[n]]=n+1<i.length?"push"==i[n+1]?[]:p[i[n]]||{}:function(){(t._ptf=t._ptf||[]).push(i,arguments)}}))})),"complete"==e.readyState?u():(t.addEventListener("DOMContentLoaded",u),t.addEventListener("load",u))}(window,document,navigator,top,window.crossOriginIsolated);document.currentScript.dataset.partytown="";</script><meta name="generated-at" content="2026-07-02T22:41:32.581Z"/><title>Cadeira Para Escritório Ergonômica, Presidente, Giratória e Mais: Promoção | Americanas</title><meta name="robots" content="index,follow"/><meta name="description" content="Na Americanas, você encontra cadeira de escritório ergonômica, presidente, giratória, preta, branca, rosa e muito mais em promoção. Confira!"/><meta property="og:title" content="Cadeira Para Escritório Ergonômica, Presidente, Giratória e Mais"/><meta property="og:description" content="Na Americanas, você encontra cadeira de escritório ergonômica, presidente, giratória, preta, branca, rosa e muito mais em promoção. Confira!"/><meta property="og:url" content="https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio"/><meta property="og:type" content="website"/><link rel="canonical" href="https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio"/><script type="application/ld+json">{"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","position":1,"item":"https://www.americanas.com.br/moveis","name":"Móveis"},{"@type":"ListItem","position":2,"item":"https://www.americanas.com.br/moveis/cadeira","name":"Cadeira"},{"@type":"ListItem","position":3,"item":"https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio","name":"Cadeira de escritório"}]}</script><link rel="preload" as="image" imageSrcSet="/_next/static/media/listIcon.4d69f34d.svg 1x, /_next/static/media/listIcon.4d69f34d.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLoginIconMobile.b078e2d1.svg 1x, /_next/static/media/storeLoginIconMobile.b078e2d1.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLogoIcon.0f542fa4.svg 1x, /_next/static/media/storeLogoIcon.0f542fa4.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLoginIcon.0af75623.svg 1x, /_next/static/media/storeLoginIcon.0af75623.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeFrontIcon.759623b8.svg 1x, /_next/static/media/storeFrontIcon.759623b8.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeWhishListIcon.0ddddf87.svg 1x, /_next/static/media/storeWhishListIcon.0ddddf87.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeCartIcon.46c2c513.svg 1x, /_next/static/media/storeCartIcon.46c2c513.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeRegionIcon.aaf1e87a.svg 1x, /_next/static/media/storeRegionIcon.aaf1e87a.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/modalCloseIcon.8bacd3b4.svg 1x, /_next/static/media/modalCloseIcon.8bacd3b4.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/linkIcon.dbb70f32.svg 1x, /_next/static/media/linkIcon.dbb70f32.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLinkIcon.7f5bb130.svg 1x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/greyHamburguerIcon.54572277.svg 1x, /_next/static/media/greyHamburguerIcon.54572277.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/greyArrowDownIcon.80ce865c.svg 1x, /_next/static/media/greyArrowDownIcon.80ce865c.svg 2x" fetchPriority="high"/><meta name="next-head-count" content="26"/><link rel="preconnect" href="https://americanas.vtexassets.com"/><link rel="dns-prefetch" href="https://americanas.vtexassets.com"/><meta name="storefront" content="fast_store"/><link rel="preconnect" href="https://fonts.googleapis.com"/><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous"/><link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&amp;family=Roboto+Flex:opsz,wght@8..144,100..1000&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet"/><noscript><link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&amp;family=Roboto+Flex:opsz,wght@8..144,100..1000&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet"/></noscript><link rel="preload" href="/_next/static/css/ddb4d27f04be367b.css" as="style"/><link rel="stylesheet" href="/_next/static/css/ddb4d27f04be367b.css" data-n-g=""/><link rel="preload" href="/_next/static/css/db6d65a93881bcc8.css" as="style"/><link rel="stylesheet" href="/_next/static/css/db6d65a93881bcc8.css" data-n-p=""/><link rel="preload" href="/_next/static/css/05b6df3951ba7e9e.css" as="style"/><link rel="stylesheet" href="/_next/static/css/05b6df3951ba7e9e.css" data-n-p=""/><link rel="preload" href="/_next/static/css/718d49681a48458e.css" as="style"/><link rel="stylesheet" href="/_next/static/css/718d49681a48458e.css" data-n-p=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/_next/static/chunks/polyfills-c67a75d1b6f99dc8.js"></script><script src="/_next/static/chunks/webpack-8e916de0c5788241.js" defer=""></script><script src="/_next/static/chunks/main-5611a9fe26819d2e.js" defer=""></script><script src="/_next/static/chunks/pages/_app-07b5522414db2dad.js" defer=""></script><script src="/_next/static/chunks/c78d26b1-fe043233b220ebfb.js" defer=""></script><script src="/_next/static/chunks/7102-be0000d0682872ec.js" defer=""></script><script src="/_next/static/chunks/6407-35ffec1a99a0fa9e.js" defer=""></script><script src="/_next/static/chunks/3105-37e4e05718827456.js" defer=""></script><script src="/_next/static/chunks/pages/%5B...slug%5D-c77cbab19ef9873c.js" defer=""></script><script src="/_next/static/WwoTUivG1rQUIEzlp3jMD/_buildManifest.js" defer=""></script><script src="/_next/static/WwoTUivG1rQUIEzlp3jMD/_ssgManifest.js" defer=""></script></head><body class="theme"><div id="__next"><a class="SkipToMai... <truncated>

Response status: 200 
Network request status: finished
````

**Timing:**
````
Queued at (timestamp): 0 s
Started at (timestamp): 1 ms
Queueing (duration): 1 ms
Connection start (stalled) (duration): 0.6 ms
Request sent (duration): 0.3 ms
Waiting for server response (duration): 19 ms
Content download (duration): 0.8 ms
Duration (duration): 23 ms
````

**Request initiator chain:**
````
- URL: https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/media/listIcon.4d69f34d.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLoginIconMobile.b078e2d1.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLogoIcon.0f542fa4.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLoginIcon.0af75623.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeFrontIcon.759623b8.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeWhishListIcon.0ddddf87.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeCartIcon.46c2c513.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeRegionIcon.aaf1e87a.svg
	- URL: https://www.americanas.com.br/_next/static/media/modalCloseIcon.8bacd3b4.svg
	- URL: https://www.americanas.com.br/_next/static/media/linkIcon.dbb70f32.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLinkIcon.7f5bb130.svg
	- URL: https://www.americanas.com.br/_next/static/media/greyHamburguerIcon.54572277.svg
	- URL: https://www.americanas.com.br/_next/static/media/greyArrowDownIcon.80ce865c.svg
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/css/ddb4d27f04be367b.css
		- URL: https://www.americanas.com.br/_next/static/media/libras.163216a6.svg
	- URL: https://www.americanas.com.br/_next/static/css/db6d65a93881bcc8.css
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/css/05b6df3951ba7e9e.css
	- URL: https://www.americanas.com.br/_next/static/css/718d49681a48458e.css
	- URL: https://www.americanas.com.br/_next/static/chunks/webpack-8e916de0c5788241.js
		- URL: https://www.americanas.com.br/_next/static/chunks/4791.8f065baab1f06aee.js
		- URL: https://www.americanas.com.br/_next/static/chunks/816.cce46a8dccd3ab2b.js
		- URL: https://www.americanas.com.br/_next/static/chunks/8748.227a2e0e5b7efdb7.js
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/main-5611a9fe26819d2e.js
		- URL: <redacted cross-origin initiator URL>
		- URL: https://www.americanas.com.br/_next/data/WwoTUivG1rQUIEzlp3jMD/pt-BR/nossas-lojas.json?chave=prf_hs_0_dt_1_00_nossas-lojas
		- URL: https://www.americanas.com.br/_next/data/WwoTUivG1rQUIEzlp3jMD/pt-BR/account.json?slug=account
		- URL: https://www.americanas.com.br/_next/static/media/arrowDownIcon.1e927531.svg
		- URL: https://www.americanas.com.br/_next/static/media/gridActiveIcon.fa859fba.svg
		- URL: https://www.americanas.com.br/_next/static/media/listInactiveIcon.6e9744d5.svg
		- URL: https://www.americanas.com.br/_next/static/media/addCartIcon.264a0d59.svg
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: https://www.americanas.com.br/_next/static/media/filterIcon.94fecf70.svg
		- URL: https://www.americanas.com.br/_next/static/css/db6d65a93881bcc8.css
		- URL: https://www.americanas.com.br/_next/static/css/05b6df3951ba7e9e.css
		- URL: https://www.americanas.com.br/_next/static/css/718d49681a48458e.css
	- URL: https://www.americanas.com.br/_next/static/chunks/pages/_app-07b5522414db2dad.js
		- URL: https://www.americanas.com.br/api/graphql?operationName=getOrderFormQueryInsiderQuery&operationHash=2faa81800c5ebc3282bda7f9d1947c81e3f1cdc9&variables=%7B%22variables%22%3A%7B%7D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=getSession&operationHash=1c54b7ca41364b8f206cf32e342dd2bf2dcb0cca
		- URL: https://www.americanas.com.br/api/graphql?operationName=getSession&operationHash=1c54b7ca41364b8f206cf32e342dd2bf2dcb0cca
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateCartMutation&operationHash=c2b3f8bff73ebf6ac79d758c66cabbc21ba9fcc0
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateSession&operationHash=8c3a5999496e227f167e9dc79697e6c478d48a9e
		- URL: https://www.americanas.com.br/api/graphql?operationName=CMSPages&operationHash=1482ea84ad6401f01cba58fbfc44e2297be50efb
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=getCategoryTree&operationHash=d0fa96900d0595c43a19b5a8f1095679e4212ef3
		- URL: https://www.americanas.com.br/api/graphql?operationName=getCategoryTree&operationHash=d0fa96900d0595c43a19b5a8f1095679e4212ef3
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateCartMutation&operationHash=c2b3f8bff73ebf6ac79d758c66cabbc21ba9fcc0
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateSession&operationHash=8c3a5999496e227f167e9dc79697e6c478d48a9e
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
	- URL: https://www.americanas.com.br/_next/static/chunks/c78d26b1-fe043233b220ebfb.js
	- URL: https://www.americanas.com.br/_next/static/chunks/7102-be0000d0682872ec.js
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/6407-35ffec1a99a0fa9e.js
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/3105-37e4e05718827456.js
	- URL: https://www.americanas.com.br/_next/static/chunks/pages/%5B...slug%5D-c77cbab19ef9873c.js
	- URL: https://www.americanas.com.br/_next/static/WwoTUivG1rQUIEzlp3jMD/_buildManifest.js
	- URL: https://www.americanas.com.br/_next/static/WwoTUivG1rQUIEzlp3jMD/_ssgManifest.js
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/icons.svg
	- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/media/BannerTopAboveHeaderDesktop.c31d6fb9.webp
	- URL: https://www.americanas.com.br/_next/static/media/accessible.ded633c6.svg
	- URL: https://www.americanas.com.br/~partytown/partytown-sandbox-sw.html?1783033966805
	- URL: https://www.americanas.com.br/api/graphql?operationName=getOrderFormQueryInsiderQuery&operationHash=2faa81800c5ebc3282bda7f9d1947c81e3f1cdc9&variables=%7B%22variables%22%3A%7B%7D%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
	- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
````

### Answer

Para buscar produtos via GraphQL na Americanas (plataforma VTEX), você deve enviar uma requisição **POST** para o endpoint de API. Isso é mais eficiente que extrair do HTML, pois retorna JSON estruturado.

### Configuração para o nó HTTP Request do n8n

**URL**: `https://www.americanas.com.br/api/graphql`
**Método**: `POST`
**Autenticação**: Nenhuma (os cookies gerenciam a sessão).

#### 1. Headers (Cabeçalhos)
Estes são essenciais para evitar o bloqueio por segurança:
*   `Content-Type`: `application/json`
*   `User-Agent`: (Use o do seu navegador atual)
*   `Cookie`: (Copie o valor completo do campo `cookie` da sua aba Network)
*   `Origin`: `https://www.americanas.com.br`
*   `Referer`: `https://www.americanas.com.br/`

#### 2. Body (Corpo da Requisição)
Selecione o formato **JSON**. O segredo está no `operationHash`, que identifica a consulta pré-registrada no servidor.


`````json
{
  "operationName": "ClientProductGalleryQuery",
  "operationHash": "bfc40da32b60f9404a4adb96b0856e3fbb04b076",
  "variables": {
    "first": 12,
    "after": "0",
    "sort": "score_desc",
    "term": "cadeira gamer",
    "selectedFacets": [
      { "key": "channel", "value": "{\"salesChannel\":1,\"regionId\":\"\"}" },
      { "key": "locale", "value": "pt-BR" }
    ]
  }
}
`````


### Análise Técnica
*   **Root Cause (Bloqueio)**: Se o n8n retornar `403 Forbidden`, o cookie expirou ou a CloudFront detectou tráfego automatizado. 
*   **Sugestão**: Em `variables`, altere o campo `"term"` para o produto desejado. Se quiser navegar por categorias em vez de busca textual, adicione chaves como `category-1`, `category-2` no array `selectedFacets`.

**Nota sobre CSRF**: Nas APIs da VTEX voltadas para o front-end, a validação geralmente é feita via o cookie `VtexIdclientAuthen` ou `checkout.vtex.com`. Não há um header `X-CSRF-Token` obrigatório para consultas `GET` encapsuladas em `POST` GraphQL, a menos que você esteja alterando o carrinho ou dados do usuário.

## User

como devo instruir o Codex para implementar essa pesquisa com o n8n considerando que será iniciada com uma requisição por meio do webhook que espera uma resposta para alimentar uma interface em html com os cards contendo descrição, preço, frete, imagem e link de compra. 

## AI

### Analyzing data

**Request:**
````
Request URL: https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio

Request headers:
:authority: www.americanas.com.br
:method: GET
:path: /moveis/cadeira/cadeira-de-escritorio
:scheme: https
accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
accept-encoding: gzip, deflate, br, zstd
accept-language: pt-BR,pt;q=0.9,en-US;q=0.8,en;q=0.7
cache-control: max-age=0
cookie: <redacted>
priority: <redacted>
referer: https://www.americanas.com.br/
sec-ch-ua: <redacted>
sec-ch-ua-mobile: <redacted>
sec-ch-ua-platform: <redacted>
sec-fetch-dest: <redacted>
sec-fetch-mode: <redacted>
sec-fetch-site: <redacted>
sec-fetch-user: <redacted>
upgrade-insecure-requests: 1
user-agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/149.0.0.0 Safari/537.36
````

**Response:**
````
Response headers:
age: 31
cache-control: s-maxage=31536000, stale-while-revalidate=31536000
content-encoding: gzip
content-type: text/html; charset=utf-8
date: Thu, 02 Jul 2026 23:12:20 GMT
etag: <redacted>
server: CloudFront
vary: Accept-Encoding
via: 1.1 7212e65fd1e4df6d4dd22c2288b21f7c.cloudfront.net (CloudFront)
x-amz-cf-id: <redacted>
x-amz-cf-pop: <redacted>
x-cache: <redacted>
x-envoy-upstream-service-time: <redacted>
x-nextjs-cache: <redacted>
x-powered-by: Next.js
x-vtex-janus-router-backend-app: <redacted>

Response body:
<!DOCTYPE html><html dir="ltr" lang="pt-BR"><head><meta charSet="utf-8"/><meta name="viewport" content="width=device-width"/><script>var partytown={forward:[...["sendrc"],!window.location.search.includes('gtm_debug=')&&false?'dataLayer.push':null].filter(Boolean)}</script><script type="text/partytown">
            window.VTEX_METADATA = {account:'americanas', renderer: 'faststore'};
            window.sendrc=function(en,ed){window.NavigationCapture&&window.NavigationCapture.sendEvent(en,ed)};
          </script><script type="text/partytown" async="" src="https://io.vtex.com.br/rc/rc.js"></script><script type="text/javascript">
            (function(v,t,e,x,a,f,s){
              f=v.vtexaf=v.vtexaf||function(){(f.q=f.q||[]).push(arguments)}
              ;f.l=+new Date;s=t.createElement(e);s.async=!0;
              s.src=x;a=t.getElementsByTagName(e)[0];
              a.parentNode.insertBefore(s,a)
            })(window,document,'script','https://activity-flow.vtex.com/af/af.js');
          </script><script type="text/javascript">
            window.vtexaf('init', {
              account: 'americanas',
              env: 'vtexcommercestable',
              workspace: 'master'
            });
          </script><script async="">
            (function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
            new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
            j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
            'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
            })(window,document,'script','dataLayer','GTM-5TPDVK2Z');
          </script><script type="text/javascript" src="https://reviews.konfidency.com.br/americanas/loader.js"></script><link rel="stylesheet" href="https://cdn.privacytools.com.br/public_api/banner/style/xz1N21419101.css?t=1"/><script type="text/javascript" src="https://cdn.privacytools.com.br/public_api/banner/autoblock/v2/kQWG21419101.js?t=1"></script><script type="text/javascript" src="https://cdn.privacytools.com.br/public_api/banner/script/bottom/xz1N21419101.js?t=1"></script><meta name="google-site-verification" content="9BlvZkcfeD56_XPs9GeY7fZaDxy2tXm_v4eQkv0zI6Q"/><script>!(function(w,p,f,c){c=w[p]=w[p]||{};c[f]=(c[f]||[])})(window,'partytown','forward');/* Partytown 0.6.4 - MIT builder.io */
!function(t,e,n,i,r,o,a,d,s,c,p,l){function u(){l||(l=1,"/"==(a=(o.lib||"/~partytown/")+(o.debug?"debug/":""))[0]&&(s=e.querySelectorAll('script[type="text/partytown"]'),i!=t?i.dispatchEvent(new CustomEvent("pt1",{detail:t})):(d=setTimeout(w,1e4),e.addEventListener("pt0",f),r?h(1):n.serviceWorker?n.serviceWorker.register(a+(o.swPath||"partytown-sw.js"),{scope:a}).then((function(t){t.active?h():t.installing&&t.installing.addEventListener("statechange",(function(t){"activated"==t.target.state&&h()}))}),console.error):w())))}function h(t){c=e.createElement(t?"script":"iframe"),t||(c.setAttribute("style","display:block;width:0;height:0;border:0;visibility:hidden"),c.setAttribute("aria-hidden",!0)),c.src=a+"partytown-"+(t?"atomics.js?v=0.6.4":"sandbox-sw.html?"+Date.now()),e.body.appendChild(c)}function w(t,n){for(f(),t=0;t<s.length;t++)(n=e.createElement("script")).innerHTML=s[t].innerHTML,e.head.appendChild(n);c&&c.parentNode.removeChild(c)}function f(){clearTimeout(d)}o=t.partytown||{},i==t&&(o.forward||[]).map((function(e){p=t,e.split(".").map((function(e,n,i){p=p[i[n]]=n+1<i.length?"push"==i[n+1]?[]:p[i[n]]||{}:function(){(t._ptf=t._ptf||[]).push(i,arguments)}}))})),"complete"==e.readyState?u():(t.addEventListener("DOMContentLoaded",u),t.addEventListener("load",u))}(window,document,navigator,top,window.crossOriginIsolated);document.currentScript.dataset.partytown="";</script><meta name="generated-at" content="2026-07-02T22:41:32.581Z"/><title>Cadeira Para Escritório Ergonômica, Presidente, Giratória e Mais: Promoção | Americanas</title><meta name="robots" content="index,follow"/><meta name="description" content="Na Americanas, você encontra cadeira de escritório ergonômica, presidente, giratória, preta, branca, rosa e muito mais em promoção. Confira!"/><meta property="og:title" content="Cadeira Para Escritório Ergonômica, Presidente, Giratória e Mais"/><meta property="og:description" content="Na Americanas, você encontra cadeira de escritório ergonômica, presidente, giratória, preta, branca, rosa e muito mais em promoção. Confira!"/><meta property="og:url" content="https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio"/><meta property="og:type" content="website"/><link rel="canonical" href="https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio"/><script type="application/ld+json">{"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","position":1,"item":"https://www.americanas.com.br/moveis","name":"Móveis"},{"@type":"ListItem","position":2,"item":"https://www.americanas.com.br/moveis/cadeira","name":"Cadeira"},{"@type":"ListItem","position":3,"item":"https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio","name":"Cadeira de escritório"}]}</script><link rel="preload" as="image" imageSrcSet="/_next/static/media/listIcon.4d69f34d.svg 1x, /_next/static/media/listIcon.4d69f34d.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLoginIconMobile.b078e2d1.svg 1x, /_next/static/media/storeLoginIconMobile.b078e2d1.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLogoIcon.0f542fa4.svg 1x, /_next/static/media/storeLogoIcon.0f542fa4.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLoginIcon.0af75623.svg 1x, /_next/static/media/storeLoginIcon.0af75623.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeFrontIcon.759623b8.svg 1x, /_next/static/media/storeFrontIcon.759623b8.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeWhishListIcon.0ddddf87.svg 1x, /_next/static/media/storeWhishListIcon.0ddddf87.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeCartIcon.46c2c513.svg 1x, /_next/static/media/storeCartIcon.46c2c513.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeRegionIcon.aaf1e87a.svg 1x, /_next/static/media/storeRegionIcon.aaf1e87a.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/modalCloseIcon.8bacd3b4.svg 1x, /_next/static/media/modalCloseIcon.8bacd3b4.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/linkIcon.dbb70f32.svg 1x, /_next/static/media/linkIcon.dbb70f32.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/storeLinkIcon.7f5bb130.svg 1x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/greyHamburguerIcon.54572277.svg 1x, /_next/static/media/greyHamburguerIcon.54572277.svg 2x" fetchPriority="high"/><link rel="preload" as="image" imageSrcSet="/_next/static/media/greyArrowDownIcon.80ce865c.svg 1x, /_next/static/media/greyArrowDownIcon.80ce865c.svg 2x" fetchPriority="high"/><meta name="next-head-count" content="26"/><link rel="preconnect" href="https://americanas.vtexassets.com"/><link rel="dns-prefetch" href="https://americanas.vtexassets.com"/><meta name="storefront" content="fast_store"/><link rel="preconnect" href="https://fonts.googleapis.com"/><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous"/><link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&amp;family=Roboto+Flex:opsz,wght@8..144,100..1000&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet"/><noscript><link href="https://fonts.googleapis.com/css2?family=Bungee+Spice&amp;family=Roboto+Flex:opsz,wght@8..144,100..1000&amp;display=swap" rel="stylesheet"/><link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet"/></noscript><link rel="preload" href="/_next/static/css/ddb4d27f04be367b.css" as="style"/><link rel="stylesheet" href="/_next/static/css/ddb4d27f04be367b.css" data-n-g=""/><link rel="preload" href="/_next/static/css/db6d65a93881bcc8.css" as="style"/><link rel="stylesheet" href="/_next/static/css/db6d65a93881bcc8.css" data-n-p=""/><link rel="preload" href="/_next/static/css/05b6df3951ba7e9e.css" as="style"/><link rel="stylesheet" href="/_next/static/css/05b6df3951ba7e9e.css" data-n-p=""/><link rel="preload" href="/_next/static/css/718d49681a48458e.css" as="style"/><link rel="stylesheet" href="/_next/static/css/718d49681a48458e.css" data-n-p=""/><noscript data-n-css=""></noscript><script defer="" nomodule="" src="/_next/static/chunks/polyfills-c67a75d1b6f99dc8.js"></script><script src="/_next/static/chunks/webpack-8e916de0c5788241.js" defer=""></script><script src="/_next/static/chunks/main-5611a9fe26819d2e.js" defer=""></script><script src="/_next/static/chunks/pages/_app-07b5522414db2dad.js" defer=""></script><script src="/_next/static/chunks/c78d26b1-fe043233b220ebfb.js" defer=""></script><script src="/_next/static/chunks/7102-be0000d0682872ec.js" defer=""></script><script src="/_next/static/chunks/6407-35ffec1a99a0fa9e.js" defer=""></script><script src="/_next/static/chunks/3105-37e4e05718827456.js" defer=""></script><script src="/_next/static/chunks/pages/%5B...slug%5D-c77cbab19ef9873c.js" defer=""></script><script src="/_next/static/WwoTUivG1rQUIEzlp3jMD/_buildManifest.js" defer=""></script><script src="/_next/static/WwoTUivG1rQUIEzlp3jMD/_ssgManifest.js" defer=""></script></head><body class="theme"><div id="__next"><a class="SkipToMai... <truncated>

Response status: 200 
Network request status: finished
````

**Timing:**
````
Queued at (timestamp): 0 s
Started at (timestamp): 1 ms
Queueing (duration): 1 ms
Connection start (stalled) (duration): 0.6 ms
Request sent (duration): 0.3 ms
Waiting for server response (duration): 19 ms
Content download (duration): 0.8 ms
Duration (duration): 23 ms
````

**Request initiator chain:**
````
- URL: https://www.americanas.com.br/moveis/cadeira/cadeira-de-escritorio
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/media/listIcon.4d69f34d.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLoginIconMobile.b078e2d1.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLogoIcon.0f542fa4.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLoginIcon.0af75623.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeFrontIcon.759623b8.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeWhishListIcon.0ddddf87.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeCartIcon.46c2c513.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeRegionIcon.aaf1e87a.svg
	- URL: https://www.americanas.com.br/_next/static/media/modalCloseIcon.8bacd3b4.svg
	- URL: https://www.americanas.com.br/_next/static/media/linkIcon.dbb70f32.svg
	- URL: https://www.americanas.com.br/_next/static/media/storeLinkIcon.7f5bb130.svg
	- URL: https://www.americanas.com.br/_next/static/media/greyHamburguerIcon.54572277.svg
	- URL: https://www.americanas.com.br/_next/static/media/greyArrowDownIcon.80ce865c.svg
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/css/ddb4d27f04be367b.css
		- URL: https://www.americanas.com.br/_next/static/media/libras.163216a6.svg
	- URL: https://www.americanas.com.br/_next/static/css/db6d65a93881bcc8.css
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/css/05b6df3951ba7e9e.css
	- URL: https://www.americanas.com.br/_next/static/css/718d49681a48458e.css
	- URL: https://www.americanas.com.br/_next/static/chunks/webpack-8e916de0c5788241.js
		- URL: https://www.americanas.com.br/_next/static/chunks/4791.8f065baab1f06aee.js
		- URL: https://www.americanas.com.br/_next/static/chunks/816.cce46a8dccd3ab2b.js
		- URL: https://www.americanas.com.br/_next/static/chunks/8748.227a2e0e5b7efdb7.js
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/main-5611a9fe26819d2e.js
		- URL: <redacted cross-origin initiator URL>
		- URL: https://www.americanas.com.br/_next/data/WwoTUivG1rQUIEzlp3jMD/pt-BR/nossas-lojas.json?chave=prf_hs_0_dt_1_00_nossas-lojas
		- URL: https://www.americanas.com.br/_next/data/WwoTUivG1rQUIEzlp3jMD/pt-BR/account.json?slug=account
		- URL: https://www.americanas.com.br/_next/static/media/arrowDownIcon.1e927531.svg
		- URL: https://www.americanas.com.br/_next/static/media/gridActiveIcon.fa859fba.svg
		- URL: https://www.americanas.com.br/_next/static/media/listInactiveIcon.6e9744d5.svg
		- URL: https://www.americanas.com.br/_next/static/media/addCartIcon.264a0d59.svg
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: https://www.americanas.com.br/_next/static/media/filterIcon.94fecf70.svg
		- URL: https://www.americanas.com.br/_next/static/css/db6d65a93881bcc8.css
		- URL: https://www.americanas.com.br/_next/static/css/05b6df3951ba7e9e.css
		- URL: https://www.americanas.com.br/_next/static/css/718d49681a48458e.css
	- URL: https://www.americanas.com.br/_next/static/chunks/pages/_app-07b5522414db2dad.js
		- URL: https://www.americanas.com.br/api/graphql?operationName=getOrderFormQueryInsiderQuery&operationHash=2faa81800c5ebc3282bda7f9d1947c81e3f1cdc9&variables=%7B%22variables%22%3A%7B%7D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=getSession&operationHash=1c54b7ca41364b8f206cf32e342dd2bf2dcb0cca
		- URL: https://www.americanas.com.br/api/graphql?operationName=getSession&operationHash=1c54b7ca41364b8f206cf32e342dd2bf2dcb0cca
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateCartMutation&operationHash=c2b3f8bff73ebf6ac79d758c66cabbc21ba9fcc0
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=simulateEffectiveInstallments&operationHash=fa046fb561196098f654ccc96b18387b17882cfa
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateSession&operationHash=8c3a5999496e227f167e9dc79697e6c478d48a9e
		- URL: https://www.americanas.com.br/api/graphql?operationName=CMSPages&operationHash=1482ea84ad6401f01cba58fbfc44e2297be50efb
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=getCategoryTree&operationHash=d0fa96900d0595c43a19b5a8f1095679e4212ef3
		- URL: https://www.americanas.com.br/api/graphql?operationName=getCategoryTree&operationHash=d0fa96900d0595c43a19b5a8f1095679e4212ef3
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateCartMutation&operationHash=c2b3f8bff73ebf6ac79d758c66cabbc21ba9fcc0
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateSession&operationHash=8c3a5999496e227f167e9dc79697e6c478d48a9e
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateCartMutation&operationHash=c2b3f8bff73ebf6ac79d758c66cabbc21ba9fcc0
		- URL: https://www.americanas.com.br/api/graphql?operationName=ValidateSession&operationHash=8c3a5999496e227f167e9dc79697e6c478d48a9e
		- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
	- URL: https://www.americanas.com.br/_next/static/chunks/c78d26b1-fe043233b220ebfb.js
	- URL: https://www.americanas.com.br/_next/static/chunks/7102-be0000d0682872ec.js
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/6407-35ffec1a99a0fa9e.js
		- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/chunks/3105-37e4e05718827456.js
	- URL: https://www.americanas.com.br/_next/static/chunks/pages/%5B...slug%5D-c77cbab19ef9873c.js
	- URL: https://www.americanas.com.br/_next/static/WwoTUivG1rQUIEzlp3jMD/_buildManifest.js
	- URL: https://www.americanas.com.br/_next/static/WwoTUivG1rQUIEzlp3jMD/_ssgManifest.js
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
	- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
		- URL: <redacted cross-origin initiator URL>
			- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
				- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/icons.svg
	- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/_next/static/media/BannerTopAboveHeaderDesktop.c31d6fb9.webp
	- URL: https://www.americanas.com.br/_next/static/media/accessible.ded633c6.svg
	- URL: https://www.americanas.com.br/~partytown/partytown-sandbox-sw.html?1783033966805
	- URL: https://www.americanas.com.br/api/graphql?operationName=getOrderFormQueryInsiderQuery&operationHash=2faa81800c5ebc3282bda7f9d1947c81e3f1cdc9&variables=%7B%22variables%22%3A%7B%7D%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A1%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
	- URL: <redacted cross-origin initiator URL>
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientSearchSuggestionsQuery&operationHash=bbaa2ed75c4fb04842189e8d53a1d65481154e2b&variables=%7B%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientProductGalleryQuery&operationHash=bfc40da32b60f9404a4adb96b0856e3fbb04b076&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
	- URL: https://www.americanas.com.br/api/graphql?operationName=ClientManyProductsQuery&operationHash=ebf3aabc70af9a8d596ba4d0fb08eda6c2b1f428&variables=%7B%22first%22%3A12%2C%22after%22%3A%220%22%2C%22sort%22%3A%22score_desc%22%2C%22term%22%3A%22%22%2C%22selectedFacets%22%3A%5B%7B%22key%22%3A%22category-1%22%2C%22value%22%3A%22moveis%22%7D%2C%7B%22key%22%3A%22category-2%22%2C%22value%22%3A%22cadeira%22%7D%2C%7B%22key%22%3A%22category-3%22%2C%22value%22%3A%22cadeira-de-escritorio%22%7D%2C%7B%22key%22%3A%22fuzzy%22%2C%22value%22%3A%220%22%7D%2C%7B%22key%22%3A%22operator%22%2C%22value%22%3A%22and%22%7D%2C%7B%22key%22%3A%22channel%22%2C%22value%22%3A%22%7B%5C%22salesChannel%5C%22%3A%5C%221%5C%22%2C%5C%22regionId%5C%22%3A%5C%22%5C%22%7D%22%7D%2C%7B%22key%22%3A%22locale%22%2C%22value%22%3A%22pt-BR%22%7D%5D%2C%22sponsoredCount%22%3A3%7D
````

### Answer

Para implementar esse fluxo no n8n via Webhook e retornar uma interface HTML, utilize a seguinte lógica estrutural.

### Arquitetura do Workflow
1.  **Webhook Node**: Recebe o parâmetro de busca (ex: `q`).
2.  **HTTP Request Node**: Executa o POST GraphQL para a Americanas.
3.  **Code Node**: Mapeia o JSON de resposta para os campos desejados e gera o HTML.
4.  **Respond to Webhook**: Retorna o HTML processado.

### Instruções para o Codex (Prompt)
> "Crie um workflow n8n que:
> 1. Inicie com um **Webhook** (GET) recebendo a variável `query`.
> 2. Use um **HTTP Request** (POST) para `https://www.americanas.com.br/api/graphql`.
>    - **Headers**: `Content-Type: application/json`, `User-Agent` de navegador real.
>    - **Body**: JSON usando `operationHash: "bfc40da32b60f9404a4adb96b0856e3fbb04b076"` e passando a `query` no campo `term` das `variables`.
> 3. Em um node **Code**, itere sobre `data.search.products` extraindo:
>    - `name` (Descrição)
>    - `price` (Preço formatado)
>    - `image[0].url` (Imagem)
>    - `link` (URL do produto)
> 4. Gere uma string HTML contendo uma lista de cards estilizados com esses dados.
> 5. Finalize com **Respond to Webhook** enviando o HTML e Header `Content-Type: text/html`."

### Considerações Técnicas
*   **Root Cause de Falhas**: A Americanas/VTEX bloqueia requisições sem `User-Agent` ou com cookies de sessão expirados. Certifique-se de copiar o `cookie` funcional do seu Network Panel para o node HTTP.
*   **Desafio do Frete**: O `ClientProductGalleryQuery` geralmente não retorna o valor exato do frete sem um CEP definido no `selectedFacets`. Sugira exibir "Consulte o frete no link" ou adicione um campo de CEP no seu Webhook para incluí-lo na consulta.

**Sugestão de Performance**: Como a resposta da Americanas é rápida (23ms), o gargalo será o processamento do n8n. Mantenha o template HTML leve para garantir baixa latência na interface.