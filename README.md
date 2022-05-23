#  PROGRAMS EN C++  DE PATA JENNIFER

'Autor:Jennifer Maibe Pata Mina'

'Correo electronico: jennifer.pata.mina@utelvt.edu.ec'

'Link de video:  https://www.youtube.com/watch?v=2skcnqHdH-c'

## Nombre de los Programas

'Compara.cpp'

'CuentaMoneda.cpp'

'Laedad.cpp'

'PuntoVenta.cpp'

'SumaN.cpp'

### Descripcion de los Programas

'Compara: Es un programa que nos permite comparar 2 números y verificar cual de estos es el mayor, menor o si son iguales'

'CuentaMoneda: Es un programa que permite al usuario contar monedas de 3 denominaciones, saber cuanto es la cantidad de dinero que tiene y cuantas monedas tiene de cada denominación'

'Laedad: Es un programa que permite al usuario calcular su edad en Años Meses y Dias'

'PuntoVenta:  Es un programa que se encargara de calcular la compra de varios productos, calculando su valor bruto, sumandole el Iva a la compra y realizando un descuento adicional a la compra del usuario'

'SumaN: Es un programa encargado para que cualquier usuario en general pueda calcular los valores de varios números'

## Funcionalidad

'Compara: 

           float MJ_x,MJ_y;
	cout<<"Ingrese el valor de X: ";
	cin>>MJ_x;
	cout<<"Ingrese el valor de Y: ";
	cin>>MJ_y;

'CuentaMoneda:

                int MJ_n,MJ_c=0,MJ_c1=0,MJ_c2=0,MJ_c3=0;

	float MJ_x,MJ_a=0,MJ_a1=0,MJ_a2=0,MJ_a3=0;
	
	cout<<"Bienvenidos al Cuenta Monedas Don Naza "<<endl<<endl;
	
	cout<<"Ingrese la Cantidad de monedas a contar: "<<endl<<endl;
	cin>>MJ_n;
	
	do{
	
		cout<<"Ingrese su valor en monedas (0.10,0.25,0.50):$ "<<endl;
	        cin>>MJ_x;

'Laedad:
 
         int MJ_da,MJ_ma,MJ_aa,MJ_dn,MJ_mn,MJ_an,MJ_d,MJ_m,MJ_a;
	
	cout<<"Ingrese la Fecha Actual: Dia Mes  Año "<<endl;
	cin>>MJ_da>>MJ_ma>>MJ_aa;

	cout<<"Ingrese la Fecha de su  Nacimiento: Dia Mes  Año "<<endl;
	cin>>MJ_dn>>MJ_mn>>MJ_an;

'PuntoVenta:

              int MJ_c=0,MJ_n;

	float MJ_a=0,MJ_x,MJ_Piva,MJ_Pdsc,MJ_iva=0.12,MJ_dsc=0.10,MJ_vf;

	cout<<"Ingrese la Cantidad de Productos a Comprar: ";
	cin>>MJ_n;
	do{
		cout<<"Ingrese el valor del Producto:$ ";
		cin>>MJ_x;

'SumaN:

        int MJ_c=0,MJ_n;

	float MJ_a=0,MJ_x;

	cout<<"Ingrese la Cantidad de Números a Sumar: ";
	cin>>MJ_n;

	do{

	cout<<"Ingrese un Número: ";
	cin>>MJ_x;

### Salidas de los Programas

'Compara:

	cout<<"El valor de X: "<<MJ_x<<"es igual a Y: "<<MJ_y<<endl;
	cout<<"El valor de X: "<<MJ_x<<" es menor a Y: "<<MJ_y<<endl;
	cout<<"El valor de Y: "<<MJ_y<<" es menor a X: "<<MJ_x<<endl;

'CuentaMoneda:

	cout<<"Valor Total en Efectivo:$ "<<MJ_a<<endl<<endl;
	cout<<"Cantidad de monedas de 0.10ctvs: "<<MJ_c1<<endl;
	cout<<"Valor en Efectivo de monedas de 0.10ctvs:$ "<<MJ_a1<<endl<<endl;
	cout<<"Cantidad de monedas de 0.25ctvs: "<<MJ_c2<<endl;
	cout<<"Valor en Efectivo de monedas de 0.25ctvs:$ "<<MJ_a2<<endl<<endl;
	cout<<"Cantidad de monedas de 0.50ctvs: "<<MJ_c3<<endl<<endl;
	cout<<"Valor en Efectivo de monedas de 0.50ctvs:$ "<<MJ_a3<<endl;

'Laedad:

         cout<<"Ustd Tiene "<<MJ_a<<" años "<<MJ_m<<" meses "<<" y "<<MJ_d<<" dias "<<endl;

'PuntoVenta:

         cout<<"El Valor del Iva de su compra es: $ "<<MJ_Piva<<endl; 
		cout<<"El valor del Descuento de su Compra es: $ "<<MJ_Pdsc<<endl;
		cout<<"El Valor Total de su Compra a pagar es: $ "<<MJ_vf<<endl;

'SumaN:

       cout<<"La Suma Total es: "<<MJ_a<<endl;
