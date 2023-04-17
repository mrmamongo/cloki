# CLoki

Console loki-like parser observer

## Usage

- single-file usage
```bash
cloki --file log.log --log_level DEBUG --module spcore
```

- multi-file usage
```bash
cloki --directory logs --log_level DEBUG --module spcore
```

- config-file usage
```json
// config.json
{
  "log_level": "DEBUG",
  "module": "spcore",
  "line_contains": "Касса"
}
```

```bash
cloki --file log.log --config config.json 
```
