FROM silarsis/yeoman
MAINTAINER Braun Goodson <braungoodson@gmail.com>
RUN git clone https://github.com/braungoodson/gin
RUN cd gin \
 && npm install \
 && git checkout backyard \
 && grunt serve:dist
