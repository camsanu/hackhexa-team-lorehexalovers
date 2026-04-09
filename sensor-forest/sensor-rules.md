// Aqui estan los datos del problema.

threshAlarma = 5;
factorActual = 0;
// La alarma se activara una vez los factores de actividad sospechosa sumen 5.

if (!luz) {
    factorActual += 3;
} else if (luz) {
    factorActual -= 3;
}

// La luz es un factor protector, por ende, el que este prendida añade seguridad, por ende resta actividad sospechosa.

if (ruido) {
    factorActual += 2;
} 

if (movimiento) {
    factorActual += 1;
}

if (factorActual >= threshAlarma) {
    sonarAlarma();
}