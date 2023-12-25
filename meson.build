project('example', 'cpp')
# Source files
src = [
    'main.cpp'
]

# Qt5 dependencies
qt5_dep = [
    dependency('Qt5Core'),
    dependency('Qt5Gui'),
    dependency('Qt5Widgets'),
]

# -fPIC required
add_project_arguments('-fPIC', language: 'cpp')

# executable file
executable('main', src, dependencies: qt5_dep)
