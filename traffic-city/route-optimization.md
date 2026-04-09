# 3. Route optimization

_Para encontrar la ruta mas rapida, tomaremos una serie de decisiones entre dos opciones a la vez. Empezamos desde el punto A._

AB = 4;
AD = 3;

if (AB < AD) {
    menor1 = AB;
} else {
    menor1 = AD;
}

_En este caso, el menor seria AD._

DF = 2;
DJ = 6;

if (DF < DJ) {
    menor2 = DF;
} else {
    menor2 = DJ;
}

_En este caso, el menor es DF, lo que hace que terminemos nuestra ruta._

ruta = menor1 + menor2;

_ruta = 5;_
