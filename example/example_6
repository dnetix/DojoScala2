/*
	Currying or returning functions special syntax in scala
*/
object example extends App {

	// Retorna una funcion que realiza la operacion entre los enteros de A y B
	def sum(f: Int => Int)(a: Int, b: Int): Int = {
		if (a > b) 0 else f(a) + sum(f)(a + 1, b)
	}
	
	// Retorna el factorial del entero enviado
	def factorial(x: Int) : Int = {
		if (x <= 0) 1 else factorial(x -1)
	}

	// De esta manera se evita la definicion de las funciones especificas y son usadas como

	// sum(x => x * x * x)(1, 10)
	// sum(factorial)(1, 10)


}