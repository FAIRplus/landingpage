## content of the FAIRplus cookbook landingpage

visit at <https://fairplus.github.io/landingpage>


## Using Syna Theme Starter
This page is based on [syna](https://syna.okkur.org/docs).

## local development

```
git clone --recurse-submodules https://github.com/FAIRplus/landingpage.git
cd landingpage
docker run --rm -it -v $(pwd):/src -p 1313:1313 klakegg/hugo:0.73.0-ext-alpine server
``` 

## hugo docker 

available from: https://hub.docker.com/r/klakegg/hugo/

## hugo CI/CD

available from: https://github.com/peaceiris/actions-hugo

----

*Code of the theme is licensed under the [Apache License, Version 2.0](/LICENSE).*  
*Documentation/examples are licensed under [Creative Commons BY-SA 4.0](/docs/LICENSE).*  
*Illustrations, trademarks and third-party resources are owned by their respective party and are subject to different licensing.*

---

Copyright of the theme: 2017 - The Syna Theme Starter Authors

