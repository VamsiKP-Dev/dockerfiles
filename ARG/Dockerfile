ARG version
FROM almalinux:${version:-9}
ARG course="docker" \
    type="in-person" \
    duration="10hrs"
ENV course=${course} \
    duration=${duration} \
    type=${type}
RUN echo "Course is: ${course}, Duration is: ${duration}, Type is: ${type}"