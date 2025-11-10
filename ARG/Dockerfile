ARG version
FROM almalinux:${version:-9}
ENV course="DevOps with AWS" \
    trainer="sivakumar reddy" \
    duration="120HRS"
#here user1 is key, someuser is default value
ARG USERNAME=sivakumar
ENV USERNAME=${USERNAME}
RUN echo "hello username=${USERNAME},image version=${version}"
CMD ["sleep", "1000"]
