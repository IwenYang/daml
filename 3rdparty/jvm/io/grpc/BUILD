# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "grpc_context",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/io/grpc/grpc_context",
    ],
)

java_library(
    name = "grpc_core",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":grpc_context",
        "//3rdparty/jvm/com/google/code/findbugs:jsr305",
        "//3rdparty/jvm/com/google/code/gson",
        "//3rdparty/jvm/com/google/errorprone:error_prone_annotations",
        "//3rdparty/jvm/com/google/guava",
        "//3rdparty/jvm/io/opencensus:opencensus_api",
        "//3rdparty/jvm/io/opencensus:opencensus_contrib_grpc_metrics",
        "//3rdparty/jvm/org/checkerframework:checker_compat_qual",
        "//3rdparty/jvm/org/codehaus/mojo:animal_sniffer_annotations",
        "//external:jar/io/grpc/grpc_core",
    ],
)

java_library(
    name = "grpc_netty",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":grpc_core",
        "//3rdparty/jvm/io/netty:netty_codec_http2",
        "//3rdparty/jvm/io/netty:netty_handler_proxy",
        "//external:jar/io/grpc/grpc_netty",
    ],
)

java_library(
    name = "grpc_protobuf",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":grpc_core",
        ":grpc_protobuf_lite",
        "//3rdparty/jvm/com/google/api/grpc:proto_google_common_protos",
        "//3rdparty/jvm/com/google/guava",
        "//3rdparty/jvm/com/google/protobuf:protobuf_java",
        "//3rdparty/jvm/org/checkerframework:checker_compat_qual",
        "//external:jar/io/grpc/grpc_protobuf",
    ],
)

java_library(
    name = "grpc_protobuf_lite",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":grpc_core",
        "//3rdparty/jvm/com/google/guava",
        "//3rdparty/jvm/org/checkerframework:checker_compat_qual",
        "//external:jar/io/grpc/grpc_protobuf_lite",
    ],
)

java_library(
    name = "grpc_services",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":grpc_protobuf",
        ":grpc_stub",
        "//3rdparty/jvm/com/google/protobuf:protobuf_java_util",
        "//3rdparty/jvm/com/google/re2j",
        "//external:jar/io/grpc/grpc_services",
    ],
)

java_library(
    name = "grpc_stub",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":grpc_core",
        "//external:jar/io/grpc/grpc_stub",
    ],
)
