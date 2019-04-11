# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "junit_platform_commons",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/apiguardian:apiguardian_api",
        "//external:jar/org/junit/platform/junit_platform_commons",
    ],
)

java_library(
    name = "junit_platform_engine",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":junit_platform_commons",
        "//3rdparty/jvm/org/apiguardian:apiguardian_api",
        "//3rdparty/jvm/org/opentest4j",
        "//external:jar/org/junit/platform/junit_platform_engine",
    ],
)

java_library(
    name = "junit_platform_launcher",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":junit_platform_engine",
        "//3rdparty/jvm/org/apiguardian:apiguardian_api",
        "//external:jar/org/junit/platform/junit_platform_launcher",
    ],
)

java_library(
    name = "junit_platform_runner",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":junit_platform_launcher",
        ":junit_platform_suite_api",
        "//3rdparty/jvm/junit",
        "//3rdparty/jvm/org/apiguardian:apiguardian_api",
        "//external:jar/org/junit/platform/junit_platform_runner",
    ],
)

java_library(
    name = "junit_platform_suite_api",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":junit_platform_commons",
        "//3rdparty/jvm/org/apiguardian:apiguardian_api",
        "//external:jar/org/junit/platform/junit_platform_suite_api",
    ],
)
