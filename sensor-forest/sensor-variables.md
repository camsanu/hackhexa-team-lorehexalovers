
// Las variables que consideramos más relevantes para la seguridad de una ciudad fueron la luz y el ruido.
// Los crimenes suelen ser camuflajeados por la poca visibilidad y el ruido, asi que una ciudad segura es una ciudad bien alumbrada y callada.
// Por ejemplo: Es menos probable que haya actividad sospechosa en una calle abierta en pleno día, a contrario de una calle cerrada en la noche.

if (!luz && ruido) {
    actSospechosa = true;
} else if (luz && !ruido) {
    actSospechosa = false;
} else if (luz && ruido) {
    actSospechosa = false;
} else if (!luz && !ruido ) {
    actSospechosa = true;
}