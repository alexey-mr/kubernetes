package(default_visibility = ["//visibility:public"])

licenses(["notice"])

load(
    "@io_bazel_rules_go//go:def.bzl",
    "go_library",
)

go_library(
    name = "go_default_library",
    srcs = ["interface.go"],
    tags = ["automanaged"],
    deps = [
        "//pkg/client/informers/informers_generated/certificates/internalversion:go_default_library",
        "//pkg/client/informers/informers_generated/certificates/v1alpha1:go_default_library",
        "//pkg/client/informers/informers_generated/internalinterfaces:go_default_library",
    ],
)
