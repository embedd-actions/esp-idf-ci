# esp-idf-ci

Сборка проектов ESP-IDF.

## Пример настройки CI/CD

```

jobs:      
  build:
    name: Building project
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
        
      - name: make   
        uses: embedd-actions/esp-idf-ci@v4.4.3
        with: 
          IDF_TARGET: esp32

```

## Доступные версии:

```
v4.4.3
latest
```
