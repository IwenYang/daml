# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "scaffeine",
    jars = [
        "//external:jar/com/github/blemale/scaffeine_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/com/github/ben_manes/caffeine",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_java8_compat",
    ],
)
