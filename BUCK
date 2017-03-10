include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'crow',
  header_only = True,
  header_namespace = '',
  exported_headers = subdir_glob([
    ('include', '**/*.h'),
    ('include', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
