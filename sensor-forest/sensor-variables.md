
// Las variables que consideramos más relevantes para la seguridad de una ciudad fueron la luz y el ruido.


if (!luz && ruido) {
    actSospechosa = true;
} else if (luz && !ruido) {
    actSospechosa = false;
} else if (luz && ruido) {
    actSospechosa = false;
} else if (!luz && !ruido ) {
    actSospechosa = true;
}
