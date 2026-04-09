# 2. Sensor rules

threshAlarma = 5;
_La alarma se activara una vez los factores de actividad sospechosa sumen 5._

factorActual = 0;

if (!luz) {
    factorActual += 3;
} else if (luz) {
    factorActual -= 3;
}

_La luz es un factor protector, por ende, el que este prendida añade seguridad, por ende resta actividad sospechosa._

if (ruido) {
    factorActual += 2;
}

if (movimiento) {
    factorActual += 1;
}

if (factorActual >= threshAlarma) {
    sonarAlarma();
}
