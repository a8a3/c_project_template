project(
    'test_c_proj', ['c', 'cpp'],
    default_options : ['c_std=c11', 'cpp_std=c++20'],
    version: '0.0.1'
)

sources = [
    'src/main.c'
]

incdir = include_directories('include')

executable(
    meson.project_name(), 
    sources,
    include_directories: incdir
)

# unit tests
subdir('test')