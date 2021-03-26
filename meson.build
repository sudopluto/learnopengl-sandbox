project('learnopengl', 'cpp', 'c')

cmplr = meson.get_compiler('cpp')

inc = include_directories('./deps/includes')

glfw_lib = cmplr.find_library('libglfw3', dirs: meson.current_source_dir() + '/deps/libs/')
dl_lib = cmplr.find_library('dl')
x11_lib = cmplr.find_library('X11')
gl_lib = cmplr.find_library('GL')
pthread_lib = cmplr.find_library('pthread')
xrandr_lib = cmplr.find_library('Xrandr')
xi_lib = cmplr.find_library('Xi')

deps = [glfw_lib, dl_lib, x11_lib, gl_lib, pthread_lib, xrandr_lib, xi_lib]

subdir('src')
