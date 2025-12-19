# CourseWork2025
Файл 'workcourse V4.zip'

# зависимости X11 + XRANDR
sudo apt update
sudo apt install libx11-dev libxrandr-dev libxinerama-dev libxcursor-dev libxi-dev libgl1-mesa-dev libglu1-mesa-dev

# зависимости Fyne
sudo apt install libgtk-3-dev libgl-dev

# Установка
1) Скачать zip,
2) docker-compose up -d
3) go mod tidy
4) go build ./cmd/app
5) ./app
