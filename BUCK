include_defs('//BUCKAROO_DEPS')

cxx_library(
  name = 'boost-regex', 
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
    ('include/boost', '**/*.h'),
  ]),
  srcs = glob([
    'src/**/*.cpp',
  ]),
  deps = BUCKAROO_DEPS,
)
