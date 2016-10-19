load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "go_library", "go_binary")

go_prefix("github.com/simonhorlick/echo-gateway")

go_binary(
    name = "server",
    srcs = ["server.go"],
    deps = [
        "//protos:go_default_library",
        "@com_github_golang_glog//:go_default_library",
        "@com_github_grpc_ecosystem_grpc_gateway//runtime:go_default_library",
        "@org_golang_google_grpc//:go_default_library",
        "@org_golang_x_net//context:go_default_library",
    ],
)
