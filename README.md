На русском:
1. start() - Начальная функция, которая приветствует пользователя и просит указать тему презентации.
get_tema() - Получает тему презентации от пользователя и запрашивает количество слайдов.
get_slides_count() - Получает и проверяет количество слайдов (от 3 до 10), затем запрашивает язык презентации.
get_language() - Получает язык презентации и запускает процесс создания.
create_presentation() - Основная функция создания презентации:
Генерирует текст для каждого слайда используя Gemini AI
Создает изображения через Stability AI
Формирует слайды с текстом и изображениями
Сохраняет и отправляет готовую презентацию пользователю
In English:
start() - Initial function that greets the user and asks for the presentation topic.
get_tema() - Receives the presentation topic from the user and requests the number of slides.
get_slides_count() - Receives and validates the number of slides (from 3 to 10), then asks for the presentation language.
get_language() - Gets the presentation language and initiates the creation process.
create_presentation() - Main presentation creation function:
Generates text for each slide using Gemini AI
Creates images through Stability AI
Forms slides with text and images
Saves and sends the completed presentation to the user
