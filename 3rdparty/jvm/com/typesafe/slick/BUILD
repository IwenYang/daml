# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "slick",
    jars = [
        "//external:jar/com/typesafe/slick/slick_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/com/typesafe:config",
        "//3rdparty/jvm/org/reactivestreams:reactive_streams",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "slick_hikaricp",
    jars = [
        "//external:jar/com/typesafe/slick/slick_hikaricp_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":slick",
        "//3rdparty/jvm/com/zaxxer:HikariCP",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
