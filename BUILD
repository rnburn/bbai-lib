load(
    "//bazel:stackext_build_system.bzl",
    "stackext_package",
    "stackext_cc_library",
)

stackext_package()

stackext_cc_library(
    name = "stackext_lib",
    hdrs = glob(["include/stackext/*.h"]),
    strip_include_prefix = "include",
)
