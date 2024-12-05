# MLOps
Студент: <Котик Котик Котик>
Группа: РИМ-230971

## Установка

1. Установить зависимости через Poetry:
   ```bash
   poetry install
   ```
2. Запустить контейнер Docker с minio:
   ```bash
   docker compose up -d  # Или docker-compose up -d      
   ```
3. Установить права доступа:
   ```bash
   chmod +x ./pipeline.sh
   ```
4. Установка pre-commit:
   ```bash
   pre-commit install
   ```
   
5. Запустить pipeline.sh:
   ```bash
   export PYTHONPATH="$PYTHONPATH:$PWD" && ./pipeline.sh
   ```