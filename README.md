# Taller1_P.O.O

1. ¿Cuál es la diferencia entre la clase CuentaBancaria y un objeto CuentaBancaria?
2. ¿Qué hace exactamente la palabra new?
3. Si tienes dos cuentas a y b y ejecutas a.consignar(1000), ¿cambia el saldo de b? Justifica tu respuesta.
4. ¿Por qué se dice que el método retirar protege el estado del objeto?
5. Propón una entidad distinta a las trabajadas e indica dos de sus atributos y dos de sus métodos.


            Respuestas

   1.Diferencia entre la clase CuentaBancaria y un objeto CuentaBancaria:
La clase CuentaBancaria es el molde o plantilla que define qué atributos y métodos tendrá una cuenta. Un objeto CuentaBancaria es una instancia concreta creada a partir de esa clase, con sus propios valores.
Por ejemplo, CuentaBancaria sería el molde y a sería una cuenta específica creada con ese molde.

2.
La palabra new se utiliza para crear un nuevo objeto a partir de una clase. Reserva espacio en memoria para ese objeto y permite inicializarlo mediante su constructor.
Por ejemplo:

CuentaBancaria a = new CuentaBancaria();

Aquí se crea una nueva cuenta y la variable a queda haciendo referencia a ese objeto.

3.
No. Si a y b son objetos diferentes, cada uno tiene su propio estado y su propio saldo. Al ejecutar a.consignar(1000), solamente se modifica el saldo de a.
Esto se debe a que los atributos de cada objeto pertenecen a su propia instancia.

4.
Porque el método puede controlar las condiciones para modificar el saldo. Por ejemplo, puede verificar que haya suficiente dinero antes de realizar el retiro. Así se evita que el saldo quede en un estado inválido, como un valor negativo cuando no está permitido. 

5.Entidad diferente: CuentaBancaria → Estudiante.

Atributos: +nombre, +edad.
Métodos: estudiar(), presentarExamen().
