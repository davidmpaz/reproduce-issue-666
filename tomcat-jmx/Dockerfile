FROM bitnami/jmx-exporter:0.16.1 as jmx
FROM tomcat:8.5.45-jdk8-adoptopenjdk-hotspot
COPY --from=jmx /opt/bitnami/jmx-exporter/jmx_prometheus_javaagent.jar /opt/
