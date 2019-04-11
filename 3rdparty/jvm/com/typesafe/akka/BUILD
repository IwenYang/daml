# Do not edit. bazel-deps autogenerates this file from dependencies.yaml.
# See 3rdparty/README.md
load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library")
load("@io_bazel_rules_scala//scala:scala_import.bzl", "scala_import")

scala_import(
    name = "akka_actor",
    jars = [
        "//external:jar/com/typesafe/akka/akka_actor_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        "//3rdparty/jvm/com/typesafe:config",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/scala_lang/modules:scala_java8_compat",
    ],
)

scala_import(
    name = "akka_http",
    jars = [
        "//external:jar/com/typesafe/akka/akka_http_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":akka_http_core",
        ":akka_stream",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_http_core",
    jars = [
        "//external:jar/com/typesafe/akka/akka_http_core_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":akka_parsing",
        ":akka_stream",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_http_spray_json",
    jars = [
        "//external:jar/com/typesafe/akka/akka_http_spray_json_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":akka_http",
        ":akka_stream",
        "//3rdparty/jvm/io/spray:spray_json",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_http_testkit",
    jars = [
        "//external:jar/com/typesafe/akka/akka_http_testkit_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":akka_http",
        ":akka_stream_testkit",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_parsing",
    jars = [
        "//external:jar/com/typesafe/akka/akka_parsing_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":akka_actor",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_protobuf",
    jars = [
        "//external:jar/com/typesafe/akka/akka_protobuf_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_slf4j",
    jars = [
        "//external:jar/com/typesafe/akka/akka_slf4j_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":akka_actor",
        "//3rdparty/jvm/org/scala_lang:scala_library",
        "//3rdparty/jvm/org/slf4j:slf4j_api",
    ],
)

scala_import(
    name = "akka_stream",
    jars = [
        "//external:jar/com/typesafe/akka/akka_stream_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":akka_actor",
        ":akka_protobuf",
        "//3rdparty/jvm/com/typesafe:ssl_config_core",
        "//3rdparty/jvm/org/reactivestreams:reactive_streams",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_stream_testkit",
    jars = [
        "//external:jar/com/typesafe/akka/akka_stream_testkit_2_12",
    ],
    visibility = [
        "//visibility:public",
    ],
    exports = [
        ":akka_stream",
        ":akka_testkit",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)

scala_import(
    name = "akka_testkit",
    jars = [
        "//external:jar/com/typesafe/akka/akka_testkit_2_12",
    ],
    visibility = [
        "//3rdparty/jvm:__subpackages__",
    ],
    exports = [
        ":akka_actor",
        "//3rdparty/jvm/org/scala_lang:scala_library",
    ],
)
