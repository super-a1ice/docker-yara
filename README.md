# docker-yara

## Getting Started

```bash
$ git clone https://github.com/Yara-Rules/rules
$ docker run --rm -v $(pwd)/rules:/rules:ro \
                  -v /path/to/malware:/malware:ro \
                  tatsui/yara /malware/malware.exe
```

