# nominaenplanillas
Creación de una nomina de asesores de seguros con integración de planillas de diferentes aseguradoras.

# Contexto 
En el sector asegurador, exixten multiples empresas de seguros y cada una ofrece diferentes tipos de pólizas al cliente.
Cada póliza tiene una comisión para el vendedor ( por eso se les suele llamar comisionista), que equivale a un porcentaje según el servicio que se ofrece.
Un buen vendedor con experiencia normalmente le da al cliente varias alternativas de las diferentes compañías de seguros
que encontrara en el mercado, para dejarle un buen ramillete al cliente de cual seleccionar según sus necesidades, 
presupuesto y situación especifíca. 
Y muchas agencias suelen contratar muchos vendedores para poder ofrecer una mayor oferta, beneficios y dar a los clientes
una mejor experiencia. 
Al final del mes, se realiza el pago de las comisiones y estas deben ser repartidas a cada asesor de seguros. Juntar todas las pólizas vendidas por cada
aseguradora y luego distribuirlas por cada asesor, requiere un orden adecuado, cuidadoso y detallista que permita generar una planilla a cada asesor. 
La suma de todo dará el valor de los ingresos que le entran al banco a la agencia y esto debe ser repartido de tal forma que cada uno reciba exactamente 
el valor que le corresponde. 

# Solución propuesta
La primera solución que se me ocurrio fue la siguiente:
1. Crear un archivo reposiorio de todas las planillas discriminadas por cada aseguradora
2. Identificar cada una de las pólizas quien es el asesor de seguro que vendió esa póliza identificando por el nombre del cliente.
3. Recorrer el histórico para encontrar algunas pólizas que se venden periodicamente y asignarlas al asesor.
4. Definir el valor de las comisiones que le corresponde a cada asesor.
5. Luego de verificar que todas las pólizas tienen el asesor y el % de comisión, se procede a organizar en orden alfabetico por asesor y separar por cada asesor las que esten  a su nombre. Se totaliza la planilla y se envia al asesor.
6. Generar un resumen de pagos donde se muestre por cada asesor cuanto se le debe pagar, esto deberá incluir los descuentos en retención en la fuente.
