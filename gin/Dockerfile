FROM silarsis/yeoman
MAINTAINER Braun Goodson <braungoodson@gmail.com>
RUN git clone https://github.com/braungoodson/gin
RUN cd gin \
 && git checkout backyard \
 && bower install \
 && npm install \
 && grunt serve:dist
