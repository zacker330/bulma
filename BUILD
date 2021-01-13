package(default_visibility = ["//visibility:public"])

load("@io_bazel_rules_sass//:defs.bzl", "sass_binary")

sass_binary(
    name = "bulma",
    src = "bulma-bazel.sass",
    deps = [
        "//sass/base",
        "//sass/components",
        "//sass/elements",
        "//sass/form",
        "//sass/grid",
        "//sass/helpers",
        "//sass/layout",
        "//sass/utilities",
    ],
)
