FROM codenvy/jdk7_gae1914
ENV CODENVY_APP_BIND_DIR /home/user/app
VOLUME ["/home/user/app/"]
CMD ./dev_appserver.sh 2>&1 --disable_update_check -a 0.0.0.0 /home/user/app
