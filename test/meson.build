sources = [
    'src/test.cpp'
]

# dependencies
gtest = subproject('gtest')
# gtest with main
gtest_dep = gtest.get_variable('gtest_dep')
gtest_main_dep = gtest.get_variable('gtest_main_dep')
# threads lib
thread_dep = dependency('threads')

executable(
    'some_test', 
    sources,
    dependencies : [
        gtest_dep,
        gtest_main_dep,
        thread_dep
    ]
)

# TODO:
# unit tests