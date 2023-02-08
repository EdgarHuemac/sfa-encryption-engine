## Proyecto de servicio social del Departamento de Ciberseguridad de Gobierno Digital de Michoacán ##
#### Motor de encriptación en PHP ####

Se debe crear una clase en PHP para encriptar y desencriptar datos. El objetivo de esta clase será brindar una capa adicional de privacidad, a nivel de aplicación, a los datos de las diversas bases de datos de Gobierno Digital. Se deben cumplir los siguientes requerimientos:

- El proyecto tiene que ser una clase (fácilmente importable)
- La clase debe ofrecer, al menos, 2 algoritmos de encriptación.
- La clase debe tener los métodos para cada algoritmo:
	- Encriptar: El método encritar debe incluir "input sanitization". 
	- Desencriptar

- Al menos 1 de los 2 algoritmos (de preferencia los 2) debe ofrecer "salting".
- Al menos 1 de los 2 algoritmos (de preferencia los 2) deben ofrecer encriptación por medio de "key".
	- La "key" debe manejarse por medio de variables de entorno Y archivos .env
- Al menos 1 de los 2 algoritmos (de preferencia los 2) deben de ser "simétricos" size(input) = size(output)
- Se debe manejar en un repositorio (Github, Gitlab, Bitbucket)

#### Próximamente... ####
Puntos extra esto lo replican para Java (Java SE 17 y superior) y Python 3 



