# INSTALACION



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

![image](https://github.com/user-attachments/assets/b08260a4-8f40-430a-9365-343e557336a0)






