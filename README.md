# CourseWork2025
## Файл workCourseV2.zip

# зависимости X11 + XRANDR
sudo apt update
sudo apt install libx11-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev libgl1-mesa-dev libglu1-mesa-dev

# зависимости Fyne
sudo apt install libgtk-3-dev libgl-dev

# Установка
1) Скачать zip, 
2) go mod tidy
3) go buiild ./cmd/app
4) ./app
