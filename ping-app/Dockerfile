#python based application
# Use bash as the default shell
SHELL ["/bin/bash", "-c"]
FROM python:3.10-slim
WORKDIR /ping-app
COPY ping.py .
EXPOSE 8000
CMD ["python", "ping.py"]
