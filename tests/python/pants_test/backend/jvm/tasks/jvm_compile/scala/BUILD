# Copyright 2017 Pants project contributors (see CONTRIBUTORS.md).
# Licensed under the Apache License, Version 2.0 (see LICENSE).


python_tests(
  name='scalac_plugin_integration',
  sources=['test_scalac_plugin_integration.py'],
  dependencies=[
    'tests/python/pants_test/backend/jvm/tasks/jvm_compile:base_compile_integration_test',
    'examples/src/scala/org/pantsbuild/example:scalac_directory',
  ],
  timeout = 640,
  tags = {'integration', 'partially_type_checked'},
)
