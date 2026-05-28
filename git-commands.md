# Mis comandos Git esenciales

## Primera vez en una PC nueva
git config --global user.name "C-Sorto"
git config --global user.email "csorto41@yahoo.com"
git clone https://github.com/C-Sorto/christian-learning-journey

## Rutina diaria
git pull                    # bajar cambios de GitHub
git add .                   # preparar todos mis cambios
git commit -m "mensaje"     # guardar con descripción
git push                    # subir a GitHub

## Verificar estado
git status                  # ver qué cambió
git config --global --list  # verificar mi configuración