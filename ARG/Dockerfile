ARG version
FROM almalinux:${version:-9}
ENV Course="Devops"\
    Trainer="Siva"
ARG duration="120hrs"
ENV Duration=$duration
RUN echo "Hi, Course is: ${Course}, duration is: ${duration}, trainer is: ${Trainer}, version: ${version}"
CMD ["sleep","1000"]
