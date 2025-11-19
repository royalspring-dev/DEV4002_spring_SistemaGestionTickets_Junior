# `ROYAL SPRING` Sistema de Gestión de Tickets (Nivel Junior)

## Sistema de gestión de tickets para ver, crear, actualizar y eliminar toda clase de tickets. Ídem para Categoría y SubCategoría (Clásico CRUD) y finalmente desarrollaremos una vista para gestionar nuestros tickets.

### Entidades
- Categoria 
  - Una Categoria puede tener muchas SubCategorias (relación @OneToMany)
- SubCategoria
  - Muchas SubCategorias pueden tener una sola Categoria (relación @ManyToOne)
- Tickets (3 enums: Stars, Status y Valoracion)
  - Muchos Tickets pueden tener una sola SubCategoria (relación @ManyToOne)
  - Enums: Status, Stars y Valoracion

### Stack Tech
- Springboot 4.0.0
- Java 25
- Spring Data JPA / Hibernate (ORM Object Relations Mapping)
- H2 Database
- Postgres v16
- Thymeleaf
- Bootstrap 5.3.2
- Lombok
- Validations
- Maven
- Git y Github (VCS version control system)

### Comandos principales de Git

### Git Add
```bash
git add .
```

### Git Commit
```bash
git commit -m "COMENTARIO"
```

### Git Push
```bash
git push origin main 
```

