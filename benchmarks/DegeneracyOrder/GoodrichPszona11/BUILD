cc_library(
  name = "DegeneracyOrder",
  hdrs = ["DegeneracyOrder.h"],
  deps = [
  "//gbbs:bucket",
  "//gbbs:gbbs",
  "//gbbs/pbbslib:dyn_arr",
  "//pbbslib:integer_sort",
  "//pbbslib:kth_smallest",
  "//pbbslib:random",
  ]
)

cc_binary(
  name = "DegeneracyOrder_main",
  srcs = ["DegeneracyOrder.cc"],
  deps = [":DegeneracyOrder"]
)

package(
  default_visibility = ["//visibility:public"],
)
