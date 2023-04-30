# ReLife-TR
Descripción del Repositorio del Front-End para el Sistema de Reciclaje

Este repositorio contiene el código del front-end desarrollado con React y Next.js para el sistema de reciclaje. El sistema permite a los usuarios declarar la cantidad de material que desean reciclar, generando un identificador único que se proporciona al centro de acopio asociado.

La aplicación se conecta a una API personalizada para recibir y enviar datos relacionados con el reciclaje. La API permite al centro de acopio ingresar el identificador proporcionado por el usuario y verificar si el material y peso corresponden a lo declarado. Si es correcto, el estado del reciclaje se cambia a "almacenado" y se actualiza el titular del identificador.

Cuando el centro de acopio está listo para entregar los materiales a una planta procesadora, crea un paquete que contiene los identificadores de los reciclajes en orden FIFO hasta alcanzar el valor indicado. Si el valor no coincide exactamente, se divide el último reciclaje seleccionado. Una vez creado el paquete, el centro de acopio puede validar su entrega mediante la carga de un documento de pesaje. Además, en caso de que se pierda una cantidad de material, se puede registrar una merma en el sistema.

Este repositorio proporciona la interfaz de usuario para que los usuarios declaren su cantidad de material a reciclar y sigan el proceso de reciclaje hasta la entrega a la planta procesadora. El código base está desarrollado utilizando React y Next.js, lo que permite una experiencia de desarrollo rápida y escalable.

¡Contribuciones y mejoras al sistema de reciclaje son bienvenidas!
