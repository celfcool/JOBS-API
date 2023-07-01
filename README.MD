#### Project Setup

In order to spin up the project, in the root create .env with these three variables, with your own values.

MONGO_URI
JWT_SECRET
JWT_LIFETIME

After that run:

```bash
npm install && npm start
```

Swagger UI

```yaml
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```
