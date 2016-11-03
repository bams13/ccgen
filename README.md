# CCGen
Generador de tarjetas de credito con check incluido.

##Uso
./ccgen.py [-b] <bin> [Opciones]
./ccgen.py -h      Este mensaje de ayuda

Opciones:
    -b, --bin          Formato de bin
    -u, --cantidad     Cantidad de tarjetas a generar
    -c, --ccv          Genera un numero ccv
    -d, --date         Genera una fecha de expiracion
    -g, --guardar      Guarda las tarjetas en un archivo

Recuerda que el formato del bin es: xxxxxxxxxxxxxxxx y consta de 16 digitos
Todas las tarjetas de credito generadas son validadas(check)
