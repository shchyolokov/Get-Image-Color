# Get-Image-Color
Определение преобладающего цвета в изображении
# Применение
<?
require_once "getImageColor.php";// подключаем файл со скриптом
$img = new GeneratorImageColorPalette();
$colors = $img->getImageColor('../Джессика Альба/wallpapers/446d83b66ae6e290d6c61cb86061d9db.jpg', 10, $image_granularity = 5);
print_r($colors);
?>
