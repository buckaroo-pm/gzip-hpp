prebuilt_cxx_library(
  name = 'gzip-hpp', 
  header_namespace = 'gzip', 
  header_only = True, 
  exported_headers = subdir_glob([
    ('include/gzip', '**/*.hpp'), 
  ]), 
  deps = [
    'buckaroo.github.buckaroo-pm.madler-zlib//:zlib', 
  ], 
  visibility = [
    'PUBLIC', 
  ], 
)
