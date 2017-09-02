# Mantenga su wordpress seguro

## Anticuado != Vulnerable
No usar cosas por defecto o de dominio público

La vulnerabilidad es más un problema de los plugins que de wordpress.

Contraseñas:
### Fact: no nos gustan las contraseñas
Asuma que su contraseña no es segura, no la use en todos los servicios, wordpress, ftp, etc

Use `haveibeenpwned` para saber si su contraseña ha sido vulnerada.

tener cuidado con los hosts y servidores usados,, pueden estar comprometidos o infectados.

Cuidarse de contaminación cruzada (Uno o varios sitios comparten hosting y uno se contagia, esparciendo el virus.) Se vuelve muy difícil de limpiar.

Cuidar el acceso a los `backdors`, no necesariamente son para hacer daño, pero pueden prestarse para ello.

Cuidars de las inyecciones, que añaden contenido no deseado, como iframes, redirecciones, código malicioso, que genera dinero a quienes las realizan.

## Recomendaciones
1. No utilice valores predeterminados.
2. No utilizar admin como nombre de usuario.
3. No usar `wp_` como prefijo de las bases de datos.
4. Utiliza contraseñas fuertes y únicas.
5. Utilizar una frase larga de contraseña.
6. Utilizar administradores de contraseñas.
7. Siempre hacer 2 cuentas en su site de wordpress (principio de minímo privilegio, no utilizar cuenta de administrador a menos que sea necesario).
8. Mantener todo actualizado (Agresores les gusta atacar sitios no actualizados).
9. Mantente fuera de los radares de los agresores (Teniendo todo axctualizado).
10. Mantén copias de seguridad frecuentes.
11. Retira plugins o temas no utilizados.
12. Utiliza un servidor dedicado o vps.
13. Hacer solo una instalación de wordpress por servidor.
14. Utiliza cifrado SSL (Previene la intercepción de tu tráfico, es casi obligatorio google lo usa para determinar los search results), se puede utilizar cloudfare para instalar el cifrado SSL.

## Conclusión

Manejar el riesgo de tus sitios. Es imposible tener una protección completa debido a lo cambiante que es el ambiente.

Utiliza las recomendaciones que puedas.

## Preguntas
### Recomendaciones cuando el sitio ha sido vulnerado
1. Determinar el tipo de infección
2. Determinar si es del server, o del site.
3. Buscar por infecciones en la base de datos.