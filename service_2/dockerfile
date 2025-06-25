FROM python:3.10-slim

RUN apt-get update && apt-get install -y curl \
  && curl -sSL https://pdm.fming.dev/install-pdm.py | python3 - \
  && apt-get clean

WORKDIR /app

COPY . .

ENV PATH="/root/.local/bin:$PATH"

RUN pdm install --prod

EXPOSE 8002

CMD ["pdm", "run", "python", "app.py"]
