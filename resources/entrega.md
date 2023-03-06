# Notas del profesor
## Grupo A: Ambar, Derick, Pol (Trabajando)
Router GNS3

## Grupo B: Iñaki, Mustafa, Andres
cisco

## Grupo C: Manu, Xavi, Danilo (Trabajando)
PFsense

## Grupo D: Javi, Marc

# Formato de entrega
A más tardar el día 10/03/2023 se debe entregar un archivo "EquipocX.zip" (donde "X" es la letra del equipo que les corresponda) con los elementos y caracteristicas sugeridas que se indican a continuación
1. Un archivo llamado `indicaciones.txt` con las indicaciones para resolver el reto. Estructura recomendada
	- **Introducción**: Una breve párrafo indicando la descripción del problema
	- **Configuracion previa**: Serie de instrucciones para poder usar el entorno donde se realizará la prueba. Estas instrucciones deben organizarse en puntos que sean facilmente ejecutables y deben servir para que el usuario pueda comenzar a trabajar de inmediato en la resolución del problema.
	- **Pruebas/Flags**: Un listado de pruebas o flags que se deben realizar para comprobar que el reto se ha terminado satisfactoriamente. Ejemplos de ello serían: _el ping a 10.100.10.2 no debería recibir respuesta desde 172.0.0.1_, _el equipo X no debería acceder a la VLAN 1_, _Todos los equipos de la red interna deben tener conexión a internet_, etc. Se podrían incluir capturas de pantalla en caso de que sea necesario o, bien, crear 
	- **Entrega**: Instrucciones sobre cómo hacer la entrega. Por ejemplo, se debe indicar si se debe entregar un documento con capturas, texto plano de la configuración de iptables, comandos ejecutados, etc. 
	- **Tabla de puntuación**: Por cada prueba o flag que hayan definido, se debe crear una tabla de puntuación. Por ejemplo:

| Flag | Puntuación |
| ---- | ---------- |
| Configuración de VLANs | 1 punto |
| Configuración de Firewall | 1 punto | 
| Conectividad entre red interna y externa | 1 punto | 

2. Un archivo con la extensión `.gns3`. Este es el archivo que debe ejecutar el concursante. Al ejecutarlo, debe tener todos los elementos necesarios para realizar el reto.
3. `.ova` de la máquina GNS3 VM donde se encuentren los contenedores de docker necesarios para montar el firewall
4. Otros archivos `.ova` necesarios para el ejecicion. Por ejemplo, otras máquinas de Virtual Box que forman parte de la red.

# Forma de entrega
Se debe entregar un enlace de Google Drive con el zip disponible para la descarga. El correo de entrega es carlos.gonzalez@itb.cat
