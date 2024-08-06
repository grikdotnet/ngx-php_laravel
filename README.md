## Benchmark results:

| PHP Env        | Requests/sec |
|----------------|--------------|
| ngx-php worker | 308.35       |  
| roadrunner     | 280.51       |  
| swoole         | 240.43       |  
| frankenphp     | 211.28       |  
| ngx-php plain  | 96.34        |  
| php-fpm        | 72.18        |  
| artisan serve  | 16.84        |  


```mermaid
xychart-beta
    title "Performance of PHP Runtimes"
    x-axis ["ngx-php worker", roadrunner, swoole, frankenphp, "ngx-php plain", php-fpm, "artisan serve"]
    y-axis "Requests/sec" 16 --> 309
    bar [308.35, 280.51, 240.43, 211.28, 96.34, 72.18, 16.84]
```