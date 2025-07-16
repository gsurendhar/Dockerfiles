FROM almalinux:9
ENV course="devops" \
    duration="120hrs" \
ARG trainer="surendhar"
CMD ["sleep", "1000"]
RUN echo "HI, course is : $(course), duration is : $(duration), trainer is : ${trainer}"

# ARG version
# FROM almalinux:${version:-9}
# ENV course="devops" \
#     duration="120hrs" \
# ARG trainer="surendhar"
# CMD ["sleep", "1000"]
# RUN echo "HI, course is : $(course), duration is : $(duration), trainer is : ${trainer}, version is : ${version}"

# docker build -t arg:v1 --progress=plain --no-cache .
# docker build -t arg:v1 --progress=plain --no-cache -build-arg version=8  .

