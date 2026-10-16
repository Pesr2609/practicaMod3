# Usa una versión estable y compatible de PostgreSQL
FROM postgres:16-alpine

# Copia los scripts SQL al directorio de inicialización automática
COPY init.sql /docker-entrypoint-initdb.d/
COPY save_data.sql /docker-entrypoint-initdb.d/