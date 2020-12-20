# ARQUIVO CONTENTO MIXINS SASS ÚTEIS PARA DESENVOLVIMENTO FRONTEND

# AUTHOR - MAT RAMALHO

* [![MR Badge](https://img.shields.io/badge/MR-matheusramalho-B5838D?style=flat-square&labelColor=E5989B&logo=MR&logoColor=white&link=https://matheusramalho.dev)](https://matheusramalho.dev)
* [![Github Badge](https://img.shields.io/badge/-Github-B5838D?style=flat-square&labelColor=E5989B&logo=Github&logoColor=white&link=https://github.com/MatheusRamalho)](https://github.com/MatheusRamalho)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-B5838D?style=flat-square&labelColor=E5989B&logo=twitter&logoColor=white&link=https://twitter.com/theu_ramalhoo)](https://twitter.com/theu_ramalhoo)
[![Instagram Badge](https://img.shields.io/badge/-Instagram-B5838D?style=flat-square&labelColor=E5989B&logo=instagram&logoColor=white&link=https://instagram.com/theu_ramalhoo)](https://instagram.com/theu_ramalhoo)

# SASS

# Compila
    sass assets/sass/style.scss assets/css/style.css

# Compila comprimido
    sass assets/sass/style.scss assets/css/style.css --style compressed

# Compila sem o arquivo map
    sass assets/sass/style.scss assets/css/style.css --no-source-map

# Compila sem o arquivo map e na versão comprimida
    sass assets/sass/style.scss assets/css/style.css --no-source-map --style compressed

# Monitora um arquivo e envia para o arquivo destino
    sass --watch style.scss style.css
    sass --watch style.scss style.css --no-source-map --style compressed

# Monitora todos os arquivos da pasta e envia para pasta de destino
    - O arquivo sasse o css tem que ter o mesmo nome.
    sass --watch assets/sass:assets/css
    sass --watch assets/sass:assets/css --no-source-map --style compressed