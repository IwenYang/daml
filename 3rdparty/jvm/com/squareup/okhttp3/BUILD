# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "okhttp",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/com/squareup/okio",
        "//external:jar/com/squareup/okhttp3/okhttp",
    ],
)

java_library(
    name = "okhttp_urlconnection",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":okhttp",
        "//external:jar/com/squareup/okhttp3/okhttp_urlconnection",
    ],
)
