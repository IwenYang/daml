# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "diffson_core",
    jars = [
        "//external:jar/org/gnieh/diffson_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "diffson_spray_json",
    jars = [
        "//external:jar/org/gnieh/diffson_spray_json_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":diffson_core",
        "//3rdparty/jvm/io/spray:spray_json",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
