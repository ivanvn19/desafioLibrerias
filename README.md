# desafioLibrerias
Readme DesafioLibrerias 
Según considero, en webs apps estilo carrito, dónde el usuario tiene que seleccionar varios productos, resulta muy util utilizar
todos los recursos visuales posibles para "resaltar" como se está desarrollando el proceso de compra y selección (enfatizar que está 
eligiendo cuando apreta algún botón, dejar en calaro el costo total de algo etc..)
Es por ello que elegí para este desafío incorporar dos librerías, que en lo personal me resultan super utiles y entretenidas.Y justamente
van reflejando visualmente el mecanismo del simulador a medida que el usuario va interactuando con él:

-Toastify: Pese a que en cada card de cada producto está puesto (ademas de la foto del equipo) el modelo y el precio. Utilicé un toastify
dentro del evento onclick que se encuentra en el bucle de seleccion de producto, para que a medida que el usuario valla seleccionando cada
equipo, una alerta visual que surge al costado superior derecho de la pantalla refuerce el modelo elegido y el precio por jornada. Para 
este alert también personalicé sus parametros visuales para que tenga la misma identidad visual que el diseño general de la web.

-Sweet Alret: Para enfatizar el monto total del costo del alquiler de equipos, y darle un "cierre" a la transacción utilicé un sweet Alert. 
Así, además de incertar el monto en el html mediante el dom, el usuario resibirá una  alerta que no podrá evitar ver, donde se indique que 
el proceso finalizó y aparezca el monto total de la cuenta (para lograrlo, coloque el swwt alert en el evento onclick del boton calcular
jornadas). Al igual que con Toastify personalicé esta alerta cambiando el color del boton, y poniendo un backgraund image blanco con textura. 
  
