// El trafico depende de la temperatura, ya que entre mas alta la temperatura, menos personas quieren salir de su casa, lo que hace que el trafico sea mas bajo.

if (temperatura <= 20) {
    trafico = ALTO
}

if (temperatura >= 20){
    trafico = MEDIO
}

if (temperatura >= 25) {
    trafico = BAJO
}
