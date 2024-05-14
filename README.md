Bem-vindo ao projeto ao Projeto Northwind!



```yaml
northwind:
  outputs:
    dev:
      dataset: northwind
      job_execution_timeout_seconds: 300
      job_retries: 1
      keyfile: path/to/keyfile.json
      location: US
      method: service-account
      priority: interactive
      project: <project_id>
      threads: 1
      type: bigquery
```

