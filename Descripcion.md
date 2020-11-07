Composite tiene como proposito componer objetos en forma estructura de arbol para representar jerarquias, permitiendo
que los consumidores usen de manera uniforme los objetos individuales y los objetos compuestos.

Cuando lo utilizo? cuando quiero representar una jerarquia de objetos donde pueda diferenciar entre objetos
compuestos y primitivos. 

Problema. Vamos a simular un sistema de archivos con el uso del patron de diseno estructural composite, un 
sistema de archivos cuaenta con directorios y archivos, los directorios pueden contener u otros archivos o tambien
otros directorios dentro, pudiendo representar los archivos y directorios estructurando con el uso de composite.
					-Directorio1
					     Archivo1
						 Archivo2
						 Directorio2
							Archivo2.1
					-Directorio3
						Archivo3.1
					-Archivo4
					-Archivo5
					-Directorio4
						Archivo6
						Archivo7
					-Archivo 8