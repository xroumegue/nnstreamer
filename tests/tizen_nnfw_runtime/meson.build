unittest_nnfw_runtime_raw = executable('unittest_nnfw_runtime_raw',
  'unittest_tizen_nnfw_runtime_raw.cc',
  dependencies: [glib_dep, gst_dep, nnstreamer_dep, gtest_dep, nnfw_plugin_dep, nnstreamer_capi_dep, unittest_util_dep],
  install: get_option('install-test'),
  install_dir: join_paths(unittest_install_dir,'tests'),
)

test('unittest_nnfw_runtime_raw', unittest_nnfw_runtime_raw, env: testenv)
