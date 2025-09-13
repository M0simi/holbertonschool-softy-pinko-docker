# نستخدم nginx بدل ubuntu
FROM nginx:latest

# ننسخ ملفات الموقع إلى المسار المناسب داخل nginx
COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end

# ننسخ ملف الإعدادات المخصص
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
