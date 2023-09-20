# esp-idf-ci

Building ESP-IDF projects.

## Usage

```

jobs:      
  build:
    name: Building project
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
        
      - name: make   
        uses: embedd-actions/esp-idf-ci@latest
        with: 
          IDF_TARGET: esp32

```

## Available tags

```
latest
```
