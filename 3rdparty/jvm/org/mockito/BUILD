# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "mockito_core",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/net/bytebuddy:byte_buddy",
        "//3rdparty/jvm/net/bytebuddy:byte_buddy_agent",
        "//3rdparty/jvm/org/objenesis",
        "//external:jar/org/mockito/mockito_core",
    ],
)

java_library(
    name = "mockito_inline",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":mockito_core",
        "//external:jar/org/mockito/mockito_inline",
    ],
)
