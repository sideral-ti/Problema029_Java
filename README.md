# Devsafio 001

Crud básico de la entidad `Cliente` en un proyecto Spring Boot.

Solo utilizaremos la capa DAO y la capa controller.

Utilizaremos ClienteRepository directamente en el controller vía inyección de dependencias (DI -> Dependency injection).
Implementaremos un CRUD básico para la entidad `Cliente`, directo en la capa controller.
Crearemos 8 endpoints REST para el CRUD de la entidad `Cliente`.

Los endpoints a desarrollar son:
Create --> save() y saveAll()
Read --> findById(), findAll() y count()
Update --> update()
Delete --> deleteById() y deleteAll()

Además, crearemos las vistas con Thymeleaf para listar, crear, editar y eliminar clientes.