FROM nginx:alpine
COPY . /etc/nginx/
RUN ln -s /etc/nginx/sites-available/wechat.dev.orangehorse.cn.conf /etc/nginx/sites-enabled
RUN nginx -t && nginx -s restart