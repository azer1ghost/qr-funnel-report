# qr-funnel-report

Statik, şifrələnmiş hesabat səhifəsi.

`index.html` yeganə fayldır və içindəki data **AES-256-GCM** ilə şifrələnib.
Açar URL-dən verilir:

    https://<pages-url>/?authKey=<açar>

Açarsız faylda oxunacaq data yoxdur — gizlədilmiş deyil, şifrəlidir.
Mənbə (sorğular, xam data, build skriptləri) bu repo-da saxlanmır.
