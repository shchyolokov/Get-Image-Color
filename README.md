# Get-Image-Color
Определение преобладающего цвета в изображении
# Применение
require_once "getImageColor.php";// подключаем файл со скриптом
$img = new GeneratorImageColorPalette();
$colors = $img->getImageColor('src', 10, $image_granularity = 5);
print_r($colors);
