git_repository(
    name = "io_bazel_rules_go",
    remote = "https://github.com/bazelbuild/rules_go.git",
    tag = "0.2.0",
)
load("@io_bazel_rules_go//go:def.bzl", "go_repositories", "new_go_repository")

go_repositories()

new_go_repository(
    name = "com_github_golang_glog",
    commit = "23def4e6c14b4da8ac2ed8007337bc5eb5007998",
    importpath = "github.com/golang/glog",
)

new_go_repository(
    name = "com_github_grpc_ecosystem_grpc_gateway",
    commit = "7ba755f85a3dc73224047317dab675b32d3a91e0",
    importpath = "github.com/grpc-ecosystem/grpc-gateway",
)

new_go_repository(
    name = "com_github_golang_protobuf",
    importpath = "github.com/golang/protobuf",
    commit = "1f49d83d9aa00e6ce4fc8258c71cc7786aec968a",
)

new_go_repository(
    name = "org_golang_x_net",
    commit = "de35ec43e7a9aabd6a9c54d2898220ea7e44de7d",
    importpath = "golang.org/x/net",
)

new_go_repository(
    name = "org_golang_google_grpc",
    tag = "v1.0.1-GA",
    importpath = "google.golang.org/grpc",
)
