load("@dnos_core//tools/build/bazel:generate_workspace.bzl", "COMPILE")

COMPILE_DEPS = COMPILE + [
    "//drivers/controller:dnos-driver-controller",
    "//drivers/onos:dnos-onos-driver-controller",


]

java_library(
    name = "dnos-services-config-service",
    srcs = glob(["*.java"]),
    visibility = ["//visibility:public"],
    deps = COMPILE_DEPS,
)