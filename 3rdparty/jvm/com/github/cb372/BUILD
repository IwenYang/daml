# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "scalacache_caffeine",
    jars = [
        "//external:jar/com/github/cb372/scalacache_caffeine_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":scalacache_core",
        "//3rdparty/jvm/com/github/ben_manes/caffeine",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "scalacache_core",
    jars = [
        "//external:jar/com/github/cb372/scalacache_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang:scala_reflect",
        "//3rdparty/jvm/org/slf4j:slf4j_api",
    ],
)
