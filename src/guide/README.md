# Introduction

As developers we want a good developer experience when we build our apps, and then we want them to be as fast as possible when we deploy them. There is nothing faster that running your app on the closest CDN near you ( 25ms away ).

VueFlare tries to solve the situations above by offering a customized Vue project that is configured to run on the not so new anymore [Cloudflare Workers](https://workers.cloudflare.com/). This product is a very interesting serverless solution from Cloudflare, that lets you run static and dynamic application on their Edge Dns nodes, using an interesting solution [V8 isolates](https://developers.cloudflare.com/workers/learning/how-workers-works).

This special implementation on top of V8, allows a very fast execution time with 0 ms cold start but also comes with some challenges, as this is not the usual Nodejs environment, some of the classical SSR implementations will not work. 

This is the reason you need VueFlare.