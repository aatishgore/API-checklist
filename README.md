# API checklist
Checklist for API development

- [ ] Follow consistency while writing apis like use same casing for fields, parameters and resources. Also, use singular or plural for resource names and have common logic for authentication and authorization
- [ ] Use UTC time in backend, local time should be managed in frontend
- [ ] Create health checkpoint for every microservice
- [ ] API versioning
- [ ] HTTP Codes like 200 for success, 201 for created, 400 for bad request, 401 for unauthorized, 500 for internal error, 404 for Not found and many more
- [ ] Use HTTP methods like POST for create resource, GET for reading resource, PATCH for partial update, PUT for full update and DELETE for deleting resource
- [ ] self-explanatory name conventions like GET /posts/{id}, user.first_name
- [ ] standardized error and response structure
- [ ] Use pagination



