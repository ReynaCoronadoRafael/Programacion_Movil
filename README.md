# Programacion_Movil
/**
 * Reyna Coronado Rafael 6NV60
 */

fun calcularPendiente(x1: Double, y1: Double, x2: Double, y2: Double): Double{
    return (y2 - y1) / (x2 - x1)
}

fun main(){
    val x1 =4.0
    val y1 =3.0
    val x2 =-3.0
    val y2 =-2.0

    val pendiente = calcularPendiente(x1, y1, x2, y2)

    println ("La pendiente es: $pendiente")
}
