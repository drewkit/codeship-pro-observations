FROM busybox

WORKDIR /app
ARG MYARG

RUN echo $MYARG > value_passed_from_build_arg.txt
RUN echo '<?xml version="1.0" encoding="UTF-8"?>' > desired_value.txt
