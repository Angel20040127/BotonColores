# COMPONENTE
![image](https://github.com/user-attachments/assets/050485de-8ef6-43d3-b006-2aee83a542d8)

![image](https://github.com/user-attachments/assets/b1a7507d-26ef-4ef4-a18a-28147c8f8729)

![image](https://github.com/user-attachments/assets/32744948-d32f-4b8c-9802-93da827394c5)




# DESCRIPCION
Este boton personalizado nos permite cambiar el fondo de un JFrame, asi como el color de algunos componetes como lo son los botones, etiquetas y cuadro de texto.
El cambio de color nos permite darle un diseño mas estetico a nuestro Frame y nos ahora el tiempo de cambiarlo desde propiedades, estoo tambien aplica para los siguientes componentes botones, etiquetas y cuadro de texto.
# USOS
Puede ocuparse en cualquier proyecto para mejorar la estetica de este y sea mas atrativo para el usuario
# CODIGO
#IMPORTACIONES

![image](https://github.com/user-attachments/assets/2cf9c233-7762-4213-9fe6-f0c24410a994)

import java.awt.Color;//Se ocupa para elegir el color para el fondo del panel

import java.awt.Component;// Lo ocupamos para un método

import java.awt.Container;// Se ocupa para contener componentes

import java.awt.Dimension;// Se ocupará darle tamaño al JButton

import java.awt.Font;//La ocupamos para darle diseño a las letras del botón personalizado

import java.awt.event.MouseEvent;//Se utiliza para el evento generado por el mouseCliked

import java.awt.event.MouseListener;//Lo ocuparemos para ocupar el método mousecliked

import javax.swing.JButton;//La clase que vamos a ocupar para generar nuestro botón personalizado

import javax.swing.JColorChooser;//Lo ocuparemos para crear el color complementario

import javax.swing.JFrame;//Se ocupara en el método color componentes

import javax.swing.JLabel;//Se ocupara en el método color componentes

import javax.swing.JPanel;//Se ocupara en el método color componentes

import javax.swing.JTextField;//Se ocupara en el método color componentes

import javax.swing.SwingUtilities;

#CONSTRUCTOR

![image](https://github.com/user-attachments/assets/4e8a9774-7d9f-406a-9c4d-57bcaece7a31)

Inicializa el botón con los colores de fondo y texto predeterminados, además de establecer la fuente y el tamaño preferido. Añade un MouseListener para gestionar los eventos del ratón.

#METODOS


![image](https://github.com/user-attachments/assets/40c723de-7437-4063-a8f3-b6833d6baba4)

mouseClicked(MouseEvent e)
Este método se llama cuando se hace clic en el botón. Llama a elegirYAplicarColor() para mostrar un diálogo de selección de color y aplicar el color seleccionado al botón.

![image](https://github.com/user-attachments/assets/26383b14-056e-4ff2-8c06-078a86903783)

elegirYAplicarColor()
Muestra un diálogo de selección de color (JColorChooser) y aplica el color seleccionado como fondo del botón y su color complementario como el color del texto. También cambia los colores de los componentes contenidos en el contenedor raíz.

![image](https://github.com/user-attachments/assets/b08260a4-8f40-430a-9365-343e557336a0)

calcularComplementario(Color color)
Calcula y devuelve el color complementario del color proporcionado.

![image](https://github.com/user-attachments/assets/9b45bc19-9bd7-455f-92e2-3228141c2e09)

setCustomBackground(Color color)
Establece el color de fondo del botón y ajusta el color del texto al color complementario del fondo.

![image](https://github.com/user-attachments/assets/a8c5b7d4-af9e-4bf8-af29-2cf10bafb9a5)

aplicarColorComplementario()
Aplica el color complementario al texto del botón en función del color de fondo actual.

![image](https://github.com/user-attachments/assets/aeece25b-8606-4c51-999a-813813445899)

cambiarColorComponentes(Container container, Color backgroundColor, Color textColor)
Recorre los componentes del contenedor proporcionado y cambia sus colores de fondo y texto al color de fondo y color de texto proporcionados.

![image](https://github.com/user-attachments/assets/80b93d7a-2698-43ee-9d63-17f5aaafdc44)

Métodos vacíos para MouseListener
Estos métodos están presentes para cumplir con la interfaz MouseListener pero no tienen implementación:

mousePressed(MouseEvent e)

mouseReleased(MouseEvent e)

mouseEntered(MouseEvent e)

mouseExited(MouseEvent e)
