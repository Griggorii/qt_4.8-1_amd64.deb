# qt_4.8-1_amd64.deb
qt_4.8-1_amd64.deb ubuntu linux

sudo apt install libpng12-0

sudo apt purge qtchooser -y

download qt_4.8-1_amd64.deb https://drive.google.com/open?id=1-Lz9-qBLzFa7hupNPUFBPOqIGgOAetiX

sudo dpkg qt_4.8-1_amd64.deb

sudo cp libpng12.so.0 /usr/lib/x86_64-linux-gnu   <--- ubuntu 19.04 variant

qtdemo

Example video demonstration run qt4 https://radikal.ru/video/yZVAgeBuvsJ pls browser firefox

Костыльное решение для 19.04 sudo cp libpng12.so.0 /usr/lib/x86_64-linux-gnu на деле это переименованный libpng12.so.0.54.0
дело в том что я не однократно предупреждал что стабильна пока только 18.10 , но раз я разгадал задачу то там наверху давайте работаите , а не выпускаите овер сотню дистрибутивов что бы кого то там обогнать все равно 16.04 не обгоните по скорости , а папки в ссылки превращать не хорошая идея после каких нибудь make install система может просто сказать что приехала на конечную вот из за этих ссылочных папок.

Скорее всего лучше начинать костылить чем выпускать новые системы каждый год с помощью костылей можно так же задействовать разные версии компиляторов и так далее , но я вам даю гарантию что пока так не сделают а, будут платить 100-150 К всяким погромистам которые будут апи делать просто жизненно не запускаемым по этому рекомендую донатить костылистам чем таким чудо иженеро техникам из за которых потом qt4 5 ошибка загрузки модуля и тому подобное , надо уже окончательно прояснить что гуй можно итак костылить , а не пересобирать его по тысячу раз. Простыми словами когда же это кончится и система уже будет закреплена и летать и потреблять 600-700 Мб.
