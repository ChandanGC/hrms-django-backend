FROM nginx
LABEL "Project"="hrms"
LABEL "Author"="GC"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY hrms.conf /etc/nginx/conf.d/hrms.conf
