load("@io_bazel_rules_go//go:def.bzl", "go_prefix", "go_library", "go_binary")

package(default_visibility = ["//visibility:public"])

go_prefix("github.com/simonhorlick/echo-gateway/protos")

go_library(
    name = "go_default_library",
    srcs = [
        "echo.pb.go",
        "echo.pb.gw.go",
    ],
    deps = [
        # proto dependencies
        "@com_github_golang_protobuf//proto:go_default_library",
        # grpc gateway dependencies
        "@com_github_grpc_ecosystem_grpc_gateway//runtime:go_default_library",
        "@com_github_grpc_ecosystem_grpc_gateway//utilities:go_default_library",
        "@com_github_grpc_ecosystem_grpc_gateway//third_party/googleapis/google/api:go_default_library",
        # grpc dependencies
        "@org_golang_x_net//context:go_default_library",
        "@org_golang_google_grpc//:go_default_library",
        "@org_golang_google_grpc//codes:go_default_library",
        "@org_golang_google_grpc//grpclog:go_default_library",
    ],
)
