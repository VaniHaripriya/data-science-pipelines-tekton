FROM registry.access.redhat.com/ubi8/python-39
WORKDIR /opt/app-root/src
COPY backend/artifact_manager/requirements.txt /opt/app-root/src
COPY backend/artifact_manager/setup.cfg /opt/app-root/src
RUN pip install --upgrade pip && pip install -Ur requirements.txt
CMD ["/bin/bash", "-e"]
