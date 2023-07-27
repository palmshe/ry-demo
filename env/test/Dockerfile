# First stage: complete build environment
FROM palmshe/jre-1.8.0_351:1.0.0

COPY target/ry.jar /opt/service/

CMD ["java", "-Dspring.profiles.active=test", "-jar", "/opt/service/ry.jar"]
