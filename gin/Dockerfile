FROM silarsis/yeoman
MAINTAINER Braun Goodson <braungoodson@gmail.com>
RUN git clone https://github.com/braungoodson/gin
RUN cd gin \
 && git checkout backyard \
 && npm install \
 && grunt serve:dist
