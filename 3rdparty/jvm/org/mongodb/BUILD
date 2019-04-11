# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

java_library(
    name = "bson",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//external:jar/org/mongodb/bson",
    ],
)

scala_import(
    name = "casbah_commons_2_12_0_RC1",
    jars = [
        "//external:jar/org/mongodb/casbah_commons_2_12_0_RC1",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":mongo_java_driver",
        "//3rdparty/jvm/com/github/nscala_time:nscala_time_2_12_0_RC1",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "casbah_core_2_12_0_RC1",
    jars = [
        "//external:jar/org/mongodb/casbah_core_2_12_0_RC1",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":casbah_commons_2_12_0_RC1",
        ":casbah_query_2_12_0_RC1",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "casbah_gridfs_2_12_0_RC1",
    jars = [
        "//external:jar/org/mongodb/casbah_gridfs_2_12_0_RC1",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":casbah_core_2_12_0_RC1",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "casbah_query_2_12_0_RC1",
    jars = [
        "//external:jar/org/mongodb/casbah_query_2_12_0_RC1",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":casbah_commons_2_12_0_RC1",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

java_library(
    name = "mongo_java_driver",
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//external:jar/org/mongodb/mongo_java_driver",
    ],
)

java_library(
    name = "mongodb_driver_async",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":bson",
        ":mongodb_driver_core",
        "//external:jar/org/mongodb/mongodb_driver_async",
    ],
)

java_library(
    name = "mongodb_driver_core",
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":bson",
        "//external:jar/org/mongodb/mongodb_driver_core",
    ],
)
