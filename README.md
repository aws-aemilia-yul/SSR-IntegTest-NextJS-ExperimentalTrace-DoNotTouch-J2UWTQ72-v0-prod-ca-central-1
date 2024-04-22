## SSR Integration Test NextJS with Experimental Serverless Trace

This project uses a Server Side module (argon) inside the `api/hello` route. It fails if built with the `serverless` target but succeeds when built with the `experimental-serverless-trace` target. 

| Feature  | Pages |
| ------------- | ------------- |
| API route using `argon` server-side module  | /api/hello  |
