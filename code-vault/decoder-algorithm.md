# 3. Decoder Algorithm

_El cifrado consiste en retroceder las letras una posición para generar un mensaje encriptado._

letras[0] = {"z"};
letras[1] = {"a"};
letras[2] = {"b"};
letras[3] = {"c"};
letras[4] = {"d"};
letras[5] = {"e"};
letras[6] = {"f"};
letras[7] = {"g"};
letras[8] = {"h"};
letras[9] = {"i"};
letras[10] = {"j"};
letras[11] = {"k"};
letras[12] = {"l"};
letras[13] = {"m"};
letras[14] = {"n"};
letras[15] = {"o"};
letras[16] = {"p"};
letras[17] = {"q"};
letras[18] = {"r"};
letras[19] = {"s"};
letras[20] = {"t"};
letras[21] = {"u"};
letras[22] = {"v"};
letras[23] = {"w"};
letras[24] = {"x"};
letras[25] = {"y"};

desencriptarPalabra (palabra[i]) {
    for (int i = 0; i < palabra.length; i++) {
        palabra[i] = letras[palabra[i]-1];
    }
}

_Por ejemplo:_

_i - 1 = h_
_p - 1 = o_
_m - 1 = l_
_b - 1 = a_
_ipmb = hola_
