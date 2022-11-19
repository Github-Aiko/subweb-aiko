FROM nginx:1.16

RUN mkdir -p /var/www/http \
    && chown -R www-data:www-data /var/www/http/ /var/log/nginx/ 

# Đặt múi giờ && thời gian đồng bộ hóa
ENV TZ=Asia/Ho_Chi_Minh
RUN ln -snf /usr/share/zoneinfo/$TZ /etc/localtime && echo $TZ > /etc/timezone
